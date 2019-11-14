# EIP_Project

# Result
print(score)  = [0.02607954332709196, 0.9925]

#Definition

1. Convolution 
Convolution is the process of detecting various patterns from
an image using lters/kernals. Element wise multiplication of pixel in a kernel
when super imposed on an input image and then summing it up to get a single
value out. This is to extract the dominating feature .

2.Filters/Kernals 
Filters/Kernals also known as feature extractor is gener-
ally a 3 x 3 matrix that convolve over an input image to extract certain feature
from the input image.

3.Epochs
The number of times a network look through the entire image data
set. If a network looks the entire image data set once, its called 1 Epochs.

4.1X1 Convolution 
The 1x1 convolution combines the channel which are
contextually linked together.Its used to reduce the depth of a layer with out
loosing much information.

5.3x3 Convolution 
A 3x3 matrix is used to convolve over the image ie 9
pixel get multiplied with corresponding pixel in input image and gets added up
to give a single value. Generally, After this convolution 2 pixel are reduced in
X and Y each.

6.Feature Maps 
Feature map is the result of convolution after applying
activation function.

7.Activation Function
Activation function are used to make the weights
of a kernel non linear.

8.Receptive Field
The number of pixel in an input image that the filter
can look at, ie a 3x3 filter can look at 9 pixel on an input image. This is local
receptive feld ie size of kernal.
