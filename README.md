<!DOCTYPE html>
<html>
<body>

<h1>My First Google Map</h1>

<div id="map" style="width:400px;height:400px;background:yellow"></div>

<script>
function myMap() {
    var mapOptions = {
        center: new google.maps.LatLng(51.5, -0.12),
        zoom: 10,
        mapTypeId: google.maps.MapTypeId.HYBRID
    }
var map = new google.maps.Map(document.getElementById("map"), mapOptions);
}
</script>

<script src="https://www.google.com/maps/@10.987431,106.6575998,162675m/data=!3m1!1e3"></script>

</body>
</html>
