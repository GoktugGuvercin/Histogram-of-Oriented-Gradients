# Histogram-of-Oriented-Gradients

Before deep learning started to overcome its problems like vanishing/exploding gradients, and in that way, it was situated as more usable and convenient way, histogram of oriented gradients approach had great popularity as an image processing method to extract necessary pieces of information from the images. Its methodology completely relies on sudden and abrupt variation between pixel values on the images. This type of color fluctuation actually has both magnitude and also particular direction. With the help of gradient computation on spatial image domain, we can access its both scalar and vectorial attributes. While where gradient vectors will point out is determined by the direction of color change on the image, their norm is about the intense of transition between the colors. In other words, oriented gradients of images are strong cues for their edges and corners, which form the shapes of objects insight the image. In the figure below, the gradients triggered by linear and radial color change are illustrated. The main reason why their vectorial norm (magnitude) is not so large is the fact that not abrupt but actually smooth intensity fluctuation occurs. 

<p align="center">
  <img src="https://github.com/GoktugGuvercin/Histogram-of-Oriented-Gradients/blob/main/images/image%20gradients.png" width="500" height="324" />
</p>

