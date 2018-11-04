# webcam_circles
Circle detection from online webcam images
Basically this programa uses the function HoughCircles from OpenCV.
HoughCircles is a function that detects and returns an output vector of circles, and each vector has 3-element floating-point vector (x, y, radius). The method for detect circles is CV_HOUGH_GRADIENT, but in general the Hough Transform works with the circle equation looking for points that transformed into a circular cone you have all the points lie on a circle, which intersect at a single point that are the circle parameters (a, b, r).

Also in HoughCircles function there are important parameters like the minimum distance between the centers of the detected circles, the minimum and the maximum circle radius.

More information in:
https://docs.opencv.org/2.4/modules/imgproc/doc/feature_detection.html?highlight=houghcircles#houghcircles
http://www.bmva.org/bmvc/1989/avc-89-029.pdf
