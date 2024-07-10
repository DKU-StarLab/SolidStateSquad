# Solid-State Squad
This is a study group studying SSD, FTL, and FEMU in 2024.

## Goal
- **Study for Flash Translation layer to Maximize the performance of storage system.**<br>
- **Understanding mapping tables, wear leveling, and garbage collection.**<br>
- **FTL Code Analysis.**


## 논문 발표
|          | Date       |  논문    |발표자     |Link     |
|----------|------------|----------|--------|---------|
| week01   | 2024-07-03 | OT       | 최건희 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|
| week02   | 2024-07-10 | Rosenblum, Mendel, and John K. Ousterhout. "The design and implementation of a log-structured file system." ACM Transactions on Computer Systems (TOCS) 10.1 (1992): 26-52. [Link](https://people.eecs.berkeley.edu/~brewer/cs262/LFS.pdf) | 김나경 | [LFS](./presentations/Week2/W2_LFS_김나경.pdf) |
| week02   | 2024-07-10 | Park, Chanik, et al. "A reconfigurable FTL (flash translation layer) architecture for NAND flash-based applications." ACM Transactions on Embedded Computing Systems (TECS) 7.4 (2008): 1-23. [Link](https://people.eecs.berkeley.edu/~kubitron/courses/cs262a-F19/handouts/papers/a38-park.pdf) | 구선주,<br>박수지 |[RFTL](./presentations/Week2/W2_RFTL_구선주_박수지.pdf)|
| week03   | 2024-07-17 | Gupta, Aayush, Youngjae Kim, and Bhuvan Urgaonkar. "DFTL: a flash translation layer employing demand-based selective caching of page-level address mappings." Acm Sigplan Notices 44.3 (2009): 229-240. [Link](https://dl.acm.org/doi/10.1145/1508284.1508271) | 김주현,<br>이용민 |
| week03   | 2024-07-17 | Agrawal, Nitin, et al. "Design tradeoffs for SSD performance." 2008 USENIX Annual Technical Conference (USENIX ATC 08). 2008. [Link](https://www.usenix.org/legacy/events/usenix08/tech/full_papers/agrawal/agrawal.pdf) | 김민성,<br>위다연 |
| week04   | 2024-07-24 | Kim, Bryan S., Jongmoo Choi, and Sang Lyul Min. "Design tradeoffs for SSD reliability." 17th USENIX Conference on File and Storage Technologies (FAST 19). 2019. [Link](https://www.usenix.org/conference/fast19/presentation/kim-bryan) | 신수환 |
| week04   | 2024-07-24 | Oh, Seonggyun, et al. "MIDAS: Minimizing Write Amplification in Log-Structured Systems through Adaptive Group Number and Size Configuration." 22nd USENIX Conference on File and Storage Technologies (FAST 24). 2024. [Link](https://www.usenix.org/conference/fast24/presentation/oh) | 구선주,<br>박수지 |
| week05   | 2024-07-31 | Jun, Yuhun, et al. "We Ain't Afraid of No File Fragmentation: Causes and Prevention of Its Performance Impact on Modern Flash SSDs." 22nd USENIX Conference on File and Storage Technologies (FAST 24). 2024. [Link](https://www.usenix.org/conference/fast24/presentation/jun) | 김주현,<br>이용민 |
| week05   | 2024-07-31 | Sun, Jinghan, et al. "Leaftl: A learning-based flash translation layer for solid-state drives." Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2. 2023. [Link](https://dl.acm.org/doi/abs/10.1145/3575693.3575744) | 최연규 |
| week06   | 2024-08-07 | Wang, Shengzhe, et al. "LearnedFTL: A Learning-Based Page-Level FTL for Reducing Double Reads in Flash-Based SSDs." 2024 IEEE International Symposium on High-Performance Computer Architecture (HPCA). IEEE, 2024. [Link](https://ieeexplore.ieee.org/abstract/document/10476463) | 김민성,<br>위다연 |
| week06   | 2024-08-07 | Niu, Fuping, et al. "FlashGNN: An In-SSD Accelerator for GNN Training." 2024 IEEE International Symposium on High-Performance Computer Architecture (HPCA). IEEE, 2024. [Link](https://ieeexplore.ieee.org/abstract/document/10476462) | 신수환 |
| week07   | 2024-08-14 | Kim, Shine, et al. "Behemoth: a flash-centric training accelerator for extreme-scale DNNs." 19th USENIX Conference on File and Storage Technologies (FAST 21). 2021. [Link](https://www.usenix.org/conference/fast21/presentation/kim) | 김나경 |
| week08   | 2024-08-21 | Wong, Daniel Lin-Kit, et al. "Baleen: ML Admission & Prefetching for Flash Caches." 22nd USENIX Conference on File and Storage Technologies (FAST 24). 2024. [Link](https://www.usenix.org/conference/fast24/presentation/wong)  | 최연규 |
| week08   | 2024-08-28 | Final Presentation | ALL |
## FTL 분석 및 개발
|          | Team       | Link |
|----------|------------| -----|
|1         |김민성, 위다연, 김나경| - |
|2         |이용민, 김주현, 최연규, 김보승, 신수환| - |
|3         |구선주, 박수지, 오여진, 쥬용지에| - |

## 참여자
- 학부과정 : 박수지, 김민성, 이용민, 구선주, 위다연, 김보승, 오여진
- 석사과정 : 쥬용지에, 신수환, 김나경, 최연규, 김주현
- 박사과정 : 최건희, 이제연, 신호진

## For Beginners
1. 개발자를 위한 SSD (Coding for SSD), Kakao Tech 번역, [Link](https://tech.kakao.com/posts/326)
2. Flash 101 and Flash Managment, Western Digital, [Link](https://documents.westerndigital.com/content/dam/doc-library/en_us/assets/public/western-digital/collateral/white-paper/white-paper-sandisk-flash101-management.pdf)

## List of Papers
1. Rosenblum, Mendel, and John K. Ousterhout. "The design and implementation of a log-structured file system." ACM Transactions on Computer Systems (TOCS) 10.1 (1992): 26-52. [Link](https://people.eecs.berkeley.edu/~brewer/cs262/LFS.pdf)
2. Park, Chanik, et al. "A reconfigurable FTL (flash translation layer) architecture for NAND flash-based applications." ACM Transactions on Embedded Computing Systems (TECS) 7.4 (2008): 1-23. [Link](http://csl.skku.edu/papers/tecs08.pdf)
3. Gupta, Aayush, Youngjae Kim, and Bhuvan Urgaonkar. "DFTL: a flash translation layer employing demand-based selective caching of page-level address mappings." Acm Sigplan Notices 44.3 (2009): 229-240. [Link](https://dl.acm.org/doi/10.1145/1508284.1508271)
4. Agrawal, Nitin, et al. "Design tradeoffs for SSD performance." 2008 USENIX Annual Technical Conference (USENIX ATC 08). 2008. [Link](https://www.usenix.org/legacy/events/usenix08/tech/full_papers/agrawal/agrawal.pdf)
5. Kim, Bryan S., Jongmoo Choi, and Sang Lyul Min. "Design tradeoffs for SSD reliability." 17th USENIX Conference on File and Storage Technologies (FAST 19). 2019. [Link](https://www.usenix.org/conference/fast19/presentation/kim-bryan)
6. Oh, Seonggyun, et al. "MIDAS: Minimizing Write Amplification in Log-Structured Systems through Adaptive Group Number and Size Configuration." 22nd USENIX Conference on File and Storage Technologies (FAST 24). 2024. [Link](https://www.usenix.org/conference/fast24/presentation/oh)
7. Jun, Yuhun, et al. "We Ain't Afraid of No File Fragmentation: Causes and Prevention of Its Performance Impact on Modern Flash SSDs." 22nd USENIX Conference on File and Storage Technologies (FAST 24). 2024. [Link](https://www.usenix.org/conference/fast24/presentation/jun)
8. Sun, Jinghan, et al. "Leaftl: A learning-based flash translation layer for solid-state drives." Proceedings of the 28th ACM International Conference on Architectural Support for Programming Languages and Operating Systems, Volume 2. 2023. [Link](https://dl.acm.org/doi/abs/10.1145/3575693.3575744)
9. Wang, Shengzhe, et al. "LearnedFTL: A Learning-Based Page-Level FTL for Reducing Double Reads in Flash-Based SSDs." 2024 IEEE International Symposium on High-Performance Computer Architecture (HPCA). IEEE, 2024. [Link](https://ieeexplore.ieee.org/abstract/document/10476463)
10. Niu, Fuping, et al. "FlashGNN: An In-SSD Accelerator for GNN Training." 2024 IEEE International Symposium on High-Performance Computer Architecture (HPCA). IEEE, 2024. [Link](https://ieeexplore.ieee.org/abstract/document/10476462)
11. Kim, Shine, et al. "Behemoth: a flash-centric training accelerator for extreme-scale DNNs." 19th USENIX Conference on File and Storage Technologies (FAST 21). 2021. [Link](https://www.usenix.org/conference/fast21/presentation/kim)
12. Wong, Daniel Lin-Kit, et al. "Baleen: ML Admission & Prefetching for Flash Caches." 22nd USENIX Conference on File and Storage Technologies (FAST 24). 2024. [Link](https://www.usenix.org/conference/fast24/presentation/wong)

## Simulation
1. **FEMU**, Li, Huaicheng, et al. "The CASE of FEMU: Cheap, accurate, scalable and extensible flash emulator." 16th USENIX Conference on File and Storage Technologies (FAST 18). 2018. [Paper Link](https://www.usenix.org/system/files/conference/fast18/fast18-li.pdf)   Git[:octocat:](https://github.com/MoatLab/FEMU)
2. **NVMeVirt**, Kim, Sang-Hoon, et al. "{NVMeVirt}: A Versatile Software-defined Virtual {NVMe} Device." 21st USENIX Conference on File and Storage Technologies (FAST 23). 2023. [Paper Link](https://www.usenix.org/conference/fast23/presentation/kim-sang-hoon)    Git[:octocat:](https://github.com/snu-csl/nvmevirt)
3. **MQSim**, Tavakkol, Arash, et al. "{MQSim}: A framework for enabling realistic studies of modern Multi-Queue SSD devices." 16th USENIX Conference on File and Storage Technologies (FAST 18). 2018. [Paper Link](https://www.usenix.org/conference/fast18/presentation/tavakkol)   Git[:octocat:](https://github.com/CMU-SAFARI/MQSim)
