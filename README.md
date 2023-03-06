# B-WtoColor
As color is very important compound of visual represent, the black and white photos make it impossible to fully imagine the actual represented scene.



Firstly,We are going to convert the b/w images from RGB color space to LAB color space.
In the LAB color space, L----> represents b/w part of the image, and AB----> represents the color part of the image.
Using this "L" part of the image we are going to predict the "AB" part of the image.

You will need to download the pre-trained data from this location and place in the model folder:
    https://www.dropbox.com/s/dx0qvhhp5hbcx7z/colorization_release_v2.caffemodel?dl=1
