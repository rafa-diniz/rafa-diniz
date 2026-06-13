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

**Topics:** video encoding/decoding, compression, GPU-accelerated tensor operations, motion estimation, chroma subsampling

####  • [Image Studio](https://github.com/RafaelAmauri/Image-Studio) - High-performance image processing library
    
Image-Studio is a from-scratch project where I implement classical image processing algorithms manually using only NumPy and Cython. No PIL, no OpenCV. 

It features colorspace conversion, color palette mapping, dithering, quantization, Cython acceleration for the inherently sequential algorithms and high-performance pixel operations on large images.

**Topics:** Image processing, NumPy, Cython, performance optimization

#### • [Tree](https://github.com/RafaelAmauri/Tree) - Non-recursive C implementation of ```tree```

Tree is a lightweight implementation of the ```tree``` command in pure C.

This project avoids recursive filesystem traversal by using a custom linked stack to list directory contents, which keeps the traversal state explicit and avoids growing the call stack on deeply nested directories. The implementation is small and lightweight, using C with POSIX filesystem APIs.

**Topics:** C, data structures, filesystem traversal

## What I'm interested in

I'm interested in Computer Vision, High-Performance Systems, Machine Learning, Visual Computing, Video ML and GPU/image processing roles.
