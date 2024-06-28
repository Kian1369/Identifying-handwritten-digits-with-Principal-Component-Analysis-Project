# Identifying-handwritten-digits-with-Principal-Component-Analysis-Project

## Project Overview

The goal of this project is to identify which handwritten digits are most differentiated using Principal Component Analysis (PCA). This project simulates a scenario where an image recognition service is implemented for a postal service to automatically read handwritten digits, improving efficiency and accuracy over human recognition.

<img src="images/Digit%200.png" alt="Digit 0" width="400" />

## Dataset

The dataset consists of handwritten digits collected by E. Alpaydin and Fevzi. Alimoglu from the Department of Computer Engineering, Bogazici University, Turkey. The data includes 250 samples from 44 writers. The samples written by 30 writers are used for training, cross-validation, and writer-dependent testing, while the digits written by the other 14 are used for writer-independent testing. The dataset is available in the UNIPEN format.

Source: [Pen-Based Recognition of Handwritten Digits](https://archive.ics.uci.edu/ml/datasets/Pen-Based+Recognition+of+Handwritten+Digits)

## Results and conclusion

The PCA transformation reduced the data dimensionality from  to 2 principal components and then 3 principal components, explaining approximately 21.6% and 30% respectively of the total variance in the dataset. This project demonstrates the use of PCA to analyze and differentiate handwritten digits, which can significantly improve the performance of an image recognition system for a postal service.

## References 

1- E. Alpaydin, Fevzi. Alimoglu, Department of Computer Engineering, Bogazici University, Istanbul, Turkey.

2- Dataset Source: Pen-Based Recognition of Handwritten Digits
