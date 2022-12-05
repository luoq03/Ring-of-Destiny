# **Ring-of-Destiny**
Coding 1 Final Project

## Project Overview ##

This is my final project, the theme of which is the Ring of Destiny(Switching views with the mouse). It describes a scenario in which, as the population continues to grow, the energy supply on earth becomes a bottleneck for human development. Attempts are made to amplify spiritual power and transform it into energy machines so that human civilisation can continue to develop at a high rate.

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
 
 <br> 
 
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

### Materials / Lighting / Camera ###

Materials

`//materials`

Material1

![ddbbb6098fff160ab650d8ff9be0151](https://user-images.githubusercontent.com/57748663/205669290-75754546-0c44-4cd6-8bbb-027c89d70d76.png)

`const material1 = new THREE.MeshBasicMaterial( { color: 0xffffff } );`

Material2

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
   
    `var tempo = 120;`
    
    `var ticks = 1;`
   
    `myClock.setTempo(tempo);
    
    `myClock.setTicksPerBeat(ticks);

   
    `audio.play = function() {`
    
    `myClock.ticker();`
    
    `f (myClock.tick) {`
            
           ` scratch=0;`
           
           ` counter++;`
       ` }`
       
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
   
    `var mix =drum1.playOnce(myOsc.sinewave(0.5)*5) + drum4.playOnce(0.5)+ drum2.playOnce(0.5)+drum3.playOnce(0.5)
    
    `return mix * 3;`
    ` }`


