# Flame_position
read several images, and figure out where the flame is, and make it to a graph.


In my research i took several pictures of flame with Ch-filtered camera. And the pictures are whiteblack.
In a folder there are hundreds of pictures.

for a picture, this program should do,

1. define the middle line of the flame.
2. read intensity of the pixels on line.
3. gauss fitting the result.(only region of 1/5 intensity of highest intensity.)
4. read the highest intensity pixel number after gauss fitted.
5. do it for enery pictures in the folder.
6. draw a graph or make a excel file for the result.

