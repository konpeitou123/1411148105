# 1411148105
<!DOCTYPE html>
<html>
<head>
<title>Web AR Example</title>
<script
src="https://aframe.io/releases/1.2.0/aframe.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/AR-js-
org/AR.js/aframe/build/aframe-ar.js"></script>
</head>
<body>
<a-scene embedded arjs="sourceType: webcam;">
<a-marker preset="hiro">
    <a-box position="-1 1 -3" rotation="0 50 0" width="3" height="2" color="#FCC0C7"></a-box>
    <a-sphere position="0 2 -6" radius="2.25" color="#A5BFAF"></a-sphere>
    <a-cylinder position="1 2 -3" radius="0.5" height="3" color="#4EBC97"></a-cylinder>
    <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#DFC1BF"></a-plane>
    <a-sky color="#00000"></a-sky>
</a-marker>
<a-entity camera></a-entity>
</a-scene>
</body>
</html>
