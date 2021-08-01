# Artificial-Intelligence-Major
Face Detection model on Webcam using Python


Approach/Algorithms used:

This project uses LBPH (Local Binary Patterns Histograms) Algorithm to detect faces. It labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.
LBPH uses 4 parameters :
(i) Radius: the radius is used to build the circular local binary pattern and represents the radius around the
central pixel.
(ii) Neighbors : the number of sample points to build the circular local binary pattern.
(iii) Grid X : the number of cells in the horizontal direction.
(iv) Grid Y : the number of cells in the vertical direction.
The model built is trained with the faces with tag given to them, and later on, the machine is given a test data and machine decides the correct label for it.
