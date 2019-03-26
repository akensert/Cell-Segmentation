# Cell-segmentation 

A python script that automatically segments individual \[biological\] cells from a multi-cell image. <br/>

# Usage and limitation

This algorithm was used to segment cell images in the Human Protein Atlas (HPA) Image Classification competition, on full resolution images. The example images ('Test-images') are lower-resolution images, but illustrate how the images were cropped before being fed to a neural network. The limitation of this implementation is that it probably won't work for any type of biological cell images --- beacuse it was specifically implemented for the HPA images.
<br/>
<br/>
*Example of cropped images*:
<br/>
![img](example_image.png)


