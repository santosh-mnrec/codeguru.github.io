<%@ Page Language="C#" AutoEventWireup="true"
 CodeFile="RightClickDisable.aspx.cs" Inherits="RightClickDisable" %>

<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">

<html xmlns="http://www.w3.org/1999/xhtml" >
<head runat="server">
   <title>Untitled Page</title>
   <script language=JavaScript>
<!--
var message="Function Disabled!";

function clickIE4(){
if (event.button==2){
alert(message);
return false;
}
}

function clickNS4(e){
if (document.layers||document.getElementById&&!document.all){
if (e.which==2||e.which==3){
alert(message);
return false;
}
}
}

if (document.layers){
document.captureEvents(Event.MOUSEDOWN);
document.onmousedown=clickNS4;
}
else if (document.all&&!document.getElementById){
document.onmousedown=clickIE4;
}

document.oncontextmenu=new Function("alert(message);return false")

// --> 
</script>

</head>
<body>
   <form id="form1" runat="server">
   <div>
 
   </div>
   </form>
</body>
</html>
<!--stackedit_data:
eyJoaXN0b3J5IjpbNTIzNDU1NDBdfQ==
-->