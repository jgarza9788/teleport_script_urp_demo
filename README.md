 Teleport_Script_URP
-------------------------------------
[Asset Store Link](http://u3d.as/2N8m)  


© 2022 Justin Garza

PLEASE LEAVE A REVIEW OR RATE THE PACKAGE IF YOU FIND IT USEFUL!
Enjoy! :)


## Table of Contents

<!--TOC-->
* [Teleport_Script_URP](#teleport_script_urp)
	* [Table of Contents](#table-of-contents)
	* [Contact](#contact)
	* [Terms of Use](#terms-of-use)
	* [Description Features](#description-features)
	* [Set Up](#set-up)
	* [Shaders](#shaders)
		* [Properties/parameters](#properties/parameters)
		* [teleport_v0:](#teleport_v0:)
		* [teleport_v1:](#teleport_v1:)
		* [teleport_[...]:](#teleport_[...]:)
		* [C scripts](#c-scripts)
		* [DemoScript01.cs](#demoscript01.cs)
		* [TurnNinety.cs](#turnninety.cs)

<!--TOC-->

## Contact

My Contact info is on my github profile  
[https://github.com/jgarza9788](https://github.com/jgarza9788)
 
## Terms of Use

Required:
please follow [Unity's EULA](https://unity3d.com/legal/as_terms) 

Suggestion/Optional:
please put my name in the credits, or in the special thanks section. :)  

## Description Features

* Change any and all parameters
    * X, Y, or Z Axis
    * Direction
    * Color or Gradients
    * Different Noises (any kind you want/need)
    * NoiseSpeed
    * works on animated models
* Awesome Demo
* and Fully Commented Code & ShaderGraph
* Video Guiding walk-through ShaderGraph


## Set Up
None:  
your set up should be the basic URP set up.  
so make sure you have the standard unity URP setup.

Optional:  
add the volume and bloom to make sure those HDR colors really pop!

## Shaders

### Properties/parameters
the shaders all have some basic properties.
1. Anim: this slides from 0 to 1 to animate the teleport
2. AnimMinMaxPosition: this is used to adjust the min and max of anim
3. Fade: how fast the colors fade
4. Rotation: the tilt or rotation of the effect
5. RotAxis: the axis you want to rotate on.
6. useWorldPosition: whether or not to use worldposition or objectposition
7. worldoffset: if the worldposition needs to be shifted or adjusted.
8. useGradient: whether or not to use gradient or color
9. Gradient: the main gradient used to create the effect.
10. Gradient(1): a mask gradient
11. Gradient(2): a mask gradient
12. ColorL the color to use if we are not using the gradient
13. direction: the direction the teleport is going
14. NoiseSpeed: use for animating the noise.
15. Metallic: basic metallic property
16. Smoothness: basic smoothness property


### teleport_v0:
this is a basic shader just for testing out the code.
### teleport_v1:
this is a shader with main-texture and emission.
### teleport_[...]:
the rest are used in various parts of the demo.

## C# scripts

### DemoScript01.cs
this manages each "side" of the demo.  
syncing up the values of the ui and shaders.  
and turning objects on/off when needed.  

### TurnNinety.cs
turns the camera 90degrees.



