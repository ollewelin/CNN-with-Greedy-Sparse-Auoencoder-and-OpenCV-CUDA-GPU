# CNN OpenCV CUDA GPU support with Greedy Sparse Autoencoder 
# Convolution-Deep-Neural-Network-with-Sparse-Autoencoder-and-Reinforcement-Learning
Under development Autoencoder tested now, Sparse Greedy Denoiseing tested. Just a place to store my code under develop the code until finish.
When finish it will be placed here.

Dependency:
NVIDIA CUDA to be able to run on GPU
OpenCV (Will use computation on GPU, to be continued)

Installation tools eample on Linux.

https://developer.nvidia.com/cuda-toolkit (For NVIDIA GPU board)

Setting up OpenCV with Cmake GUI

https://cmake.org/

https://github.com/opencv/opencv

do ../yourdownloadOpenCVfolder

$mkdir build

start CMake GUI program

click and set path with 

Brows source ../yourdownloadOpenCVfolder/opencv-master

Brows build ../yourdownloadOpenCVfolder/build

set checkbox

WITH_CUDA=1

WITH_QT=1

and other settings you want..

click Configre 2 times so the window turn white

click Generate

go to terminal ../yourdownloadOpenCVfolder/build

$sudo make

wait loooong time (several houers) for compilation

Then important to load 
/usr/local 
with the new stuff do in ../yourdownloadOpenCVfolder/build

$sudo make install

$sudo ldconfig

To do the application do

Compile:

$make

Run:

$./OW_CNN_R


Input image is eather from input.JPG or CIFAR-10 depending on Y/N start question. 
CIFAR-10 data set as image input testing. 
To do that download "CIFAR-10 binary version (suitable for C programs)" dataset from
https://www.cs.toronto.edu/~kriz/cifar.html
Extract and put data_batch_1.bin in same place as the program. 
