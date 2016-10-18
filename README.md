# javascript
<html>
<head>
</head>
<body>
<script type="text/javascript">
var userAgent=navigator.userAgent;
var opera=(userAgent.indexOf('Opera')!=-1);
var ie=(userAgent.indexOf('MSIE')!=-1);
var gecko=(userAgent.indexOf('Gecko')!=-1);
var netscape=(userAgent.indexOf('Mozilla')!=-1):
var version=navigator.appVersion;
if(opera){
document.write("Opera based browser");
window.location="http://www.opera.com";
}
else if(gecko){
document.write("Mozilla based browser");
window.location="http://www.fb.com";
}
else if(netscape){
document.write("Netsacpe based browser");
window.location="http://www.netscape.com";
}
else if(ie){
document.write("IE based browser");
window.location="http://www.fb.com";
}
else{
document.write("Unknown browser");
}
document.write("<br/>Browser version info:"+version);
</script>
</body>
</html>
