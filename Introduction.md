# Outline
- Introduction to GPU
- Compute Unified Device Architecture:CUDA
- CUDA C on Google colab
- PyCUDA on Google colab
- CUDA Machine Learning
  - <a href="https://rapids.ai/about.html">RAPIDS suite</a>
  - <a href="https://github.com/rapidsai/notebooks">RAPIDS suite notebook</a>

# Introduction to GPU
- The Graphic Processing Unit (GPU) is a processor that was specialized for processing graphics.
- The GPU has recently evolved towards a more flexible architecture.
- Opportunity: We can implement *any algorithm*, not only graphics.
- Challenge: obtain efficiency and high performance.
## Difference between CPU and GPU
![](picture/gpu-programming.jpg)

## GPU computing 
key ideas:
- Massively parallel
- Hundreds of cores
- Thousands of threads
- Programable

<img src="picture/rtx.JPG">
<img src="picture/nvidia.JPG">
<img src="picture/amd.JPG">
<img src="picture/intel.JPG">

## Why accelerator technology today?
- Investment on GPU technology makes more sense today than in 2004. 
- CPU uni-processor speed is not doubling every 2 years anymore!
- Consider the point that GPU parallel performance is doubling every 18 months!

# Can we get 100x speedups?
- You can get hundred-fold speedup for some algorithms.
- Look for alternative ways to perform the computations that are more parallel.
- An accelerated program is going to be as fast as its serial part.

<img src="picture/amdahl.JPG">
Next>> <a href="CUDA.md">Compute Unified Device Architecture:CUDA</a>


