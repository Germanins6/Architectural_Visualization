# Architectural Visualization

## Contributor
Germán Insua - Game Development Degree at CITM-UPC
*[Webpage]* -  www.germaninsua.com 
*[Github]* -  https://github.com/Germanins6

## Project repository

*[Project]* - https://github.com/Germanins6/Architectural_Visualization
*[Releases]* - https://github.com/Germanins6/Architectural_Visualization/releases

## Project Description

This project, it's part of my final Bachelors Degree Thesis for Universitat Politécnica de Catalunya. 

The project contains a real-time application developed with **Unreal Engine 5.0.2** that shows an architectural visualization testing Lumen, Nanite and Virtual Shadow Mapping technology. Moreover, each asset seen in this project have been modeled and textured by me*.

*Only exception for vegetation using Quixel Megascans libraries.

## Application Controls

**Key 1:** Change between static camera viewpoints.
> Camera viewpoints can be changed with **Left/Right arrows**
 
**Key 2:** Enable player controller and navigate through the scene.
> **WASD + Mouse :** Move camera around scene in this mode

**Key 3**: Start camera sequences.

**Escape:** Show Settings menu.
>In settings menu the user can cap framerate(by default uncaped at -1), change between different screen resolutions, enable/disable Vsync, change scalability settings related with quality settings and exit the application.

**L:** Turn *on/off* artificial lighting.
**Q/E:** Camera Up/Down.

### Debug Modes
**F1:** Show GPU status.
**F2:** Show current framerate.

## ChangeLog

**-version 0.1**
- Basic Illumination and Postprocess implemented
- Blockout with some finished assets placed in scene
- Prototype functional( static cameras, free camera, sequences...)

**-version 0.2**

- Polished illumination using blue lighting mixed with artificial calid lighting
- Added static viewpoints to the camera array.
- Placed finished assets in some areas.
- Escape to exit application function added.

**-version 0.3**

- Implemented scalability settings to avoid performance issues and adapt to different devices.
- Quit button instead escape.
- Key bindings to display performance indicators( current framerate, gpu status...).

**-version 0.3**

- Improved and optimized UI for scalability settings.

**-version 0.4**

- Scene polish, more finished assets added.
- Implemented buttons to change between two resolutions *(1920x1080 and 1280x720)*.
- FPS cap option now functional in settings menu.
- Fixed screen resolution by default to 1280x720px
- Enabled RTX hardware raytracing + lumen technology.

**-version 0.5**

- Disabled RTX hardware raytracing options due to performance and testing issues.
- Troubleshooting non-working VSync option.
- Multiple resolutions added using ComboBox instead of resolution buttons as in 0.4.

**-version 0.6**

- VSync enabled by default.
- Setting up final static camera viewpoints + postprocessing.
- Changed game settings to enable by default windowed mode.

**-version 1.0**

- Placed final assets.
- Static cameras adjustments, reducing post-process values as bloom fx.
- Final camera sequences and adjustments.
- Asset auditation and general memory reducement.

 
## Lincese

MIT License

Copyright (c) 2022 Germán Insua

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
