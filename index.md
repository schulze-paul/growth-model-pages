# Growth Model Pressurized Surfaces

## Introduction

Here I present some initial tests from our simulation of shell growth in bacterial cells.

## Shell Pressurization

Due to osmotic pressure, the pressure inside a cell is larger than outside. Here we increase this pressure difference from 0 atm to 1 atm for a spherical shell of radius 250nm and observe the change in geometry.  

[![splitting triangles](https://img.youtube.com/vi/Df_-EIv69zU/0.jpg)](https://www.youtube.com/watch?v=Df_-EIv69zU)  
**Video 1: Shell pressurization.**


## Growth Mechanism

After pressurization, we can start to grow the shell. We randomly select a growth site on the surface of the shell and incorporate material into the shell with one of two growth mechanisms.

### 1. Splitting Triangles Growth Mechanism

Here we apply a growth mechanism where two adjacent triangles across an edge are split into four triangles.

<img alt="splitting triangles" src="https://github.com/schulze-paul/growth-model-pages/blob/gh-pages/SplitTriangles.png?raw=true" height=200>  

**Figure 1: Splitting two triangles into four.**


We can again observe the change in geometry as we incorporate more and more material into the shell.

[![splitting triangles](https://img.youtube.com/vi/PKs73A-TIWM/0.jpg)](https://www.youtube.com/watch?v=PKs73A-TIWM)  
**Video 2: Splitting triangles growth mechanism.** 

Although the spherical shape is roughly conserved, the surface is very crumpled. Overall the change in geometry throughout the growth process


### 2. Vertex Edges Growth Mechanism 

Another possible mechanism selects a vertex and then grows the rest lenths of the edges connected to that vertex.

<img alt="splitting triangles" src="https://github.com/schulze-paul/growth-model-pages/blob/gh-pages/grow_vertex_bonds.png?raw=true" width=200>  

**Figure 2: Selecting a vertex and the edges connected to it.**

Using this growth mechanism, we can observe the change in geometry shown in video 3.

[![vertex edges](https://img.youtube.com/vi/PKs73A-TIWM/0.jpg)](https://www.youtube.com/watch?v=PKs73A-TIWM)  

**Video 3: Vertex edges growth mechanism.** 

We can see that the surface of the shell stays much smoother and agrees much better with our intuition of growth.
