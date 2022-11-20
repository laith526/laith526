if (document.all) { // Проверка старой версии IE
	alert("Система не поддерживает браузер Internet Explorer этой версии");
	window.close();
	document.location.href="/";
}

//--------------------------------------------------------------
// Устанавливает значение в SELECT'е
//--------------------------------------------------------------
function setIndexByText(id,val) {
	obj=document.getElementById(id);
	for (i=0;i<obj.length;i++) {
		if (obj.options[i].text==val) { obj.selectedIndex=i; return; }
	}
}
//--------------------------------------------------------------
// Устанавливает значение в SELECT'е
//--------------------------------------------------------------
function setIndexByValue(id,val) {
	obj=document.getElementById(id);
	for (i=0;i<obj.length;i++) {
		if (obj.options[i].value==val) { obj.selectedIndex=i; return; }
	}
}
//--------------------------------------------------------------
function my_sign() {
document.getElementById("id_sign").checked=true;
}
//--------------------------------------------------------------
function my_sign2() {
document.getElementById("id_sign2").checked=true;
}
//--------------------------------------------------------------
function set_new_value(name,value) {
obj=window.parent.document.getElementById("id_"+name+"_value");
obj.value=value;
}
//--------------------------------------------------------------
function get_checked_number(w,min,max,def) {
if (isNaN(w)) w=def; else if (w=="") w=def;
if (1*w<min) w=min;
if (1*w>max) w=max;
return(w);
}
