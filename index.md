---
layout: default
---

# Chendi Li

## Academic life

<!---
<img class="profile-picture" src="sherlock.jpg">
-->

I am currently a graduate student at the State Key Laboratory of Computer Architecture, Institute of Computing Technology, Chinese Academy of Sciences (CARCH, ICT, CAS), supervised by Prof. **Yunquan Zhang**. For more details, please refer to my [resume](https://www.chendi.gq/Chendi_Li_Resume.pdf){:target="_blank"}.

Expected Graduation Date: 2022 Summer

I am looking for a 2022 Fall Ph.D. program.

---

### Research Interest

High-Performance Computing, Optimized BLAS Library, CPU and GPU acceleration.

<!---
I like hardcore programming and I really want to do some research on system area.

## News

2021.9.18 I found there are not many works on sparse matrix-matrix multiplication with fault-tolerant

2021.9.16 Recently, I'm doing some research on optimizing sparse matrix-matrix multiplication.

2021.7.13 It seems like SC is more likely to accept works about large-scale applications.

2021.6.14 I finished my paper. I have a plan about submitting a pull request to OpenBLAS, but I don't have enough time to test for all target architecture.
-->

---

### Publications

**Chendi Li**, Haipeng Jia, Hang Cao, et al. AutoTSMM: An Auto-tuning Framework for Building High-Performance Tall-and-Skinny Matrix-Matrix Multiplication on CPUs (IEEE ISPA 2021, New York)

Jianyu Yao, Boqian Shi, Chunyang Xiang, Haipeng Jia, **Chendi Li**, et al. IAAT: An Input-Aware Adaptive Tuning framework for Small GEMM(IEEE ICPADS 2021, under review)

**Chendi Li**, Guangting Zhang, Haipeng Jia. Fast Computation of Elementary Functions on ARM Platforms(in Chinese) (CCF HPC China 2020, Zhengzhou)

---

### Projects
* AutoTSMM(Author)

I designed AutoTSMM independently, which is used to build high-Performance tall-and-skinny matrix multiplication on all mainstream CPUs. And the performance is competitive with state-of-the-art TSMM implementation from Intel MKL and outperforms all conventional GEMM implementations on X86 and ARMv8 platforms. AutoTSMM was accepted by IEEE ISPA 2021.

* OpenBLAS(Con)

OpenBLAS is an open-source BLAS library. I'm responsible for optimizing pre-pack matrix-matrix multiplication and triangular solve with multiple right-hand-sides(TRSM) on ARMv8 and X86 platforms.

* Small-GEMM-JIT

This is a just-in-time small GEMM framework targeting on CPUs. I help to launch the project and did many investigations on how to use JIT tools. I participated in the brainstorm and meeting every week. However, I'm not the main coder of Small-GEMM-JIT.

* IAAT

IAAT is an input-aware adaptive tuning framework for small GEMM. I'm not the main coder of IAAT, yet I participated in the brainstorm and meeting every week. IAAT is being reviewed by IEEE ICPADS 2021.

* OpenVML

OpenVML is a vector math library. I'm responsible for optimizing the math functions on ARMv8 platform. The experimental results show that OpenVML achieve a performance improvement of 66% to 540% compared with C standard library function, and a performance improvement of 12% to 90% compared with Arm Performance Libraries(ARMPL). The paper ``Fast Computation of Elementary Functions on ARM Platform" was accepted by HPC China 2020.

* AutoFFT
  
AutoFFT is a template-based FFT codes auto-generation framework for ARM and X86 CPUs. I'm mainly responsible for optimizing small-scale FFT on ARMv8 architecture. Later, I also did some preliminary work on multi-threading and 2D-FFT. AutoFFT is the first research project I participated in, and I learned a lot from it. AutoFFT was accepted by SC19.

---

### Patents
* A run-time auto-tune method for non-regular-shaped matrix-matrix multiplication

This patent solves the poor performance caused by the excessively high ratio of the packing operation and the inability to reuse the data when the traditional general matrix-matrix multiplication calculates non-regular-shaped matrices.

## Non-academic life
I think I have that goal-driven personality, if I have a goal I will try my best to do it. My undergraduate life lacked guidance. I wanted to be a good programmer and I used to make a lot of effort on some coding projects to improve my coding skills instead of getting good grades. After graduation, I worked as a research assistant for gap year and passed the admissions test for graduate school with good grades(342/500, 22 points above the score line of the ICT.CAS), and then I participated in many research projects and had an oppotunity to do some independent research. The most important thing is that I have always been eager to learn and become better, so I believe that I have the ability to become a PhD candidate.
### Projects

### ACM compete programming

### Volunteer

