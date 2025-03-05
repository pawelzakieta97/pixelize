# Cursed LEGO instructions 
The aim of this project was to generate an instruction for a LEGO set.
The set is a mosaic consisting of a single 32x32 base plate and a bunch of 1x1 plates in a 7 different colors.

## Pixelizing an image
The first objective is to downscale the image to 32x32 pixels and set their value to the most suitable available color. 
The best approach turned out to be an Euclidean distance in RGB space with additional manual scaling.
![image](https://github.com/user-attachments/assets/9643f7f0-e2cb-4dc4-9fcd-040eebb4a0ff)


## Generating instructions pages
To add an element of surprise, the instructions are generated in such a way that the recipient does not know what exactly they are going to be building.
The instructions is divided into a configurable number of pages that hide the colors of blocks that are already in place.
![Uploading image.png…]()
