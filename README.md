# CS867-Assignment-1-Ameera
Tasks
A set of images is given with this assignment to perform the following tasks. However, feel free to use
your own set of images.



2.1
Load the set of images and display them as Grayscale and rgb images. You are required to show these
images ”inline” rather than creating a new window for every other image. (2 points)



2.2
Implement the function rgbExclusion() in the helper script, in which the input image is decomposed
into the three channels: R, G and B and return the image excluding the specified channel. Display
the results in notebook. (3 points)



2.3
Take at-least 3 images from given set and plot histograms before and after applying histogram equalization. Show these image inline format i.e. grayscale image –> display histogram –> apply histogram
equalization–> display the equalized image and its histogram. (5 points)



2.4
You are required to implement the convolution operation from scratch. This function which takes an
image and a kernel and returns the convolution of them.
Compare the results of your implemented function with the ones available (built-in) in python
packages. You are required to convolve images for sharpening and blurring effects. (5 points)



2.5
Load a couple of images from the given set.
1. Apply box filter using convolution, and display the resultant image


2. Apply Gaussian filter to the image, with varying sigma values.


3. Add Gausian Noise and Salt and Pepper Noise to them.


4. Apply Gaussian Filter and Median Filters.


5: Display mesh plots for different i) Gaussian filters, ii) First Order Derivative of Gaussian, iii)
Laplacian of Gaussian; using different sigma values

You are encouraged to play with the different parameter values.The results should be displayed in
three columns i.e Original Image, Corrupted Image and the Filtered Image.
(20 points)



2.6
Load a few images from the given set.

1. Apply Sobel operator, computer gradient magnitude and display the results (original image, gradient images and gradient magnitude image).

2. Apply Laplacian of Gaussian, computer laplacian magnitude and display the results (original image, filtered images and laplacian magnitude image). Try different filter kernel coefficients.

3. Apply Canny Edge Detector and display the results.
