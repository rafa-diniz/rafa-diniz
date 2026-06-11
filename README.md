# Rafael

I'm a Computer Vision / Machine Learning master's student at UFMG researching Active Learning for sequential tasks. 

I also build visual-computing systems from scratch. My strongest interests are computer vision, machine learning, image/video processing, Linux systems and open-source tools. Most of the software I've written relates to one or more of these topics in some way.

I like building technical projects to understand how pipelines work internally, how data moves through a system, and where the performance bottlenecks appear in practice.

### Technical focus

* Computer Vision and Machine Learning
* Active Learning
* PyTorch for ML and tensor computation
* High-performance pipelines for image/video processing
* Vectorized NumPy and Cython optimization
* Linux-based development and open-source tooling
   
### Selected projects

Feel free to check out my [Projects Repo](https://github.com/RafaelAmauri/Projects), where I try to keep an updated record of what I'm working on.

Here are some of my personal projects:

#### • [Z-Tensor](https://github.com/RafaelAmauri/Z-Tensor) - Experimental video codec built from scratch

Z-Tensor is an experimental video codec implemented in Python and PyTorch. It features tensorized block-matching motion estimation, residual coding, scene-aware I-frame selection, chroma subsampling, custom binary serialization and Zstandard compression.

The goal is to explore how video codecs work internally and implement major features from scratch in high-performance GPU-accelerated tensor ops, without any libraries.

**Topics:** GPU programming, video encoding/decoding, compression, motion estimation, chroma subsampling, tensor operations

####  • [Image Studio](https://github.com/RafaelAmauri/Image-Studio) - High-performance image processing library
    
Image-Studio is a project where I implement classical image processing algorithms manually using only Numpy and Cython. No PIL, no OpenCV. 

It features colorspace conversion, color pallete mapping, dithering, quantization, Cython acceleration for the inherently sequential algorithms and high-performance pixel operations on large images.

**Topics:** Image processing, NumPy, Cython, optimization

#### • [Tree](https://github.com/RafaelAmauri/Tree) - Non-recursive C implementation of ```tree```
    
An implementation of the ```tree``` command in pure C. What makes it interesting is that it avoids any recursion, instead using a custom linked stack to list directory contents. This improves performance and reduces resource usage. The program also only utilizes the C standard library, which makes it extremely portable and lightweight.

**Topics:** C, data structures, filesystem traversal
