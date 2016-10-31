# GEO IP DB
Simple API to search IP and user location data.

## Examples
You can use [see more](http://htmlpreview.github.io/?https://github.com/albertocerqueira/geo-map-js-utils/blob/master/plugins/geoip-db/examples/index.html "see more"):
```javascript
$(document).ready(function() {
	$.getJSON('https://geoip-db.com/json/geoip.php?jsonp=?').done(function(response) {
        $('#getIPinfo1').val(response.IPv4);
        $('#getIPinfo2').val(response.postal);
        $('#getIPinfo3').val(response.city);
        $('#getIPinfo4').val(response.state);
        $('#getIPinfo5').val(response.country_name);
        $('#getIPinfo6').val(response.latitude);
        $('#getIPinfo7').val(response.longitude);
    });
});
```
  
## Contributions
[See website](https://geoip-db.com/ "See website")

## Adaptations
[Alberto Cerqueira](https://github.com/albertocerqueira/ "Alberto Cerqueira") - alberto.cerqueira1990@gmail.com  
