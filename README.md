# Deferred insertion media
Deferred  insertion video youtube, twitch, html5 and images

[example](https://get-web.site/insertmedia.html)

### Install:
 ```
<script src="../src/insertmedia.js"></script>
 ```
 
### Usage:
 ```
insertmedia();
 ```
 
### Use with options:
 ```
insertmedia({
  delay: 300, // delay. default: 300ms
  immediately: true, // performing a delay true/false. Immediately or one at a time every "delay" ms. default: true
  attr: 'data-insert', // Processed attribute. default: data-insert
});
 ```
 
### Add an attribute to the block where we insert the media:
 ```
data-insert='{"type" : "youtube", "src" : "https://www.youtube.com/embed/6Q6cCuSvFpI", "setting" : "autoplay=1&mute=1" }'
 ```
 
### Options:
 ```
type*: youtube , twitch , html5 , img
src*: resource url https://example.com/img.jpg
width: Width available for this type of media
height: Height available for this type of media
setting: Settings available for this type of media
(*) - required 
 ```
