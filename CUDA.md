# CUDA introduction 
(images from <a href="https://docs.nvidia.com/cuda/cuda-c-programming-guide/index.html">CUDA programming guide</a>)
## CUDA architecture
  - A GPU is built around an array of Streaming Multiprocessors (SMs).
  - A multithreaded program is partitioned into blocks of threads that execute independently from each other.
  - GPU with more multiprocessors will automatically execute the program in less time than a CPU with fewer multiprocessors.
  
  <img src="picture/automatic-scalability.PNG">
