ABSTRACT :
Image classification algorithms such as Convolutional Neural Network used for classifying huge
image datasets takes a lot of time to perform convolution operations, thus increasing the
computational demand of image processing. Compared to CPU, Graphics Processing Unit
(GPU) is a good way to accelerate the processing of the images. Parallelizing multiple CPU
cores is also another way to process the images faster. Increasing the system memory (RAM)
can also decrease the computational time of image processing. Comparing the architecture of
CPU and GPU, the former consists of a few cores optimized for sequential processing whereas
the later has thousands of relatively simple cores clocked at approx. 1Ghz. The aim of this
project is to compare the performance of parallelized CPUs and a GPU. Python’s Ray library is
being used to parallelize multicore CPUs. The benchmark image classification algorithm used
in this project is Convolutional Neural Network. The dataset used in this project is Plant
Disease Image Dataset. Keywords – Convolutional Neural Network, parallel computing, speedup
