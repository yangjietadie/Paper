# Paper
Title: End-to-End Automated Verification for OS Kernels  //
Authors：Jizheng Ding, Xiaoran Zhu, Jian Guo  //
Abstract: 
Formal verification has been recognized as an essential part in improving the correctness and soundness of OS kernels. The verification of OS kernels faces many challenges. For example, the formal proof always comes with difficulties and non-trivial cost. Researchers often have to verify the OS kernel in high level programming languages and ignore low level languages. In this paper, we propose a framework for verifying the whole OS kernel with a low proof burden. We claim it as an end-to-end automated verification framework for the purposes of: (1) verifying the OS kernel that consists of assembler and C languages by formally modeling assembler programs in C level; (2) reasoning the verification with no manual proofs on the basis of SMT. We successfully apply the framework to automatic verifying a commercial operating system μC/OS-II in different hardware architectures, including all the 74 system calls and the core written in mixed-language (i.e., assembler and C). Our framework helps to catch several overflows and type mismatch vulnerabilities of μC/OS-II kernel.

Infomation: 10 pages, 5 figures, accepted by APSEC2018
