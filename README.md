# Document-Scanner
Document scanner using OpenCV

After importing the image we convert the image into graysscale
Using Gaussian blurr we remove the noise using 5/5 kernel
After removing the noise we detect the edges using canny edge detection so that we can detect contours
We get all the contours and select the contour with maximum area
Drawing the contour on the original image we use mask to get the contour and later detect the corners from this mask
We the apply perspective transfrom on the image and later use thresholding to get the scanned effect
