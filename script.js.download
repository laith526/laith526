//--------------------------------------------------------------
function iexlist(sem, iddisc, idlt, itype, key) {
    biddisc=iddisc;
    bidlt=idlt;
    bsem=sem;
    bitype=itype;
    var disc=$("#s"+sem+'k'+key).text();
    $("#disc").empty().text(disc);
    $("#scom").empty();
    var title='Заказать ';
    if (itype==3) title+='экзаменационный';
    else title+='зачетный';
    title+=' лист';
    $("#refconfdialog").dialog("option",'title',title);
    $("#refconfdialog").dialog("open");
}

function savelist() {
    var scom=$("#scom").val();
    var sdate=$("#sdate").val();
    $.ajax({
	type: "GET",
	url: "savelist.php",
	data: {sem: bsem, iddisc: biddisc, idlt: bidlt, type: bitype, scom: scom, sdate: sdate},
	async: false,
        error: function( jqXHR, textStatus, errorThrown ) {
          alert(errorThrown);
        },
	success: function(msg){ 
             alert(msg);
        }
});
}


