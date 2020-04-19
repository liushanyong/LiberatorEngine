# Liberator3D Engine

## Description
A 3D game engine for creating high quality 3D game. The name comes from a song. Anyway i'll rename it if i devise a better one.
I spend 1 year to write the game engine at the last year of my college. And i put it into my graduation thesis, it got full mark, 
23333.

<br>
<br>
<br>

# Targets
- 1 vs 10000
- easy to drive

<br>
<br>
<br>

## Engine development principle
不开源的引擎不一定牛逼，但是牛逼的引擎一定不开源。<br>

<br>
<br>
<br>

# Features
<br>

## General
- 3D
- high performance
- fiber ECS
- plugin based
- real-time world editing
- fast prototyping
- almost everything is hot-loadable
- fully multi-threading schedule

## gfx engine
- general, cross-platform, stateless, multi-threading, immediate rendering mode gfx interface
- cross API (D3D11, D3D12, Vulkan,,) 

## Rendering engine
- programmable material system
- render pipeline blueprint system
- millions of objects on screen
- multi-threading rendering
   
## Graphics
- decals
- particle effect
- temporal AA
- cascade shadow
- subsurface scattering
- SSAO
- god ray
- real time PBR volumetric light shaft
- modern "real time" PBR path tracing
- large scale open world clipmap VXGI, real time 2 bounce 

## Voxel engine
- GPU voxelize
- seamless 
- voxel streaming
- support endless world

## Global illumination engine
- PBR BXDF
- GTAO, GTSO, VXAO
- screen space reflection
- IBL
- screen space raytracing
- caustic effect
- soft indirect shadow
- real time irradiance volume
- handemade RTX
- "realtime" pathtracing preview scene
- radiance transfer, real time multi-bounce
- VXGI
- PTGI
- VXPTGI
- large scale, ourdoor scene, ground true, fully dynamic (object and light), fully real time global illumination

## Terrain engine
- seamless LOD
- quadtree LOD
- clipmap LOD
- stream base load balancing
- quadtree clipmap PVRT
- up to hundreds of square kilometers(16km x 16km) fully visible landscape
- down to cm details 
   
## Physics
- Bullet
- rigidbody 
- heightfield

## GUI
- in-house GUI, very fast

## Animation
- skeleton animation
- up to 200 independent animators in a world 
- real-time animation blueprint

## Script
- lua
- unity3d mono-like script component 
- hot-loadable script

## Editor 
- multi-world editing
- material edit
- preview model
- preview statemachine blueprint
- terrain editor 

***
<br>
<br>
<br>
<br>
 
# Who's using it ?
- https://github.com/kampxtr/SimpleARPG

![](https://github.com/kampxtr/SimpleARPG/blob/master/screenshot/2018-2-28.png)
<br>
<br>
<br>
<br>
<br>
***

<br>
<br>
<br>
<br>

# Where's the code ?
- https://github.com/kampxtr/LiberatorEngine/tree/master/src
<br>
<br>
<br>
<br>
<br>

***
<br>
<br>
<br>
<br>
<br>

# More showcase
- https://github.com/kampxtr/EngineShow
<br>
<br>
<br>
<br>
<br>

***
<br>
<br>
<br>
<br>
<br>

# Samples

Completed at 2017.5.18

### PTGI scene sample (hold on !!! 2M picture here !!!)
## ↓
![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-3-1.png)
<br>
<br>
<br>
<br>
<br>
<br>

### support large scale ourdoor scene, fully dynamic, fully real time GI  (hold on !!! 2M picture here !!!)
## ↓

![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-5-20.png)
<br>
<br>
<br>
<br>
<br>
<br>

### up to hundreds of kilometers(16km x 16km) fully visible landscape  (hold on !!! 2M picture here !!!)
## ↓
![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-12-25.png)
<br>
<br>
<br>
<br>
<br>
<br>


### realtime PTGI on 100K triangle scene , still not a big deal   (hold on !!! 5M GIF here !!!)
## ↓

| real time 5MB gif ↓ | ground true ↓ |
| --- | --- |
|![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-23.gif) |  ![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-23.png)|

<br>
<br>
<br>
<br>
<br>

![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-22.png)
<br>
<br>
<br>
<br>
<br>
<br>

### real time PBR path tracing is naive, still not a big deal   (hold on !!! 5M GIF here !!!)
## ↓

![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-24.png)
<br>
<br>
<br>
<br>
<br>
<br>

| real time 5MB gif ↓ | ground true ↓ |
| --- | --- |
|![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-14.gif) |  ![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-14.png)|

<br>
<br>
<br>
<br>
<br>

![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-15.1.png)
<br>
<br>
<br>
<br>
<br>
<br>


### PTGI caustics  (hold on !!! 2M picture here !!!)
## ↓

|  |  |
| --- | --- |
|![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-28.1.png) |  ![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2019-2-28.png)|

<br>
<br>
<br>
<br>
<br>
<br>

### real time PBR volumetric light shaft   (hold on !!! 2M picture here !!!)
## ↓

![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-9-18.png)
<br>
<br>
<br>
<br>
<br>
<br>

## ↓
![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-8-11.png)
<br>
<br>
<br>
<br>
<br>
<br>


## edit large scale terrain is not a big deal (hold on !!! 2M picture here !!!)
## ↓
![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-10-12.png)
<br>
<br>
<br>
<br>
<br>
<br>

## performance is not a big deal (hold on !!! 2M picture here !!!)
## ↓
![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-2-22.png)
<br>
<br>
<br>
<br>
<br>
<br>


## demo is cheap, not a big deal though. (hold on !!! 2M picture here !!!)
## ↓
![](https://github.com/kampxtr/LiberatorEngine/blob/master/screenshots/2018-1-14.1.png)
<br>
<br>
<br>
<br>
<br>
<br>





