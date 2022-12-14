### A Transpose-free Three-dimensional FFT Algorithm

**[IEEE HPCC 2021]** Tun Chen, Haipeng Jia,  Zhihao Li, **Chendi Li**, Yunquan Zhang. **A Transpose-free Three-dimensional FFT Algorithm on ARM CPUs**([link](https://www.researchgate.net/publication/360966539_A_Transpose-free_Three-dimensional_FFT_Algorithm_on_ARM_CPUs){:target="_blank"})


#### Abstract: 
According to the traditional multi-dimensional FFT, memory layouts of high-dimensional data are discontinuous. Transposition is introduced to keep high-dimensional data continuous in memory. However, transposition increases memory access and is a hot spot for multi-dimensional FFT. This paper proposes an optimization framework to eliminate explicit transpositions and optimize the three-dimensional (3D) FFT. This framework includes three research points. 1) combines the width-first and breadth-first search to optimize the butterfly network of one-dimensional (1D) FFT; 2) adopts a column-order algorithm to eliminate data transposition; 3) adopts a blocking algorithm of cache-aware to better use the hardware resources of ARM architecture. Based on this optimized framework, a multi-dimensional FFT library named MDFFT is implemented. The experiments demonstrate that MDFFT generally performs better than FFTW and ARMPL on ARM CPUs.
