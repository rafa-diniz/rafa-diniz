# Rafael

I'm a Computer Vision / Machine Learning master's student at UFMG researching Active Learning for sequential tasks. 

I also build visual-computing systems from scratch. My strongest interests are computer vision, machine learning, image/video processing, Linux systems and open-source tools.

I like building technical projects to understand how pipelines work internally, how data moves through a system, and where the performance bottlenecks appear in practice.

### Technical focus

* Computer Vision and Machine Learning
* Active Learning
* PyTorch for ML and tensor computation
* High-performance pipelines for image/video processing
* Vectorized NumPy and Cython optimization
* Linux-based development and open-source tooling
   
### Selected projects

#### • [Z-Tensor](https://github.com/RafaelAmauri/Z-Tensor) - Experimental video codec 

Z-Tensor is an experimental video codec implemented from scratch in Python and PyTorch. 

It features tensorized block-matching motion estimation, residual coding, scene-aware I-frame selection, chroma subsampling, custom binary serialization, Zstandard compression and CPU/GPU execution.

The goal is to explore how video codecs work internally and how classical codec components can be implemented manually in high-performance GPU-accelerated tensor ops, rather than using existing codec libraries.

**Topics:** GPU programming, video encoding/decoding, compression, motion estimation, chroma subsampling, tensor operations

####  • [Image Studio](https://github.com/RafaelAmauri/Image-Studio) - High-performance image processing library
    
Image-Studio is a from-scratch project where I implement classical image processing algorithms manually using only Numpy and Cython. No PIL, no OpenCV. 

It features colorspace conversion, color palette mapping, dithering, quantization, Cython acceleration for the inherently sequential algorithms and high-performance pixel operations on large images.

**Topics:** Image processing, NumPy, Cython, performance optimization

#### • [Tree](https://github.com/RafaelAmauri/Tree) - Non-recursive C implementation of ```tree```

Tree is a portable implementation of the ```tree``` command in pure C.

This project avoids any recursion, instead using a custom linked stack to list directory contents, which improves performance and reduces resource usage by avoiding recursion. The program also only utilizes the C standard library, which makes it extremely portable and lightweight.

**Topics:** C, data structures, filesystem traversal

## What I'm interested in

I'm interested in Computer Vision, High-Performance Systems, Machine Learning, Applied AI, Visual Computing, Video ML and GPU/image processing roles.
