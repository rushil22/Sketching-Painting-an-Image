# Animating-An-Image

Problem Statement:

While editing photos, we usually apply filters to get the cartoon form or animated form of our photos directly. 
For our project we discover the science behind such filters and try to design our own filter which animates a given photo.

Algorithm:

To animate an image we need to break it into smaller parts.
We first downscale the image and apply a bilateral filter to get a cartoon effect.
We upscale the image again.
We convert the image to grayscale and then we apply the media blur filter in order to get a blurred effect on the photo.
Next step is to identify the edges in the image and then add this to the previously modified images to get a sketch effect. We use  Adaptive Threshold for to do this step.
We compile the final images obtained from the previous steps to get the final result.


