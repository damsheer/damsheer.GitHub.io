---
layout: default
---

### Research projects
* **Apache TVM (Contributor)**

Designed and developed the dynamic gradient algorithm in TVM. Experimental evaluation on a number of matrix-matrix multiplication and 2D convolution kernels demonstrates an order-of-magnitude improvement in auto-tuning time to achieve the same level of code performance. The paper was published in ICS 2024.

* **OpenBLAS (Contributor)**

Implemented and optimized the pre-pack matrix-matrix multiplication and triangular solve with multiple right-hand-sides(TRSM) on ARMv8 and X86 platforms. OpenBLAS is one of the most famous open-source BLAS libraries.

* **AutoTSMM (Author)**

Designed and developed AutoTSMM, which is used to build high-performance tall-and-skinny matrix multiplication on mainstream CPUs. AutoTSMM is competitive with Intel OneMKL and outperforms all conventional GEMM implementations on ARMv8 platform. This work was published in IEEE ISPA 2021 and it was published in TPDS'24 as a part of IrGEMM framework.

* **AutoFFT and OpenFFT (Contributor)**

Optimized small-scale FFT, and contributed to multi-threading and 2D-FFT. AutoFFT and OpenFFT is a template-based FFT codes auto-generation framework that contributes to many Chinese vendors' libraries. This work was published in SC'19, TPDS'20, HPCC'21, and ICS'23.

* **IAAT (Contributor)**

Launched the project and investigated JIT tools for small GEMM. IAAT is a template-driven just-in-time(JIT) small GEMM framework targeting CPUs. This work was accepted by IEEE ICPADS 2021.

* **OpenVML (Contributor)**
  
Enhancing the mathematical functions by manipulating IEEE 754 floating-point representations, OpenVML, a high-performance vector math library, demonstrated significant performance improvements over both the C standard library and ARMPL. This work was accepted and presented at HPC China 2020.
