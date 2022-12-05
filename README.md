# **Ring-of-Destiny**
Coding 1 Final Project

## Project Overview ##

This is my final project, the theme of which is the Ring of Destiny. It describes a scenario in which, as the population continues to grow, the energy supply on earth becomes a bottleneck for human development. Attempts are made to amplify spiritual power and transform it into energy machines so that human civilisation can continue to develop at a high rate.

<br>

![1aa081e0e8eabb389d7609fdd48741b](https://user-images.githubusercontent.com/57748663/205641986-cc722455-af3d-4a18-8017-1abe1fc7fb49.png)

<br>

## Code introduction ##

### Skybox ###

<br>

I chose to use images of psycho-bionics to map the context of the story of people accessing energy through their spirits.

<br>

![09a954267d49fee369528e34ce22561](https://user-images.githubusercontent.com/57748663/205642493-308c5ceb-48b3-4423-9a4e-9dc5a3e0d6fb.png)

<br>

`const urls = [  
  'up.png',
  'left.png',  
  'middle1.png',
  'middle2.png',
  'middle2.png',
  'down.png',];`
 
 <br> 
 
 ### The circle in the centre ###

<br>
  
![998f09cefe541c7fcabfd1abdbfc3bf](https://user-images.githubusercontent.com/57748663/205646483-bec85a9d-fd9a-44d1-a1be-25c63e92cbc4.png)

<br>

`var sphereGeometry = new THREE.TorusKnotGeometry(0.5, 0.15,100, 30); `
<br>
`//const material = new THREE.MeshBasicMaterial( { color: 0xffff00 } );` 
<br>
`var sphereMesh = new THREE.Mesh(sphereGeometry, cubeMaterial1);` 
<br>
`scene.add(sphereMesh);`
