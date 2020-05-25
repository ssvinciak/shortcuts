# Useful shortcuts for development

#### JS 

* copy to clipboard

`
var dummy = document.createElement('input');document.body.appendChild(dummy);dummy.setAttribute("id", "dummy_id");
document.getElementById("dummy_id").value=sessionStorage.getItem('item.key');
dummy.select();document.execCommand("copy");document.body.removeChild(dummy);
`
* refresh CSS

`
var links = document.getElementsByTagName("link"); for (var i = 0; i < links.length;i++) { var link = links[i]; if (link.rel === "stylesheet") {link.href += "?"; }}
`
