# COS791-A2

## Introduction

This assignment compares the performance of two optimisation techniques, Simulated Annealing (SA) and Variable Neighbourhood Search (VNS), in solving the multilevel thresholding problem for image segmentation. Multilevel thresholding involves splitting a picture into various regions based on pixel intensity levels, which is an important task in many image processing applications. It prioritises thresholding at levels (k = 2, 3, 4, 5 ) for a batch of five images.

The Otsu technique and Kapur's entropy are two well-known objective functions used to assess thresholding quality. These methods will be used to determine the ideal thresholds for segmenting the photos. The goal is to see how well the SA and VNS algorithms work in determining suitable thresholds across different levels and images.

In addition, a table will be produced that summarises the threshold values and the relevant quality metrics obtained from both methods. Furthermore, for each image, at least one pair of Otsu and Kapur technique results will be visualised to better explain the segmentation outcomes.

<hr>

## Setup

This assignment was done using [Kaggle](kaggle.com). It is recommended to also make use of [Kaggle](kaggle.com) when using this notebook to avoid any issues with packages. The following steps should be followed to use this notebook:

**Upload notebook to Kaggle**
1. Register/Sign in at [Kaggle](kaggle.com).
2. Create a new notebook.
3. Download the notebook from the source(src) folder located [here](src).
4. Import the downloaded notebook in [Kaggle](kaggle.com) under `File -> Import Notebook`.

    **Import input data**
5. If closed, open the panel on the rigt using the arrow in the bottom right corner.
6. Under `Input`, select `Upload -> New Dataset`.
7. Download and upload the input files located [here](data/input).
8. Name the dataset `cos791-a2-input` and click `Create`. _(note that if you want to rename it to something else, you will have to change the path for the variable named `input_path`)_

