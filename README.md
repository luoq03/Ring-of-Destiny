# **Ring-of-Destiny**
Coding 1 Final Project

mimicproject-link

https://mimicproject.com/code/5f339607-753c-8dbb-70c1-0dc780dd5f97


https://user-images.githubusercontent.com/57748663/205693530-9913dee0-7b66-45a8-ae83-c93b7603818e.mp4



## Project Overview ##

This is my final project, the theme of which is the Ring of Destiny(Switching views with the mouse). It describes a scenario in which, as the population continues to grow, the energy supply on earth becomes a bottleneck for human development. Attempts are made to amplify spiritual power and transform it into energy machines so that human civilisation can continue to develop at a high rate.I have tried to present this theme using a combination of sound and 3D images, allowing the interactor to experience the core of the work both aurally and visually.

<br>

![1aa081e0e8eabb389d7609fdd48741b](https://user-images.githubusercontent.com/57748663/205641986-cc722455-af3d-4a18-8017-1abe1fc7fb49.png)

<br>

## Code introduction ##

### Skybox ###

<br>

I chose to use images of psycho-bionics to map the context of the story of people accessing energy through their spirits.Many outstretched tentacles form the fabric of society.On the other hand, the texture of the neural network is enriched by the reflective material of the central circle.

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

The form at the centre is constantly rotating, representing the course of destiny dependent on never-ending resources
  
![998f09cefe541c7fcabfd1abdbfc3bf](https://user-images.githubusercontent.com/57748663/205646483-bec85a9d-fd9a-44d1-a1be-25c63e92cbc4.png)



`var sphereGeometry = new THREE.TorusKnotGeometry(0.5, 0.15,100, 30); `
<br>
`//const material = new THREE.MeshBasicMaterial( { color: 0xffff00 } );` 
<br>
`var sphereMesh = new THREE.Mesh(sphereGeometry, cubeMaterial1);` 
<br>
`scene.add(sphereMesh);`

 <br> 
 
 ### "Diamonds" scattered around ###
 
 The 24 Diamonds represent 24 hours, indicating that time rotates with the circle in the centre.
 
 ![bb6e1d31d46426d3b06e4f1db025faf](https://user-images.githubusercontent.com/57748663/205657096-ceb72fd2-353b-4ec2-84d0-c2a9543efb36.png)

Diamond1 

`var sphereGeometry2 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh2 = new THREE.Mesh(sphereGeometry2, cubeMaterial1);`

`scene.add(sphereMesh2);`

<br> 
Diamond2

`var sphereGeometry3 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh3 = new THREE.Mesh(sphereGeometry3, cubeMaterial1);`

`scene.add(sphereMesh3);`

<br> 
Diamond3

`var sphereGeometry4 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh4 = new THREE.Mesh(sphereGeometry4, cubeMaterial1);`

`scene.add(sphereMesh4);`

<br> 
Diamond4

`var sphereGeometry5 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh5 = new THREE.Mesh(sphereGeometry5, cubeMaterial1);`

`scene.add(sphereMesh5);`

<br> 
Diamond5

`var sphereGeometry6 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh6 = new THREE.Mesh(sphereGeometry6, cubeMaterial1);`

`scene.add(sphereMesh6);`

<br> 
Diamond6     

`var sphereGeometry7 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh7 = new THREE.Mesh(sphereGeometry7, cubeMaterial1);`

`scene.add(sphereMesh7);`

<br> 
Diamond7

`var sphereGeometry8 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh8 = new THREE.Mesh(sphereGeometry8, cubeMaterial1);`

`scene.add(sphereMesh8);`

<br> 
 Diamond8
 
`var sphereGeometry9 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh9= new THREE.Mesh(sphereGeometry9, cubeMaterial1);`

`scene.add(sphereMesh9);`

<br> 
 Diamond9   
`var sphereGeometry10 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh10 = new THREE.Mesh(sphereGeometry10, cubeMaterial1);`

`scene.add(sphereMesh10);`

<br> 
 Diamond10  
 
`var sphereGeometry11 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh11 = new THREE.Mesh(sphereGeometry11, cubeMaterial1);`

`scene.add(sphereMesh11);`

<br> 
 Diamond11
 
`var sphereGeometry12 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh12= new THREE.Mesh(sphereGeometry12, cubeMaterial1);`

`scene.add(sphereMesh12);`

<br> 
 Diamond12    
 
`var sphereGeometry13 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh13 = new THREE.Mesh(sphereGeometry13, cubeMaterial1);`

`scene.add(sphereMesh13);`

<br> 
Diamond13

`var sphereGeometry14 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh14 = new THREE.Mesh(sphereGeometry14, cubeMaterial1);`

`scene.add(sphereMesh14);`

<br> 
Diamond14

`var sphereGeometry15 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh15 = new THREE.Mesh(sphereGeometry15, cubeMaterial1);`

`scene.add(sphereMesh15);`

<br> 
Diamond15

`var sphereGeometry16 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh16 = new THREE.Mesh(sphereGeometry16, cubeMaterial1);`

`scene.add(sphereMesh16);`

<br> 
Diamond16

`var sphereGeometry17 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh17 = new THREE.Mesh(sphereGeometry17, cubeMaterial1);`

`scene.add(sphereMesh17);`

<br> 
Diamond17

`var sphereGeometry18 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh18 = new THREE.Mesh(sphereGeometry18, cubeMaterial1);`

`scene.add(sphereMesh18);`

<br> 
Diamond18   

`var sphereGeometry19 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh19 = new THREE.Mesh(sphereGeometry19, cubeMaterial1);`

`scene.add(sphereMesh19);`

<br> 
Diamond19

`var sphereGeometry20 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh20 = new THREE.Mesh(sphereGeometry20, cubeMaterial1);`

`scene.add(sphereMesh20);`

<br> 
Diamond20      

`var sphereGeometry21 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh21= new THREE.Mesh(sphereGeometry21, cubeMaterial1);`

`scene.add(sphereMesh21);`

<br> 
 Diamond21  
 
`var sphereGeometry22 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh22= new THREE.Mesh(sphereGeometry22, cubeMaterial1);`

`scene.add(sphereMesh22);`

<br> 
Diamond22    

`var sphereGeometry23 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh23 = new THREE.Mesh(sphereGeometry23, cubeMaterial1);`

`scene.add(sphereMesh23);`

<br> 
 Diamond23    
 
`var sphereGeometry24 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh24= new THREE.Mesh(sphereGeometry24, cubeMaterial1);`

`scene.add(sphereMesh24);`

<br> 
Diamond24     

`var sphereGeometry25 = new THREE.SphereGeometry(0.15, 15, 2);`

`var sphereMesh25 = new THREE.Mesh(sphereGeometry25, cubeMaterial1);`

`scene.add(sphereMesh25);`

 <br> 
 
 ### Revolving three circles and three revolving triangles ###
 
 The interweaving of straight lines and curves represents the possibility of different futures
 
 ![9de6d8c13992fa5c87c9e85ab79750b](https://user-images.githubusercontent.com/57748663/205663702-77a94c9b-e820-42e1-bf98-4eeaf49e6108.png)

<br> 
CircleLoop 1 

`var geometry = new THREE.TorusGeometry( 2, 0.02, 20, 100 );`

`var torus = new THREE.Mesh( geometry, cubeMaterial1);`

`scene.add( torus );`


<br> 
Triangle1

`var geometry2 = new THREE.TorusGeometry(1, 0.01, 4, 3 );`

`//const material = new THREE.MeshBasicMaterial( { color: 0xffff00 } );`

`var torus2 = new THREE.Mesh( geometry2, material1 );`

`scene.add( torus2 ); `

<br> 
CircleLoop 2

`var geometry3 = new THREE.TorusGeometry( 2, 0.02, 20, 100 );`

`//const material = new THREE.MeshBasicMaterial( { color: 0xffff00 } );`

`var torus3 = new THREE.Mesh( geometry3, cubeMaterial1 );`

`scene.add( torus3 ); `

<br> 
Triangle2

`var geometry4 = new THREE.TorusGeometry( 1, 0.01, 4, 3);`

`//const material = new THREE.MeshBasicMaterial(  );`

`var torus4 = new THREE.Mesh( geometry4, material1);`

`scene.add( torus4 );`

<br> 
CircleLoop 3

`var geometry5 = new THREE.TorusGeometry( 2, 0.02, 20, 100 );`

`//const material = new THREE.MeshBasicMaterial( { color: 0xffff00 } );`

`var torus5 = new THREE.Mesh( geometry5, cubeMaterial1 );`

`scene.add( torus5 ); `

<br> 
Triangle3

`var geometry6 = new THREE.TorusGeometry(1, 0.01, 4, 3 );`

`//const material = new THREE.MeshBasicMaterial( { color: 0xffff00 } );`

`var torus6 = new THREE.Mesh( geometry6, material1 );`

`scene.add( torus6 );`

### Object Movement ###

 `function draw() {`
  
 `torus.rotation.x += 0.005;torus.rotation.y -= 0.005;`
  
 `//torus.rotation.z += 0.005;`
  
 `//torus2.rotation.x -= 0.005;`
  
 `torus2.rotation.y += 0.005; 
 torus2.rotation.x -= 0.005;`
  
 `torus3.rotation.x -= 0.005;
 torus3.rotation.z += 0.005;`

 `torus4.rotation.x += 0.005;
 torus4.rotation.z -= 0.005;`
  
 `//torus.rotation.z += 0.005;`
  
 `//torus2.rotation.x -= 0.005;`
  
 `torus5.rotation.y += 0.005;
  torus5.rotation.z -= 0.005;`
  
 `torus6.rotation.y -= 0.005;
  torus6.rotation.z += 0.005;`
  
 ` sphereMesh.rotation.x += 0.005;
  sphereMesh.rotation.y += 0.005;
  sphereMesh.rotation.z += 0.005;`
  
 `sphereMesh2.rotation.x += 0.01;
  sphereMesh2.rotation.y += 0.01;`
  
 ` sphereMesh3.rotation.x += 0.01;
  sphereMesh3.rotation.y += 0.01;`
  
 ` sphereMesh4.rotation.x += 0.01;
  sphereMesh4.rotation.y += 0.01;`
  
 `sphereMesh5.rotation.x += 0.01;
  sphereMesh5.rotation.y += 0.01;`
  
 ` sphereMesh6.rotation.x += 0.005;
  sphereMesh6.rotation.y += 0.005;
  sphereMesh6.rotation.z += 0.005;`
  
 `sphereMesh7.rotation.x += 0.01;
  sphereMesh7.rotation.y += 0.01;`
  
 `sphereMesh8.rotation.x += 0.01;
  sphereMesh8.rotation.y += 0.01;`
  
 `sphereMesh9.rotation.x += 0.01;
  sphereMesh9.rotation.y += 0.01;`
  
 `sphereMesh10.rotation.x += 0.01;
  sphereMesh10.rotation.y += 0.01;`
  
 `sphereMesh11.rotation.y += 0.01;
  sphereMesh11.rotation.x += 0.01;`
  
 ` sphereMesh12.rotation.y += 0.01;
  sphereMesh12.rotation.x += 0.01;`
  
  `sphereMesh13.rotation.y += 0.01;
  sphereMesh13.rotation.x += 0.01;
  sphereMesh13.rotation.z += 0.01;`
  
  
  `sphereMesh14.rotation.x += 0.005;
  sphereMesh14.rotation.y += 0.005;
  sphereMesh14.rotation.z += 0.005;`
  
  `sphereMesh15.rotation.x += 0.01;
  sphereMesh15.rotation.y += 0.01;`
  
  `sphereMesh16.rotation.x += 0.01;
  sphereMesh16.rotation.y += 0.01;`
  
  `sphereMesh17.rotation.x += 0.01;
  sphereMesh17.rotation.y += 0.01;`
  
  `sphereMesh18.rotation.x += 0.01;
  sphereMesh18.rotation.y += 0.01;`
  
  `sphereMesh19.rotation.x += 0.005;
  sphereMesh19.rotation.y += 0.005;
  sphereMesh19.rotation.z += 0.005;`
  
  `sphereMesh20.rotation.x += 0.01;
  sphereMesh20.rotation.y += 0.01;`
  
  `sphereMesh21.rotation.x += 0.01;
  sphereMesh21.rotation.y += 0.01;`
  
  `sphereMesh22.rotation.x += 0.01;
  sphereMesh22.rotation.y += 0.01;`
  
  `sphereMesh23.rotation.x += 0.01;
  sphereMesh23.rotation.y += 0.01;`
  
  `sphereMesh24.rotation.y += 0.01;
  sphereMesh24.rotation.x += 0.01;`
  
  `sphereMesh25.rotation.y += 0.01;
  sphereMesh25.rotation.x += 0.01;`
  
  `//camera.position.x += 0.01;
   //sphereMesh.position.x = 50;
  //sphereMesh.position.z = -10;`
  
  `sphereMesh2.position.x = 1;
  sphereMesh2.position.z= 1;`
  
  `sphereMesh3.position.x = 1;
  sphereMesh3.position.z = -1;`
  
  `sphereMesh4.position.x = -1;
  sphereMesh4.position.z = 1;`
  
  `sphereMesh5.position.x = -1;
  sphereMesh5.position.z = -1;`
  
  `sphereMesh6.position.x = 1;
  sphereMesh6.position.y = 1;`
  
  `sphereMesh7.position.x = 1;
  sphereMesh7.position.y = -1;`
  
  `sphereMesh8.position.x = -1;
  sphereMesh8.position.y = 1;`
  
  `sphereMesh9.position.x = -1;
  sphereMesh9.position.y = -1;`
  
  `sphereMesh10.position.y = 1;
  sphereMesh10.position.z = 1;`
  
  `sphereMesh11.position.y = 1;
  sphereMesh11.position.z = -1;`
  
  `sphereMesh12.position.y = -1;
  sphereMesh12.position.z = 1;`
  
  `sphereMesh13.position.y = -1;
  sphereMesh13.position.z = -1;`
  
  `sphereMesh14.position.x = 2;
  sphereMesh14.position.z= 2;`
  
  `sphereMesh15.position.x = 2;
  sphereMesh15.position.z = -2;`
  
  `sphereMesh16.position.x = -2;
  sphereMesh16.position.z = 2;`
  
  `sphereMesh17.position.x = -2;
  sphereMesh17.position.z = -2;`
  
  `sphereMesh18.position.x = 2;
  sphereMesh18.position.y = 2;`
  
  `sphereMesh19.position.x = 2;
  sphereMesh19.position.y = -2;`
  
  `sphereMesh20.position.x = -2;
  sphereMesh20.position.y = 2;`
  
  `sphereMesh21.position.x = -2;
  sphereMesh21.position.y = -2;`
  
  `sphereMesh22.position.y = 2;
  sphereMesh22.position.z = 2;`
  
  `sphereMesh23.position.y = 2;
  sphereMesh23.position.z = -2;`
  
  `sphereMesh24.position.y = -2;
  sphereMesh24.position.z = 2;`
  
  `sphereMesh25.position.y = -2;
  sphereMesh25.position.z = -2;`
  
  `controls.update();
  renderer.render(scene, camera);
  requestAnimationFrame(draw);`
}

### Materials / Lighting / Camera ###

Materials

`//materials`

Material1
The white material has a 'more rule' feeling and represents layers of restriction.
![ddbbb6098fff160ab650d8ff9be0151](https://user-images.githubusercontent.com/57748663/205669290-75754546-0c44-4cd6-8bbb-027c89d70d76.png)

`const material1 = new THREE.MeshBasicMaterial( { color: 0xffffff } );`

Material2

The reflective material better reflects the blend with the environment.

![d43f5e7b568044e132efdceeb044092](https://user-images.githubusercontent.com/57748663/205668994-b1482f75-014c-4e6a-987d-bb3c6e990ebb.png)

`const cubeMaterial1 = new THREE.MeshLambertMaterial({`


 ` color: 0xffffff,`
 
 
  `envMap: reflectionCube,`
  
  
`});`

Lights and Camera

`//lights`

`const ambient = new THREE.AmbientLight(0xffffff);`

`scene.add(ambient);`

`const pointLight = new THREE.PointLight(0xffffff, 2);`

`scene.add(pointLight)   `

`const color = 0xFFFFFF;`

`const intensity = 1;`

`const spotlight = new THREE.DirectionalLight(color, intensity);`

`spotlight.position.set(0, 1, 5);`

`scene.add(spotlight); ;`

`var renderer = new THREE.WebGLRenderer();`

`camera.position.z = 3.4;`

### Sounds ###

A combination of four voices, high and low, urgent and slow, to set the scene for the future where crisis and opportunity coexist.

  `let maxi = maximilian();`
  
  `let audio = new maxi.maxiAudio();`
  
 ` let myOsc = new maxi.maxiOsc();`
 
 ` let drum1 = new maxi.maxiSample();`
 
 ` let drum4 = new maxi.maxiSample();`
 
  `let drum2 = new maxi.maxiSample();`
  
  `let drum3 = new maxi.maxiSample();`
  
  `let myClock=new maxi.maxiClock();`
  
  `audio.init();`
  
  `audio.loadSample('drum3.wav',drum3);`
  
  `audio.loadSample('drum4.wav',drum4);`
  
  `audio.loadSample('drum2.wav',drum2);`
  
  `audio.loadSample('drum1.wav',drum1);`
  
   ` var scratch=0;`
   
   ` var counter = 0;`
   
   ` var tempo = 120;`
    
   `var ticks = 1;`
   
   `myClock.setTempo(tempo);`
    
   `myClock.setTicksPerBeat(ticks);`

   
   `audio.play = function() {`
    
   `myClock.ticker();`
    
   `if (myClock.tick) {`
            
   ` scratch=0;`
           
   ` counter++;
    }`
       
   `//if (myClock.tick){`
   
   `//playHead++;`
    
   `//if （Math.random(）>0.5 && PlayHead % 8 ！=4）{`
    
   `//if （PlayHead % 8 ==0||playHead %8 == 3）{`
    
   ` if (myClock.tick && counter % 8 == 0){`
   
   `  drum1.trigger();`
    
   ` drum4.trigger();`
   ` }`
   `else if (myClock.tick && myClock.playHead %6 == 3){`
    
   `  drum3.trigger();`
      
   ` }`
   
   ` else if (myClock.tick && counter %7 == 2){`
    
   `drum4.trigger();`
    
   `drum2.trigger();`
    ` }`
    
   ` else if (myClock.tick && myClock.playHead %5== 0){`
    
   ` drum4.trigger();`
      
   `}`
   
   `var mix =drum1.playOnce(myOsc.sinewave(0.5)*5) + drum4.playOnce(0.5)+ drum2.playOnce(0.5)+drum3.playOnce(0.5)`
    
   `return mix * 3;`
   ` }`


