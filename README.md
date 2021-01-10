# Document-Scanner
Document scanner using OpenCV

Steps:\
After importing the image we convert the image into graysscale\
Using Gaussian blurr we remove the noise using 5/5 kernel\
Having the noise removed, we detect the edges using canny edge detection so that we can detect contours\
We get all the contours and select the contour with maximum area\
Drawing the detected contour on the original image we create a mask consisting of that contour only and later detect the corners from this mask\
We the apply perspective transform on the image and later use thresholding to get the scanned effect\
