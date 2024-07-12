# Awesome-quantum-compilers
Must read research papers and useful links on quantum compiler.
This repo was created voluntarily for me and the research community.


**This repo is still in the process of being edited**
(In the future, I plan to add a GitHub repo corresponding to each paper)


## Contents

+ paper
  + Survey
  + Unified Compilation Framework for Quantum Control
  + Quantum Intermediate Representation
  + Program Representation
  + Instruction scheduling
  + Quantum Program Optimization
  + Quantum ISA
  + Qubit mapping, Qubit allocation
  + Distributed Quantum Computing
+ Books
+ Software
+ Benchmarks and Datasets
+ Conferences
+ Journals



## Papers

**Survey**
+ [Quantum Compiling](https://arxiv.org/abs/2112.00187) - Marco Maronese, Lorenzo Moro, Lorenzo Rocutto, Enrico Prati, 2021


</br></br>

**Unified Compilation Framework for Quantum Control**
 + **Compiler for Neutral Atom Arrays**
   + [Q-Pilot: Field Programmable Qubit Array Compilation with Flying Ancillas](https://arxiv.org/abs/2311.16190) - Hanrui Wang., DAC, 2024 
   + [Compiling quantum circuits for dynamically field-programmable neutral atoms array processors](https://arxiv.org/pdf/2306.03487.pdf) - D. B. Tan et al., 2024
   + [FPQA-C : A Compilation Framework for Field Programmable Qubit Array](https://arxiv.org/abs/2311.15123) - Hanrui Wang, Pengyu Liu, Bochen Tan, Yilian Liu, Jiaqi Gu, David Z. Pan, Jason Cong, Umut Acar, and Song Han, ISCA, 2024
   + [Full-stack quantum computing systems in the NISQ era: algorithm-driven and hardware-aware compilation techniques](https://arxiv.org/abs/2204.06369) - Mendina Bandic, DATE, 2022 
   + [Qubit mapping for reconfigurable atom arrays](https://dl.acm.org/doi/abs/10.1145/3508352.3549331) - B. Tan et al, ICCAD, 2022
   + [Quantum optimization of maximum independent set using Rydberg atom arrays](https://arxiv.org/abs/2202.09372) - S.Ebadi et al., Science, 2022
   + [Geyser: a compilation framework for quantum computing with neutral atoms](https://dl.acm.org/doi/abs/10.1145/3470496.3527428) - T. Patel et al., ISCA, 2022
   + [Exploiting Long-Distance Interactions and Tolerating Atom Loss in Neutral Atom Quantum Architectures](https://arxiv.org/pdf/2111.06469.pdf) -  Jonathan M. Baker, et al. ISCA, 2021
   + [Software-hardware co-optimization for computational chemistry on superconducting quantum processors](https://arxiv.org/abs/2105.07127) - GushuLi, YunongShi, and AliJavadi-Abhari, ISCA, 2021
   + [Optimal mapping for near-term quantum architectures based on Rydberg atoms](https://arxiv.org/abs/2109.04179) - S.Brandhofer et al., ICCAD, 2021

 + **Compiler for Ion Traps**
   + [Hybrid discrete-continuous compilation of trapped-ion quantum circuits with deep reinforcement learning](https://arxiv.org/abs/2307.05744) - Francesco Preti,. Quantum, 2024
   + [Automated Generation of Shuttling Sequences for a Linear Segmented Ion Trap Quantum Computer](https://arxiv.org/abs/2208.04881) - Jonathan Durandau, Quantum, 2023
   + [TISCC: A Surface Code Compiler and Resource Estimator for Trapped-Ion Processors](https://dl.acm.org/doi/abs/10.1145/3624062.3624214) - Tyler Leblond, Ryan S. Bennink, Justin G. Lietz, and Christopher M. Seck, SC, 2023
   + [Backend compiler phases for trapped-ion quantum computers](https://arxiv.org/abs/2206.00544) - T. Schmale et al., 2022
   + [Quantum Circuit Compiler for a Shuttling-Based Trapped Ion Quantum Computer](https://arxiv.org/pdf/2207.01964v2.pdf) - Fabian Kreppel et al., 2022
   + [TILT: Achieving Higher Fidelity on a Trapped-Ion Linear-Tape Quantum Computing Architecture](https://arxiv.org/pdf/2010.15876v3.pdf) - Xin-Chuan Wu, Dripto M Debroy, Yongshan Ding, Jonathan M Baker, Yuri Alexeev, Kenneth R Brown, and Frederic T Chong, HPCA, 2020
   + [Architecting Noisy Intermediate-Scale Trapped Ion Quantum Computers](https://arxiv.org/abs/2004.04706) - Prakash Murali, Dripto M. Debroy, Kenneth R. Brown, and Margaret Martonosi, ISCA, 2020


 + **Superconducting Qubits in Circuit QED**
   + [Systematic Cross talk Mitigation for Superconducting Qubits via Frequency-Aware Compilation](https://arxiv.org/abs/2008.09503), Yongshan Ding, Pranav Gokhale, Sophia Fuhui Lin, Richard Rines, Thomas Propson, Frederic T. Chong, MICRO, 2020



</br></br>
**Quantum Intermediate Representation**
+ [InQuIR: Intermediate Representation for Interconnected Quantum Computers](https://arxiv.org/abs/2302.00267) - Shin Nishio, Ryo Wakizaka, 2023
+ [QSSA: an SSA-based IR for Quantum computing](https://arxiv.org/abs/2109.02409) - Anurudh Peduri, Siddharth Bhat, CC, 2022
+ [Quantum circuit transformations with a multi-level intermediate representation compiler](https://arxiv.org/abs/2112.10677) - T. Nguyen et al., 2021
+ [Enabling Retargetable Optimizing Compilers for Quantum Accelerators via a Multi-Level Intermediate Representation](https://arxiv.org/abs/2109.00506) - Thien Nguyen, Alexander McCaskey, 2021
+ [A MLIR Dialect for Quantum Assembly Languages](https://arxiv.org/abs/2101.11365) - Alexander McCaskey, Thien Nguyen, QCE, 2021
+ [ScaffCC: A Framework for Compilation and Analysis of Quantum Computing Programs](https://arxiv.org/abs/1507.01902) - Ali JavadiAbhari, Shruti Patil, Daniel Kudrow, Jeff Heckey, Alexey Lvov, Frederic T. Chong, Margaret Martonosi, Parallel Comput, CF, 2014
+ [Introducing Quantum Intermediate Representation (QIR)](https://devblogs.microsoft.com/qsharp/introducing-quantum-intermediate-representation-qir/)


</br></br>

**Program Representation**
+ [QIRO: A Static Single Assignment-based Quantum Program Representation for Optimization](https://dl.acm.org/doi/10.1145/3491247) - David Ittah, Thomas Häner, Vadym Kliuchnikov, Torsten Hoefler, ACM Transactions on Quantum Computing, 2021


</br></br>
**Quanum OS**
+ [QOS: A Quantum Operating System](https://arxiv.org/abs/2406.19120) - Emmanouil Giortamis, Francisco Romão, Nathaniel Tornow, Pramod Bhatotia, 2024


</br></br>
**Quantum Circuit Analysis**
+ [QuCT: A Framework for Analyzing Quantum Circuit by Extracting Contextual and Topological Features](https://dl.acm.org/doi/10.1145/3613424.3614274) - Siwei Tan,. MICRO, 2023
+ [Quantum Vulnerability Analysis to Guide Robust Quantum Computing System Design](https://arxiv.org/pdf/2207.14446) - Fang Qi ,2023
  
</br></br>

**Instruction Scheduling**
+ [SCIM MILQ: An HPC Quantum Scheduler](https://arxiv.org/abs/2404.03512) - Philipp Seitz, Manuel Geiger, Christian Ufrecht, Axel Plinge, Christopher Mutschler, Daniel D. Scherer, Christian B. Mendl, Quantum Week, 2024
+ [DISQ: Dynamic Iteration Skipping for Variational Quantum Algorithms](https://arxiv.org/abs/2308.06634) - Junyao Zhang, Hanrui Wang, Gokul Subramanian Ravi, Frederic T. Chong, Song Han, Frank Mueller, Yiran Chen, QCE, 2023
+ [Let Each Quantum Bit Choose Its Basis Gates](https://arxiv.org/abs/2208.13380) - Sophia Fuhui Lin, Sara Sussman, Casey Duckering, Pranav S. Mundada, Jonathan M. Baker, Rohan S. Kumar, Andrew A. Houck, Frederic T. Chong, MICRO, 2022
+ [Software-hardwareco-optimization for computational chemistry on superconducting quantum processors](https://arxiv.org/abs/2105.07127) - Gushu Li, Yunong Shi, Ali Javadi-Abhari, ISCA 2021
+ [Error Mitigation in Quantum Computers through Instruction Scheduling](https://arxiv.org/abs/2105.01760) - Kaitlin N. Smith, Gokul Subramanian Ravi, Prakash Murali, Jonathan M. Baker, Nathan Earnest, Ali Javadi-Abhari, Frederic T. Chong, 2021
+ [EQC: ensembled quantum computing for variational quantum algorithms](https://arxiv.org/abs/2111.14940) - Samuel Stein, Yufei Ding, Nathan Wiebe, Bo Peng, Karol Kowalski, Nathan Baker, James Ang, Ang Li, ISCA, 2022
+ [Software mitigation of crosstalk on noisy intermediate-scale quantum computers](https://arxiv.org/abs/2001.02826) - Prakash Murali, David C. McKay, Margaret Martonosi, Ali Javadi-Abhari, ASPLOS, 2020
+ [TILT: Achieving Higher Fidelity on a Trapped-Ion Linear-Tape Quantum Computing Architecture](https://arxiv.org/abs/2010.15876) - Xin-Chuan Wu, Dripto M. Debroy, Yongshan Ding, Jonathan M. Baker, Yuri Alexeev, Kenneth R. Brown, Frederic T. Chong, HPCA, 2020


</br></br>

**Quantum Program Optimization**
+ [SuperstaQ: Deep Optimization of Quantum Program](https://arxiv.org/abs/2309.05157) - Campbell, Colin, et al. ,QCE, 2023
+ [Paulihedral: a generalized block-wise compiler optimization framework for Quantum simulation kernels](https://arxiv.org/abs/2109.03371) - Gushu Li, Anbang Wu, Yunong Shi, Ali Javadi-Abhari, Yufei Ding, Yuan Xie, 2021
+ [Enabling Dataflow Optimization for Quantum Programs](https://arxiv.org/abs/2101.11030) - David Ittah, Thomas Häner, Vadym Kliuchnikov, Torsten Hoefler, CoRR, 2021
+ [A Meet-in-the-Middle Algorithm for Fast Synthesis of Depth Optimal Quantum Circuits](https://arxiv.org/abs/1206.0758) - Matthew Amy, Dmitri Maslov, Michele Mosca, Martin Roetteler, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2021
+ [Automated optimization of large quantum circuits with continuous parameters](https://arxiv.org/abs/1710.07345) - Yunseong Nam, Neil J. Ross, Yuan Su, Andrew M. Childs, Dmitri Maslov, Nature npj Quantum Information, 2017
+ [A software methodology for compiling quantum programs](https://arxiv.org/abs/1604.01401) - Thomas Häner, Damian S. Steiger, Krysta Svore, Matthias Troyer, 
Quantum Science and Technology, 2016
+ [Exact synthesis of single-qubit unitaries over Clifford-cyclotomic gate sets](https://arxiv.org/abs/1501.04944) - Simon Forest, David Gosset, Vadym Kliuchnikov, David McKinnon, Journal of Mathematical Physics, 2015
+ [Polynomial-TimeT-Depth Optimization of Clifford+T Circuits Via Matroid Partitionin](https://arxiv.org/abs/1303.2042) - Matthew Amy, Dmitri Maslov, Michele Mosca, TCAD, 2013
+ [Assertion-Based Optimization of Quantum Programs](https://arxiv.org/abs/1810.00375) - Häner, Thomas, Hoefler, Torsten, Troyer, Matthias, OOPSLA, 2013
+ [Repeat-until-Success: Non-Deterministic Decomposition of Single-Qubit Unitaries](https://arxiv.org/abs/1311.1074) - Adam Paetznick, Krysta M. Svore, Quantum Information & Computation, 2013
+ [Circuit for Shor’s Algorithm Using 2n+3 Qubits](https://arxiv.org/abs/quant-ph/0205095) - Stephane Beauregard, Quantum Information and Computation, Quantum Information and Computation, 2002


</br></br>

**Quantum ISA**
+ [OpenQASM 3: A Broader and Deeper Quantum Assembly Language](https://dl.acm.org/doi/10.1145/3505636) - Andrew cross, et al., Transactions on Quantum Computing, 2022
+ [Open quantum assembly language](https://arxiv.org/abs/1707.03429) - Andrew W. Cross, Lev S. Bishop, John A. Smolin, Jay M. Gambetta, 2017
+ [A Practical Quantum Instruction Set Architecture](https://arxiv.org/abs/1608.03355) - Robert S. Smith, Michael J. Curtis, William J. Zeng, 2017


</br></br>

**Qubit mapping,** **Qubit allocation**
+ [Qubit Mapping Toward Quantum Advantage](https://arxiv.org/pdf/2210.01306v1.pdf) - Chin-Yi Cheng et al., 2022
+ [Qubit Mapping and Routing via MaxSAT](https://arxiv.org/abs/2208.13679v1) - Abtin Molavi, Amanda Xu, Martin Diges, Lauren Pick, Swamit Tannu, Aws Albarghouthi, MICRO, 2022
+ [Paulihedral: a generalized block-wise compiler optimization framework for Quantum simulation kernels](https://arxiv.org/abs/1901.11054) - Prakash Murali, Jonathan M. Baker, Ali Javadi Abhari, Frederic T. Chong, Margaret Martonosi, ASPLOS, 19
+ [QuCloud: A New Qubit Mapping Mechanism for Multi-programming Quantum Computing in Cloud Environment](https://ieeexplore.ieee.org/document/9407180) - Lei Liu, Xinglei Dou, HPCA, 2021
+ [Time-optimal Qubit mapping](https://dl.acm.org/doi/pdf/10.1145/3445814.3446706) - Chi Zhang et al., ASPLOS, 2021
+ [Not All Qubits Are Created Equal: A Case for Variability-Aware Policies for NISQ-Era Quantum Computers](https://dl.acm.org/doi/10.1145/3297858.3304007) - Swamit S. Tannu, Moinuddin K. Qureshi, ASPLOS, 2019
+ [Noise-adaptive compiler mappings for noisy intermediate-scale quantum computers.](https://arxiv.org/abs/1901.11054) - Prakash Murali, Jonathan M. Baker, Ali Javadi Abhari, Frederic T. Chong, Margaret Martonosi, ASPLOS, 2019 


</br></br>

**Distributed Quantum Computing**
+ [A Modular Quantum Compilation Framework for Distributed Quantum Computing](https://arxiv.org/abs/2305.02969) - Davide Ferrari, Stefano Carretta, Michele Amoretti
IEEE Transactions on Quantum Engineering, 2023
+ [Optimized compiler for distributed quantum computing](https://arxiv.org/abs/2112.14139) - D. Cuomo, ACM Transactions on Quantum Computing, 2023
+ [Divide and Conquer for Combinatorial Optimization and Distributed Quantum Computation](https://arxiv.org/abs/2107.07532) - Teague Tomesh, Zain H. Saleem, Michael A. Perlin, Pranav Gokhale, Martin Suchara, Margaret Martonosi, QCE, 2023
+ [Compiler design for distributed quantum computing](https://arxiv.org/abs/2404.17077) - D. Ferrari, IEEE Transactions on Quantum Engineering, 2021
</br></br>


## Related-repos & pages
+ [Awesome-quantum-computing](https://github.com/desireevl/awesome-quantum-computing)
+ [Awesome-Quantum-Computation](https://github.com/hsavit1/Awesome-Quantum-Computation)
+ [Awesome-quantum-software](https://github.com/qosf/awesome-quantum-software?tab=readme-ov-file#quantum-compilers)
+ [Awesome-quantum-machine-leaning](https://krishnakumarsekar.github.io/awesome-quantum-machine-learning/)
+ [Awesome-post-quantum](https://github.com/veorq/awesome-post-quantum)
+ [Awesome-he](https://github.com/jonaschn/awesome-he)

## Books

+ [Quantum Computer Systems Research for Noisy Intermediate-Scale Quantum Computers (Synthesis Lectures on Computer Architecture)-Morgan & Claypool Publishers (2020)](https://www.amazon.com/Quantum-Computer-Systems-Intermediate-Scale-Architecture/dp/168173866X/ref=sr_1_1?crid=2K59KWTC2A6IG&dib=eyJ2IjoiMSJ9.FgRSqqg5BPKkIMPcNZN4SDxi0rLadqKNi_gKEwfnfdbx3NVbf-QqRugr0cm0gkqz.IP3MXubP83FTCTx1iDY4mGPq-3PRGX21K_rEV4QrWHU&dib_tag=se&keywords=Quantum+Computer+Systems+Research+for+Noisy+Intermediate-Scale+Quantum+Computers&qid=1711388706&s=books&sprefix=quantum+computer+systems+research+for+noisy+intermediate-scale+quantum+computers%2Cstripbooks-intl-ship%2C337&sr=1-1)




## Conference
 + HPCA, ASPLOS, ISCA, MICRO, ICCAD, DAC, CC </br>
 + QCE(Quantum Computing and Engineering) </br>
 + CF(Computing Frontiers)

## Journal
 + IEEE Transactions on Quantum Engineering </br>
 + Quantum Information & Computation </br>
 + Quantum Science and Technology </br>
 + ACM on Programming Languages </br>
 + Journal of Mathematical Physic </br>
 + Quantum Information and Computation </br>
 + IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems </br>
 + ACM Transactions on Quantum Computing </br>
 + Computing Research Repository(CoRR) </br>
 + Nature npj Quantum Information </br>
 + Transactions on Computer-Aided Design of Integrated Circuits and Systems </br>
 + OOPSLA


