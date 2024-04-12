# Visual-Neuroscience Analysis

## Overview
This repository contains code for the odd-one-out detection experiment, which involves computing various distance metrics between pairs of images and analyzing firing rate data of neurons.

## Features
- **Relative Entropy Distance:** Measures the difference between the probability distributions of pixel values in two images.
- **L1 Distance:** Calculates the absolute differences between corresponding elements of two images.
- **Average Search Delay:** Uses firing rate data of neurons to compute the average time taken for a neuron to fire in response to a stimulus.
- The second part involves finding the ratio of the Arithmetic Mean (AM) and Geometric Mean (GM) of the spreads of the products of the distance metrics calculated above.


## Usage
- **Data Preparation:** Ensure that the input data for images and firing rate data of neurons are properly formatted and accessible to the code.
- **Running the Code:** Execute the main script or functions provided in the repository to compute the distance metrics and perform the analysis.
- **Interpreting Results:** Review the output generated by the code to analyze the relative differences between images and the behavior of neurons in response to stimuli.


## Comparison
The results of odd-one-out detection using L1 Distance and Relative Entropy Distance are as follows:
- The AM/GM measure of spread for the products:
    -  search delay × relative entropy = 1.042
    -  search delay × L1 distance1.128
- The estimated parameters are as follows:
    - The estimated value for the shape parameter is 3.222.
    - The estimated value for Rate parameter is 0.002.  
  
## Data Set
This file contains data on search times on certain image pairs.
- [data](https://ece.iisc.ac.in/~rajeshs/E0259/02_data_visual_neuroscience_searchtimes.csv)



## Getting Started

### Prerequisites

- [Python](https://www.python.org/) and [pip](https://pip.pypa.io/)
- [TensorFlow](https://www.tensorflow.org/) and [SciPy](https://scipy.org/)
- [NumPy](https://numpy.org/) 

### Installation

1. Clone the repository:

   git clone [Visual-Neuroscience](https://github.com/ugendar07/Visual-Neuroscience.git)


## Contact
For questions or inquiries, please contact [ugendar](mailto:ugendar07@gmail.com) .