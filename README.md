# ProceduralPlanetRendering

[![ProceduralPlanet](http://img.youtube.com/vi/0bQz5ugtfLY/0.jpg)](http://www.youtube.com/watch?v=0bQz5ugtfLY)

## About

Simple Realtime procedural planet rendering application. 
Implemented using C/C++, OpenGL, and NVIDIA Cg.

## Features

- Seamless Patches for GPU-Based Terrain Rendering* 

- Deferred Shading

- Precomputed Atmospheric Scattering

- In-flight terrain height map generation using GPU procedural noises

- Virtual Texturing

* Slightly modified for spherical surface tessellation.

## Running application

1. Download prebuilt application from [**here**](https://github.com/masatakesato/ProceduralPlanetRendering/releases/download/v0.0.1-alpha/ProceduralPlanetRendering.zip).

2. Extract zip file and execute ProceduralPlanetRendering.exe inside bin folder.

## Building application

### Prerequisities

Following system configurations are required to build application.

- Windows 10(or later) with Visual Studio Community 2017 installed

- NVIDIA Cg Toolkit 3.1

- FreeGLUT

- GLEW

### Setup

- Clone this repository.

- Create a new directory named "**external**" inside /ProceduralPlanetRendering directory.

- Download **[OreOreLib](https://github.com/masatakesato/OreOreLib/releases/download/2022q1/oreore.zip)** and put extracted directory into "**external**".

- Download **[GraphicsLib](https://github.com/masatakesato/GraphicsLib/releases/download/2022q1/graphics.zip)** and put extracted directory into "**external**".

- Open VisualStudio project
  
  - /ProceduralPlanetRendering/dev/ProceduralPlanetRendering/ProceduralPlanetRendering.vcxproj

- Modify "**Additional Include Directory**" and "**Additional Library Directories**" settings related to following libraries
  
  - NVIDIA Cg Toolkit
  
  - FreeGLUT
  
  - GLEW

- Build project.
