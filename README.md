# PROJECT


#Canny edge detection is a technique to extract useful structural information from different vision objects and dramatically reduce the amount of data to be processed.
The general criteria for edge detection include:

Detection of edge with low error rate, which means that the detection should accurately catch as many edges shown in the image as possible
The edge point detected from the operator should accurately localize on the center of the edge.
A given edge in the image should only be marked once, and where possible, image noise should not create false edges.


The Process of Canny edge detection algorithm can be broken down to  different steps:

Apply Gaussian filter to smooth the image in order to remove the noise
Find the intensity gradients of the image
Apply non-maximum suppression to get rid of spurious response to edge detection
Apply double threshold to determine potential edges



TO RUN CODE
Requirement-
GPU
Device 0: Tesla K20Xm
GPU Cores: 14
Compute Capability: 3.5

command-
nvcc sas.cu -o sas
followed by
./sas

