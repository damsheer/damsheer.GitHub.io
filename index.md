---
layout: default
---

<!---
# Chendi Li

-->
## Academic life

<img class="profile-picture" src="me.jpg">
<!---
-->

I am currently a PhD student at the University of Utah, and supervised by Prof. [**P. (Saday) Sadayappan**](https://www.cs.utah.edu/~saday/){:target="_blank"}. I got my master degree from the State Key Laboratory of Computer Architecture, Institute of Computing Technology, Chinese Academy of Sciences (CARCH, ICT, CAS), and supervised by Prof. [**Yunquan Zhang**](https://dblp.org/pid/17/6660.html){:target="_blank"}. Please refer to my short [resume](https://www.chendi.gq/Chendi_Li_Resume.pdf){:target="_blank"}. If you have any questions, feel free to contact me by [email](mailto:lichendi.cs@gmail.com).

### Research Interests

* High-Performance Computing
<br/>
* Matrix/Tensor Optimization
<br/>
* High-Performance Machine learning


<!---
I like hardcore programming and I really want to do some research on the system area.

## News

2021.9.18 I found there are not many works on sparse matrix-matrix multiplication with fault-tolerant

2021.9.16 Recently, I'm doing some research on optimizing sparse matrix-matrix multiplication.

2021.7.13 It seems like SC is more likely to accept works about large-scale applications.

2021.6.14 I finished my paper. I have a plan about submitting a pull request to OpenBLAS, but I don't have enough time to test for all target architecture.
-->

### Publications

**[IEEE ISPA 2021]** **Chendi Li**, Haipeng Jia, Hang Cao, et al. **AutoTSMM: An Auto-tuning Framework for Building High-Performance Tall-and-Skinny Matrix-Matrix Multiplication on CPUs**([presentation](https://www.youtube.com/watch?v=NjIla6zXRHM){:target="_blank"})([link](http://www.cloud-conf.net/ispa2021/proc/pdfs/ISPA-BDCloud-SocialCom-SustainCom2021-3mkuIWCJVSdKJpBYM7KEKW/264600a159/264600a159.pdf){:target="_blank"},[arxiv](https://arxiv.org/abs/2208.08088){:target="_blank"})

**[IEEE ICPADS 2021]** Jianyu Yao, Boqian Shi, Chunyang Xiang, Haipeng Jia, **Chendi Li**, et al. **IAAT: An Input-Aware Adaptive Tuning framework for Small GEMM**([link](https://ieeexplore.ieee.org/document/9763771/){:target="_blank"})

**[IEEE HPCC 2021]** Tun Chen, Haipeng Jia,  Zhihao Li, **Chendi Li**, Yunquan Zhang. **A Transpose-free Three-dimensional FFT Algorithm on ARM CPUs**([link](https://www.researchgate.net/publication/360966539_A_Transpose-free_Three-dimensional_FFT_Algorithm_on_ARM_CPUs){:target="_blank"})

**[CCF HPC China 2020]** **Chendi Li**, Guangting Zhang, Haipeng Jia. **Fast Computation of Elementary Functions on ARM Platforms**(in Chinese)

### Research projects
* **AutoTSMM (Author)**

Designed AutoTSMM, which is used to build high-performance tall-and-skinny matrix multiplication on mainstream CPUs. AutoTSMM can speed up convolution layers in real-world deep learning applications, and the performance is competitive with Intel OneMKL and outperforms all conventional GEMM implementations. This work was published in IEEE ISPA 2021.

* **OpenBLAS (Contributor)**

Optimized pre-pack matrix-matrix multiplication and triangular solve with multiple right-hand-sides(TRSM) on ARMv8 and X86 platforms. OpenBLAS is one of the most famous open-source BLAS libraries.

* **IAAT (Contributor)**

Launched the project and investigated JIT tools for small GEMM. IAAT is a template-driven just-in-time(JIT) small GEMM framework targeting CPUs. This work was accepted by IEEE ICPADS 2021.

* **OpenVML (Co-author)**
  
Enhanced the math functions by manipulating IEEE 754 floating points. OpenVML is a vector mathematical library. It achieves an outstanding performance improvement compared to C standard library and ARMPL. This work was accepted by HPC China 2020.

* **AutoFFT (Contributor)**

Optimized small-scale FFT, and contributed to multi-threading and 2D-FFT. AutoFFT is a template-based FFT codes auto-generation framework that contributes to many Chinese vendors' libraries. This work was published in SC'19, TPDS'20, and was accepted by HPCC'21.

### Patents
* A run-time auto-tune method for non-regular-shaped matrix-matrix multiplication (Pending)

This patent solves the poor performance caused by the excessively high ratio of the packing operation and the inability to reuse the data when the traditional general matrix-matrix multiplication calculates non-regular-shaped matrices.

### Awards & Honors
2021: First-Class Scholarship of Chinese Academy of Sciences
<br/>
2020: Second-class scholarship of Chinese Academy of Sciences
<br/>
2019: Third-Class Scholarship of Chinese Academy of Sciences
<br/>
2019: Outstanding intern in PerfXLab
<br/>
2015: Outstanding volunteer
<br/>
2015: Collegiate programming contest first prize

### Invited Talks

ISPA'21: AutoTSMM: An Auto-tuning Framework for Building High-Performance Tall-and-Skinny Matrix-Matrix Multiplication on CPUs (IEEE ISPA 2021, Virtual Conference)([Youtube](https://www.youtube.com/watch?v=NjIla6zXRHM){:target="_blank"})

HPC-CHINA'20: OpenVML: Fast Computation of Elementary Functions on ARM Platforms(CCF HPC CHINA 2020, Virtual Conference)

### Services
Student Volunteer at HPC CHINA 2021
<br/>
Student Volunteer at HPC CHINA 2020
<br/>
Student Volunteer at HPC CHINA 2019 

---

## Non-academic life
<!---
I have a goal-driven personality. If I have a goal, I will do my best to achieve it. My undergraduate life lacks guidance, but I want to be an outstanding programmer. I put a lot of effort into coding projects and competitive programming to improve my coding skills. After graduation, I worked as a research assistant for the gap year and passed the National Graduate School Admissions Examination with an excellent score. After that, I participated in many scientific research projects and had the opportunity to do some independent research. Most importantly, I have always been eager to learn and challenge myself, so I believe I can become a Ph.D. candidate.
-->

### Personal projects
* **AutoSeed for Private tracker sites**
<br/>
The project is written using Python, it automatically downloads and fills the form to the new site with POST. It is deployed on one of my VPS, although there are still some bugs.

* **Bilibili/Youtube daily backup**
<br/>
I wrote this program via Python, which automatically downloads my favorite Youtubers' video and upload it to my Google Drive.

* **Similarity English words search engine**
<br/>
Sometimes I misunderstand the words' meaning because they look very similar, so I write the project to search all the similar words, it is based on Levenshtein distance.

* **Student Information Management System**
<br/>
A student information management system, I am responsible for the front-end of the website.

* **2014 FIFA World Cup results**
<br/>
An Android app to search for the results of the 2014 FIFA World Cup.

### ACM competition programming
I won the first prize of the "Fingertip Storm" programming contest in HUNAU. And I participated in many competitions, such as Xiangtan Invitational and Hunan University Program Design Competition.

### Volunteer
I have given classes to the primary school, and I have raised fundraising for non-developed regions.

I was an outstanding volunteer in 2015.

---