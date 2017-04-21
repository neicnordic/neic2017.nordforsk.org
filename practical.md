---
layout: master
include: generic
title: Practical information
---

## Practical information

Anything missing? In this case please [contact us](/contact).


### Deadlines

* 2016-12-14 Session titles final, speakers and chairs confirmed.
* 2016-12-14 Workshop tiles, formats and abstracts sent in to program committee.
* 2017-01-16 Registration opens.
* 2017-03-31 Presentation titles and abstracts sent in to program committee.
* 2017-03-31 Workshop agendas sent in to program committee.
* 2017-03-31 Recommended: Workshop organizers send out pre-workshop surveys to participants.
* 2017-03-31 Workshops communicate tech requirements to program committee.
* 2017-04-28 Recommended: Workshop organizers host pre-workshop meetings with participants.
* 2017-05-22 Presentations sent in to program committee.
* 2017-05-28 Optional: Workshop materials sent in to program committee.
* 2017-05-29 Event opens.
* 2017-06-29 Workshop report sent in to conference reporting.


### Venue

The venue is [Umeå Folkets Hus](http://www.umeafolketshus.se).

### Map
<script>
var bigmap = false;
function toggleMapSize() {
  var center = map.getCenter();
  mapcontainer = document.getElementById('mapcontainer');
  toggle = document.getElementById('map-size-toggle');
  if (bigmap) {
    mapcontainer.style.width = "400px";
    mapcontainer.style.height = "300px";
    mapcontainer.style.float = "right";
    toggle.innerHTML = "Enlarge map"
  } else  {
    mapcontainer.style.width = "90%";
    mapcontainer.style.height = "500px";
    mapcontainer.style.float = "none";
    toggle.innerHTML = "Shrink map"
  }
  bigmap = !bigmap;
  google.maps.event.trigger(map, "resize");
  map.setCenter(center);
}
</script>
<div id="mapcontainer" style="border: 1px solid black; margin-bottom: 2em; text-align: center;">
 <div id="mapwidget" style="width: 100%; height: 100%; border: 1px solid black;"></div>
 <div><a id="map-size-toggle" onClick="javascript:toggleMapSize();" style="font: small;">Enlarge map</a></div>
</div>
<!-- Replace the value of the key parameter with your own API key. -->
<script>
markers = {
  "ufh": {
    name: "Umeå Folkets Hus #NeIC2017",
    label: "N",
    position: {lat: 63.82684436766725, lng: 20.266549118138073},
    zone: 1,
    link: "https://www.google.se/maps/place/Ume%C3%A5+Folkets+Hus/@63.8261357,20.2635817,17z/data=!4m12!1m6!3m5!1s0x467c5b0c2b2bffb5:0x63c0421bed2f5a92!2sComfort+Hotel+Winn,+Ume%C3%A5!8m2!3d63.8261334!4d20.2657704!3m4!1s0x467c5b0c2a97ed89:0x39a2b1ce7ce0c4a4!8m2!3d63.8268468!4d20.2665545?hl=en"},
  "radhuset": {
    name: "Rex Rådhusets Festsal #NeIC2017 Dinner",
    label: "D",
    position: {lat: 63.82528952379491, lng: 20.2624865211792},
    zone: 1,
    link: "https://www.google.se/maps/place/Rex+R%C3%A5dhuset/@63.8252303,20.2604695,17z/data=!3m1!4b1!4m5!3m4!1s0x467c5b0c403f451b:0x57e6970530451681!8m2!3d63.825228!4d20.2626582?hl=en"},
  "winn": {
    name: "Comfort Hotel Winn",
    label: "W",
    position: {lat: 63.82613226754759, lng: 20.265772955047623},
    zone: 1,
    link: "https://www.google.se/maps/place/Comfort+Hotel+Winn,+Ume%C3%A5/@63.8261357,20.2635817,17z/data=!4m12!1m6!3m5!1s0x467c5b0c2b2bffb5:0x63c0421bed2f5a92!2sComfort+Hotel+Winn,+Ume%C3%A5!8m2!3d63.8261334!4d20.2657704!3m4!1s0x467c5b0c2b2bffb5:0x63c0421bed2f5a92!8m2!3d63.8261334!4d20.2657704?hl=en"},
  "mimer": {
    name: "Elite Hotel Mimer",
    label: "M",
    position: {lat: 63.82520236739132, lng: 20.26941161139223},
    zone: 1,
    link: "https://www.google.se/maps/place/Elite+Hotel+Mimer/@63.8252071,20.2672122,17z/data=!3m1!4b1!4m5!3m4!1s0x467c5b0ef30d1fab:0xa7d43a431cddc70e!8m2!3d63.8252048!4d20.2694009?hl=en"},
  "ume": {
    name: "U&Me Hotel",
    label: "U",
    position: {lat: 63.825155698169, lng: 20.26021169472051},
    zone: 1,
    link: "https://www.google.se/maps/place/U%26Me+Hotel/@63.8249167,20.2586882,17z/data=!4m12!1m6!3m5!1s0x467c5b0c65c1fcb1:0x52c931daddf18921!2sU%26Me+Hotel!8m2!3d63.8249167!4d20.2608769!3m4!1s0x467c5b0c65c1fcb1:0x52c931daddf18921!8m2!3d63.8249167!4d20.2608769?hl=en"},
  "airport": {
    name: "Umeå Airport",
    label: "A",
    zone: 2,
    position: {lat: 63.79329794161111, lng: 20.289001032818533},
    link: "https://www.google.se/maps/place/Ume%C3%A5+Airport/@63.7930184,20.2870913,17z/data=!4m12!1m6!3m5!1s0x467c5a4bd0eefb9b:0x5d6a5a12f7557933!2sUme%C3%A5+Airport!8m2!3d63.793016!4d20.28928!3m4!1s0x467c5a4bd0eefb9b:0x5d6a5a12f7557933!8m2!3d63.793016!4d20.28928?hl=en"},
  "sculpturepark": {
    name: "Umedalen Sculpture Park",
    label: "S",
    zone: 3,
    position: {lat: 63.83774654518536, lng: 20.15996684788513},
    link:
    "https://www.google.se/maps/place/Guided+tours+in+Umedalen+Sculpture+park/@63.8381553,20.1579393,17z/data=!4m13!1m7!3m6!1s0x0:0x0!2zNjPCsDUwJzE3LjQiTiAyMMKwMDknMzYuNSJF!3b1!8m2!3d63.838153!4d20.160128!3m4!1s0x0:0xe8e1e137c76975e5!8m2!3d63.8385511!4d20.15852?hl=en"},
};

var map, neighborhood, surroundings, greaterarea;

function initMap() {
  map = new google.maps.Map(document.getElementById('mapwidget'), {
    zoom: 14,
    center: {lat: 63.8268491, lng: 20.2643658}
  });
  var infowindow = new google.maps.InfoWindow();
  neighborhood = new google.maps.LatLngBounds();
  surroundings = new google.maps.LatLngBounds();
  greaterarea = new google.maps.LatLngBounds();
  for (var key in markers) {
    if (markers.hasOwnProperty(key)) {
      m = markers[key];
      var marker = new google.maps.Marker({
        label: m.label, position: m.position, map: map}); //, draggable: true});
      markers[key]["marker"] = marker;
      marker.addListener('click', (function(marker,content,infowindow){
        return function() {
          infowindow.setContent(content);
          infowindow.open(map,marker);
        };
      })(marker,"<b><a target='_blank' href='" + m.link + "'>" + m.label + ": " + m.name + "</a></b>",infowindow)); //_
      //marker.addListener('dragend', function() {console.log(this.getPosition().toString())});
      greaterarea.extend(marker.position);
      if (m.zone <= 2) {
        surroundings.extend(marker.position);
        if (m.zone == 1) {
          neighborhood.extend(marker.position);
        }
      }
    }
  }
}
function goToMarker(name) {
  var marker = markers[name].marker;
  for (var key in markers) {
    if (markers.hasOwnProperty(key)) {
      markers[key]["marker"].setAnimation(null);
    }
  }
  map.panTo(marker.getPosition());
}
function bounceMarker(name) {
  markers[name].marker.setAnimation(google.maps.Animation.BOUNCE);  
}
function stopMarker(name) {
  markers[name].marker.setAnimation(null);  
}
</script>
<script async defer
src="https://maps.googleapis.com/maps/api/js?key=AIzaSyCkuFwKigZgzcnX3s9Zd4yRTrtNlBS1Tsk&callback=initMap">
</script>
Click to navigate the map: <br>
<a onClick="map.fitBounds(neighborhood);">Conference neighborhood</a><br/>
<a onClick="map.fitBounds(greaterarea);">Greater area</a><br/>
<div id="map-location-list">
</div>
<script>
window.onload = function() {
  locationlist = document.getElementById("map-location-list");
  var res = locationlist.innerHTML + 'Markers: <table style>';
  for (var key in markers) {
    if (markers.hasOwnProperty(key)) {
      var m = markers[key];
      res = res + '<tr><td>' + m.label + '</td><td><a data-name="' + key + '" onClick="goToMarker(this.dataset.name);" onMouseOver="bounceMarker(this.dataset.name);" onMouseOut="stopMarker(this.dataset.name);">' + m.name + '</a><td></tr>\n';
    }
  }
  res = res + "</table>"
  locationlist.innerHTML = res;
};
</script>

### Accomodation

We have reservations in several hotels in Umeå that you can book a room at in our registration form.

### Social events

#### Opening Get Together

On the evening of the 29th May we invite all our conference participants to
join us for an opening get together at Folkets Hus between 19.00-22.00. There
will be a light meal, drinks and plenty of opportunities to meet old friends or
make new acquaintances.

#### Experience Umeå

Tuesday May 30 17:30-22:00. Choice of events (pending available seats):

* Guitar museum
* Whitewater rafting
* Shrimping boat tour
* Guided walk around Umeå
* Guided tour of the Umeå Sculpture Park
* TBA

All the social activities will have options for dinner.

#### NeIC Run

Wednesday May 31 07:00. Meet up with us outside Hotel Winn (<a href="#map" onMouseOver="bounceMarker('winn');" onMouseOut="stopMarker('winn');" onClick="map.fitBounds(neighborhood); goToMarker('winn'); return true;">map marker W</a>); at 07:00 we take off on a social 5km jog around Umeå!

#### Conference dinner

Wednesday May 31 19:00-22:00 at [Rådhusets Festsal](http://www.rexumea.com/salong/radhusets-festsal/).

### Rooms

<img src="/assets/img/venue/floor-plan-ufh.jpg" width="70%">

The conference has activities in the following rooms, with these maximum numbers of seats:

* [Idun](http://www.umeafolketshus.se/idun), 1150
* [Tonsalen](http://www.umeafolketshus.se/tonsalen), 110
* [Grim](http://www.umeafolketshus.se/grim), 104
* [Miklagård](http://www.umeafolketshus.se/miklagard), 96
* [Balder](http://www.umeafolketshus.se/balder), 95
* [Loke](http://www.umeafolketshus.se/loke), 89
* [Embla](http://www.umeafolketshus.se/embla), 54
* [Ask](http://www.umeafolketshus.se/ask), 48
* [Mimer](http://www.umeafolketshus.se/mimer), 40
* [Tor](http://www.umeafolketshus.se/tor-tyr), 12
* [Tyr](http://www.umeafolketshus.se/tor-tyr), 12

Areas:

* [Teaterfoajén](http://www.umeafolketshus.se/teaterfoajen), exhibition floor
* [Pub Freja](http://www.umeafolketshus.se/teaterfoajen), lunch area next to [Idun](http://www.umeafolketshus.se/idun) and [Teaterfoajén](http://www.umeafolketshus.se/teaterfoajen)
* [Galleriet](http://www.umeafolketshus.se/galleriet), exhibition floor
