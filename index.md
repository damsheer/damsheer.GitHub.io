---
layout: default
---

## Chendi Li

## About Me

<img class="profile-picture" src="sherlock.jpg">

I am currently a graduate student at the State Key Laboratory of Computer Architecture, Institute of Computing Technology, Chinese Academy of Sciences (CARCH, ICT, CAS), supervised by Prof. Yunquan Zhang. For more details, please refer to my [resume](https://www.chendi.gq/Chendi_Li_Resume.pdf){:target="_blank"}.

Expected Graduation Date: 2022

I am looking for a Ph.D. program.

## Research Interest

High-Performance Computing, Optimized BLAS Library, Automatic Performance Tuning, Sparse Matrix Multiplication.

I am also eager to do some Hybrid-Research like HPC+AI. :)

<!---
## News

2021.9.18 I found there are not many works on sparse matrix-matrix multiplication with fault-tolerant

2021.9.16 Recently, I'm doing some research on optimizing sparse matrix-matrix multiplication.

2021.7.13 It seems like SC is more likely to accept works about large-scale applications.

2021.6.14 I finished my paper. I have a plan about submitting a pull request to OpenBLAS, but I don't have enough time to test for all target architecture.
-->

## Publications

Chendi Li, Haipeng Jia, Hang Cao, AutoTSMM: An Auto-tuning Framework for Building High-Performance Talland-Skinny Matrix-Matrix Multiplication on CPUs (IEEE ISPA 2021, New York)

Chendi Li, Guangting Zhang, Haipeng Jia, Fast Computation Elementary Functions on ARM Platforms(in Chinese) (Under review)

---

## Patents
#### A run-time auto-tune method for non-regular-shaped matrix-matrix multiplication
This patent solves the poor performance caused by the excessively high ratio of the packing operation and the inability to reuse the data when the traditional general matrix-matrix multiplication calculates non-regular-shaped matrices.

## Projects
* AutoTSMM
I designed an auto-tuning framework, AutoTSMM, for building high-Performance tall-and-skinny matrix multiplication on all mainstream CPUs. And the performance is competitive with state-of-the-art TSMM implementation from Intel MKL and outperforms all conventional GEMM implementations on X86 and ARMv8 platforms. AutoTSMM was accepted by IEEE ISPA 2021.

* OpenBLAS
OpenBLAS is an open-source BLAS library. I'm responsible for optimizing pre-pack matrix-matrix multiplication and triangular solve with multiple right-hand-sides(TRSM) on ARMv8 and X86 platforms.

* OpenVML
OpenVML is a vector math library. I'm responsible for optimizing the math functions on ARMv8 architecture. The experimental results show that on Kunpeng 920, the high-performance algorithm and optimization we proposed not only meet the calculation accuracy, but also achieve a performance improvement of 66\% to 540\% compared with C standard library function, and a performance improvement of 12\% to 90\% compared with Arm Performance Libraries(ARMPL). The paper of OpenVML is still under review.

* AutoFFT
I'm responsible for optimizing small-scale FFT on ARMv8 architecture. I write small-scale inline assembly. AutoFFT is the first project I participated in, and I learned a lot from it. AutoFFT published in SC19.

* OpenFFT
