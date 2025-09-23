<!DOCTYPE html>
<html>
  <head>
    <title>AR Car View</title>
    <script src="https://aframe.io/releases/1.3.0/aframe.min.js"></script>
    <script src="https://raw.githack.com/AR-js-org/AR.js/master/aframe/build/aframe-ar.js"></script>
  </head>
  <body style="margin: 0; overflow: hidden;">
    <a-scene embedded arjs="sourceType: webcam;">
      <a-marker-camera preset="hiro">
        <a-entity
          gltf-model="url(3Dcar.glb)"
          scale="0.5 0.5 0.5"
          rotation="0 0 0"
          position="0 0 0"
        ></a-entity>
      </a-marker-camera>
      <a-camera-static />
    </a-scene>
  </body>
</html>
