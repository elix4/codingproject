#**Functions**
- **Function 1: draw_polygon**\
This function is used to create polygons (triangles, hexagons, and octagon).
- **Function 2: draw_circle**\
This function is used to create circles.
- **Function 3: repeat_hexagon**\
This function is used to draw a row of repeated hexagons.
- **Function 4: repeat_octagon**\
This function is used to draw a row of repeated octagons.
- **Function 5: repeat_triangle**\
This function is used to draw a row of repeated triangles.
- **Function 6: repeat_triangle_spaced**\
This function is used to draw a row of repeated triangles that are spaced out.

# **Working Method**
The idea behind the drawings was to create a form of shapes that would then transition with each new image and increase in color and saturation. I wanted there to be subtle changes in the expansion of each row and growth in size of the center spiral. I first made every image in black and white to figure out the placement and coordinates for each shape in the drawing. 

# **Difficulties**

Probably the most difficult thing I encountered while working on this project was how long each drawing took to render in Colab. Each drawing took about 15-20 minutes each. The last bit of the drawing is a spiral of 20 circles, but ninety percent of the time, Colab would fail to completely render all 20 iterations, leaving me with a 3/4th done spiral. I would then have to rerun the cell and hope that the spiral gets finished completely.

Another problem that occurred was the lines showing up at the bottom of each row. I tried to search up solutions on Google/Stack Overflow, but I was unable to figure out the source behind this problem. I tried multiple methods of trying to zero in on the source, but this combined with how long each drawing took to render really ate up a lot of my time.

# **Resources**

I found some references online that listed all the Turtle commands, which I found very helpful. Some other resources that I found helped me in figuring out how to use nested functions and the examples they gave aided me in knowing how to format and call the functions. I also looked on Stack Overflow to help try resolve any other problems that I came across.


# **Future**

In the future, I would improve this work by doing more iterations between the color shifts to make it a bit more seamless. After coming up with the idea that I had, I envisioned this taking form as a GIF as well, so with more color iterations the GIF would be visually smoother. I would also like to experiment with different shape compositions and see where that could take me.
