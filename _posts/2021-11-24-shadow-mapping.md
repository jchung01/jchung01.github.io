---
title:  "OpenGL Shadow Mapping"
taxonomy: personal
date: 2021-11-24
last_modified_at: 2024-10-24
---
#### Languages/Tools Used
OpenGL, C++
#### Responsibilities
Implementation of shadow mapping in 3D scene
#### Description
A project using OpenGL to render rudimentary shadows for a custom 3D scene with a point light. Uses shadow mapping with 2-pass technique to calculate shadows. Artifacting/aliasing issues were mitigated by implementing depth bias, Poisson sampling, and percentage-closer filtering (PCF).

Repo: [github.com/jchung01/shadowmap-opengl/](https://github.com/jchung01/shadowmap-opengl) \
Explanation: [here](https://github.com/jchung01/shadowmap-opengl/blob/master/Shadow_Mapping_Writeup.pdf)

{% include video id="q-XJi58YZhY" provider="youtube" %}