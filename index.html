<!DOCTYPE html>
<html>
<head>
	
<script src="https://unpkg.com/axios/dist/axios.min.js"></script>
</head>
<body>
<p>
In Windows, paste this command in run window:

chrome.exe --user-data-dir="C:/Chrome dev session" --disable-web-security<p>

<p>Click the button to get your coordinates.</p>
<button onclick="getLocation()">Try It</button>
<p id="demo"></p>

<p id="first"></p>
<p id="array"></p>
<!-- 
<script>
var x = document.getElementById("demo");

function getLocation() {
    if (navigator.geolocation) {
        navigator.geolocation.getCurrentPosition(showPosition);
    } else { 
        x.innerHTML = "Geolocation is not supported by this browser.";
    }
}
 
function showPosition(position) {
    x.innerHTML = "Latitude: " + position.coords.latitude + 
    "<br>Longitude: " + position.coords.longitude;
    var l1=position.coords.latitude ;
    var l2=position.coords.longitude ; 
    console.log(l1);
    console.log(l2);
}
</script> -->
<script> 
var x = document.getElementById("demo");
function getLocation() {
    if (navigator.geolocation) {
        navigator.geolocation.getCurrentPosition(showPosition, function error(msg){alert('Please enable your GPS position future.');  

  } ,{maximumAge:600000, timeout:5000, enableHighAccuracy: true});
    } else { 
        x.innerHTML = "Geolocation is not supported by this browser.";
    }
}
 
function showPosition(position) {
	var pos = position.coords.latitude + "," + position.coords.longitude;
    
    x.innerHTML = "Latitude: " + position.coords.latitude + 
    "<br>Longitude: " + position.coords.longitude;
    var l1= position.coords.latitude ;
    var l2= position.coords.longitude ;
    console.log(position.coords.accuracy); 
    console.log(l1);
    console.log(l2);
    console.log(pos);
    geo(l1,l2);	
}
	function geo(l1,l2){
		var l ='Mumbai';
		axios.get('https://maps.googleapis.com/maps/api/place/nearbysearch/json',{
			params:{
				location:l1+' ,'+l2 ,
				keyword:'railway station',
				rankby:'distance',
				/*keyword:'railway',*/
				/*radius:'1000',*/
				key:'AIzaSyAtwUD7qYaGPkDIm7joVw49DGtGHg2LuuY'
			}

		})
	// 	function geo(l1,l2){
	// 	axios.get("https://maps.googleapis.com/maps/api/place/nearbysearch/json?location="+l1+","+l2+"&radius=500&keyword=railway+station &key= AIzaSyAtwUD7qYaGPkDIm7joVw49DGtGHg2LuuY")
		
		.then(function(response){
        	console.log("In response function");
        	console.log(response);
        	console.log("In response function");
	        var names=response.data.results[0].name;
	        document.getElementById('first').innerHTML="first element: "+names;
	
        })
	
      	.catch(function(error){
        	console.log(error);
      	})
	
		}

function showError(error) {
    switch(error.code) {
        case error.PERMISSION_DENIED:
            res.innerHTML = "User denied the request for Geolocation."
            break;
        case error.POSITION_UNAVAILABLE:
            res.innerHTML = "Location information is unavailable."
            break;
        case error.TIMEOUT:
            res.innerHTML = "The request to get user location timed out."
            break;
        case error.UNKNOWN_ERROR:
            res.innerHTML = "An unknown error occurred."
            break;
    }
}
</script>
<!-- https://maps.googleapis.com/maps/api/place/nearbysearch/json?location=-33.8670522,151.1957362&radius=500&type=restaurant&keyword=cruise&key=AIzaSyAtwUD7qYaGPkDIm7joVw49DGtGHg2LuuY
 -->

</body>
</html>
