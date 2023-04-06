# LCRM: Layer-wise Complexity Reduction Method for CNN Model Optimization on End Devices
This repository contains Python notebooks with code for optimizing AlexNet, VGG, and U-Net neural networks using the LCRM optimization method. We also include an ablation study to demonstrate the effectiveness of the optimization method and an appendix section with additional code examples.

## Getting Started


To get started, first clone this repository:
`git clone https://github.com/han-an/LCRM.git`


## Prerequisites
The code in this repository requires Python 3.6 or later and the following packages:
* Tensorflow-gpu >2.0
* NumPy
* Matplotlib
* TensorBoard (Profiler plugin)


Required packages are given at the beginning of each notebook.

## Usage
To use the optimization method, open the appropriate Python notebook for the network you want to optimize (e.g., LCRMVGG9.ipynb or LCRMUnet.ipynb). Run the notebook cells in order to train the model with the optimization method. We have included both the parent model and the LCRM-generated model for comparison.

## Ablation Study
We conducted an ablation study to evaluate the effectiveness of the optimization method for four different cases specified in the LCRM paper. The results are presented in the ablation_study.ipynb notebook. 

## Appendix
The appendix Python notebook contains code examples for using the optimization method with other set of convolutions exist in the literature: The substitution layers studied include standard convolution (Std Conv), transpose convolution (TrC), Groupwise convolution (GrC), depthwise convolution (DWC), pointwise convolution (PWC), and dilated convolution (DiC) and their combinations for checking the number of parameters.

## Reference
A portion of U-Net parent model code is referred from https://github.com/bnsreenu/python_for_microscopists. 
