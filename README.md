# Sketching-Painting-an-Image

Problem Statement:

While editing photos, we usually apply filters to edit the photos directly and 
get a sketch representation or a pastel paint representation of the image. 
In this project we design a program which discovers the working behind 
such existing filters and shows the intermediate steps as well before giving 
the sketch form and pastel paint form.

Description:

Since our project involves image processing we have used OpenCV and 
Adaptive Thresholding for its development. Rather than making it as a web 
application we are making an open source software which runs without the 
requirement of internet and the source code can be modified by user based 
on his requirements. 
So we first take the image as an input, and break it into smaller parts using 
adaptive thresholding and assign a number to each part.
Then downscale the image and apply a bilateral filter to get a cartoon like 
effect.
We convert the image to grayscale and then we apply the media blur filter 
in order to get a blurred effect on the photo. This will help us in making the 
sketch.
Next step is to identify the edges in the image, which is basically used to get 
the sketch form of the image. 
Then add this to the previously modified images to get a sketch effect. We 
use Adaptive Threshold for to do this step. Adaptive thresholding breaks 
the image into small regions and assigns a number to each region.
The painted image is an advanced form of the sketch image obtained.
We compile the final images obtained from the previous steps to get the 
final output as a painted image.
