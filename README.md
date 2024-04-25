## OOP Visual 2024

### What is this about?
For this assignment, I have created 4 audio-reactive visuals using Proccessing in java.\
Each visual reacts to the music in its own way.

### Chosen Music
I decided to go with a techno remix done by C100 of a song by Skepta - Glow in the dark
and BLK - I Need A Boiler Room

This song has a clear rhythm, beat and upbeat mood which I found easiest to make reactive elements for.

### How to run
Everything is called by the Main.java file.\
Once ran it will open up a processing window, which should be blank and you can
control.

**Controls:**\
**Play/Pause Music**: Space bar\
**Pick Visual**: Use keys 1 to 4 to display the 4 different visuals.


### My Visuals

**1) Rotating Stars**\
This visual creates a pattern of stars within more stars. The size of the smallest star changes gradually/
with respect to the loudness of the base, which creates a pulsating effect.

Furthermore the color of the stars as well as the speed of there rotations, depend on the overall amplitude of the song at any given moment.

**2) Infinite Terrain**\
For this visual, each side of the screen has a ever changing psuedo-random terrain that gives the illusion that its moving.

The terrain itself is created using a grid made of interlocking triangles where each point(x,y) has a \psuedo-random z-value (using perlin noise) giving the appearance of a 3D terrain.\ These grids are then rotated about the X and Y axis.

The color of the terrain changes with respect to the average amplitude, while the terrains pulsate on the beat.

**3) Rotating Spectrum Analysis**\
This visuals displays a Spectrum Analyzer (bar graph) of the song. The graph is displayed in 3D and the screen is split into a grid of 3D blocks.

The bars of the graph are made up of these blocks,which will also fall as though gravity is pulling on them.

To make it more visually appealing the whole graph is rotating upon the Y axis, and the color of the each block continually changes as though rotating around a color wheel.

**4) Reactive Sphere**\
A simple sphere is displayed, but each point of the sphere has its own radius from the centre. This radius is\
dependent on the amplitude of the song at a specific point, such that each point has its own unique radius and it doesnt just look like a sphere getting bigger and smaller.

The color of each point is determined by its position on the X axis + an offset. This offset is increased with relation\
to amplitude which creates the effect of a changing color wave.















