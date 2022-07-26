# Building a 3D world in react three fiber

Build walkthrough in this Youtube video:

[![Video preview](https://img.youtube.com/vi/FGG0EeMNUl0/0.jpg)](https://www.youtube.com/watch?v=FGG0EeMNUl0)

Learn how to add 3D elements to any React website. I would recommend knowing some React basics since i will focus on the 3D aspects rather than React itself. In this video you will learn how to use "React three fiber", a React renderer built to render Three.js content. In the tutorial I will download 2 different 3D models. The first model is the earth and a second model is an airplane. The models are in the GLTF format and i will show how to convert them directly into React components using a npm utility package called "gltfjsx". I will add some animations to the earth like click to zoom and rotating to showcase geographic locations at any lon/lat coordinate pair. I will use the browser geolocation API to place the webpage user on the correct spot on earth. Finally I will connect to an API giving realtime locations of surrounding airplanes and place them correctly on the surface of the earth, sorting them by closest to the user of the webpage.

⭐️ [Video Contents](https://www.youtube.com/watch?v=pLKE2DvPxDo) ⭐️
 - [0:00](/watch?v=pLKE2DvPxDo&t=0s) Video overview 
 - [1:15](/watch?v=pLKE2DvPxDo&t=75s) Initial code walkthrough 
 - [3:32](/watch?v=pLKE2DvPxDo&t=212s) Starry background 
 - [5:30](/watch?v=pLKE2DvPxDo&t=330s) Earth model 
 - [8:47](/watch?v=pLKE2DvPxDo&t=527s) Adding lights 
 - [9:28](/watch?v=pLKE2DvPxDo&t=568s) Resizing Earth 
 - [10:38](/watch?v=pLKE2DvPxDo&t=638s) Airplane Model 
 - [15:28](/watch?v=pLKE2DvPxDo&t=928s) Map Marker Sphere 
 - [17:48](/watch?v=pLKE2DvPxDo&t=1068s) Colorizing Airplanes 
 - [22:33](/watch?v=pLKE2DvPxDo&t=1353s) Click to zoom 
 - [28:23](/watch?v=pLKE2DvPxDo&t=1703s) Rotate earth to coordinate 
 - [33:46](/watch?v=pLKE2DvPxDo&t=2026s) Geolocate user 
 - [36:25](/watch?v=pLKE2DvPxDo&t=2185s) Handle marker types 
 - [37:23](/watch?v=pLKE2DvPxDo&t=2243s) Using sample flight data 
 - [45:37](/watch?v=pLKE2DvPxDo&t=2737s) Calculate airplane direction 
 - [48:45](/watch?v=pLKE2DvPxDo&t=2925s) Store airplanes to state 
 - [49:41](/watch?v=pLKE2DvPxDo&t=2981s) Airplane distance to user 
 - [51:18](/watch?v=pLKE2DvPxDo&t=3078s) Testing finished usePlanes hook 
 - [55:33](/watch?v=pLKE2DvPxDo&t=3333s) Distance & Origin in control panel 
 - [57:23](/watch?v=pLKE2DvPxDo&t=3443s) Airplane facing direction of travel
 - [59:18](/watch?v=pLKE2DvPxDo&t=3558s) Animate switching planes and correct color 
 - [1:01:59](/watch?v=pLKE2DvPxDo&t=3719s) Fetching real planes from OpenSky 
 - [1:04:29](/watch?v=pLKE2DvPxDo&t=3869s) Fetching on an interval 
 - [1:05:47](/watch?v=pLKE2DvPxDo&t=3947s) Thanks for watching 


PUBLICATION PERMISSIONS: Daniel provided Coding Tech with the permission to republish this video on the Coding Tech channel. 
REDITS: Daniel's channel: [https://www.youtube.com/c/BarelyCoding](https://www.youtube.com/c/BarelyCoding)
