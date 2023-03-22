# An Even Easier Introduction to CUDA
Source: https://developer.nvidia.com/blog/even-easier-introduction-cuda/

## Disclaimer

This is just a small private playground for CUDA Beginners based on the Nvidia CUDA Source Course. Use the resources with 
care!

Note: that the resources in this repository are based on my private learning a can contain frauds and errors. 

## Setup

I use JetBrains CLion as IDE and the 'latest' CUDA installation. If you don't know how to set up the IDE and install 
and bind the path variables, then you face the consequence, that must learn C++ and OS principles first!
Don't start with CUDA without a solid foundation, or you will end up frustrated and break with a fruitfully career
opportunity.

- [Learn CPP first](https://www.learncpp.com)
- [Learn cMake first](https://cmake.org/cmake/help/latest/guide/tutorial/index.html)


# Course is Branch based!

- 00_VectorAddition: [An Even Easier Introduction to CUDA _ NVIDIA Technical Blog.pdf](An%20Even%20Easier%20Introduction%20to%20CUDA%20_%20NVIDIA%20Technical%20Blog.pdf)



# Profile it!

NVPROFE is located in std. installation setting in:

    C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1\bin>
    
    nvprofe.exe <path.to.yourproject>\cmake-build-debug\CUDA-Easier-Introduction.exe



## Problems with *.dll's 

I had an issue that some required dll's for pvprofe.exe was not visible in the Windows Path.

In that case add:

    C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v12.1\extras\CUPTI\lib64
