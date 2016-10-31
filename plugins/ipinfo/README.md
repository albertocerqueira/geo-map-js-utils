# IP Info
Simple API to search IP and user location data.

## Examples
You can use [see more](http://htmlpreview.github.io/?https://github.com/albertocerqueira/geo-map-js-utils/blob/master/plugins/ipinfo/examples/index.html "see more"):
```javascript
$(document).ready(function() {
	$.get("http://ipinfo.io", function (response) {
		$('#getIPinfo1').val(response.ip);
		$('#getIPinfo2').val(response.hostname);
		$('#getIPinfo3').val(response.city);
		$('#getIPinfo4').val(response.region);
		$('#getIPinfo5').val(response.country);
		$('#getIPinfo6').val(response.loc);
		$('#getIPinfo7').val(response.org);
	}, "jsonp");
});
```
  
## Contributions
[See website](https://ipinfo.io/ "See website")

## Adaptations
[Alberto Cerqueira](https://github.com/albertocerqueira/ "Alberto Cerqueira") - alberto.cerqueira1990@gmail.com  
