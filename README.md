# Making a globe from a spherical photo

Spherical photos taken with spherical cameras like the [Ricoh Theta S](https://theta360.com) can be considered as "maps" of a globe. These photos are stored in a rectangular JPEG file as a so-called equirectangular projection in which degrees latitude and longitude correspond linearly to position in the x axis and y axis respectively. To construct a physical globe using these files we may redraw the "map" using an interrupted sinusoidal projection, print out the map on paper, cut it out, and glue along the edges to form a globe. 

The *Mathematica* code below takes a spherical photo in equirectangular format as input and produces image files of an interrupted sinusoidal projection: one file of the complete map; and another file containing the first and last lobes of the first file drawn as adjacent lobes, as they are on the globe, which we call a patch. The patch can assist in closing the last seem of the constructed globe. The code should work with *Mathematica 10* or above.

If you do anything interesting with this or if you use it in your own classroom I would love to hear about it! However, there is no obligation to do so.

Best regards,

Robert Jacobson
<br>[rjacobson@rwu.edu](mailto:rjacobson@rwu.edu)
