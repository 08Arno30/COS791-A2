# COS791-A2

## Introduction

This assignment compares the performance of two optimisation techniques, Simulated Annealing (SA) and Variable Neighbourhood Search (VNS), in solving the multilevel thresholding problem for image segmentation. Multilevel thresholding involves splitting a picture into various regions based on pixel intensity levels, which is an important task in many image processing applications. It prioritises thresholding at levels (k = 2, 3, 4, 5 ) for a batch of five images.

The Otsu technique and Kapur's entropy are two well-known objective functions used to assess thresholding quality. These methods will be used to determine the ideal thresholds for segmenting the photos. The goal is to see how well the SA and VNS algorithms work in determining suitable thresholds across different levels and images.

In addition, a table will be produced that summarises the threshold values and the relevant quality metrics obtained from both methods. Furthermore, for each image, at least one pair of Otsu and Kapur technique results will be visualised to better explain the segmentation outcomes.
