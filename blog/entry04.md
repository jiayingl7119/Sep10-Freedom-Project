# Entry 4
##### 3/9/2026

## Context
Students were tasked to select a tool to make their Freedom Project. This could include 3D models, animations, and more. In this case, I decided to pick Aframe. A website typically used for VR. However, it could be used as a model that the user can look around the said model. This includes tinkering with shapes, their colors, and also their positions. 

## Engineering Design Process
At first, I looked at the program before I did some changing. It included a box, a sphere, and a cylinder. There was also a platform for the said objects/shapes. The starting code looking like this:
```language
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
In which, the user could copy these lines of code to make their own experience. Such as changing the color of the sphere to green or change the box's position to the left by 3. 

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
