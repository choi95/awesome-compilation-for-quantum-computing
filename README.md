# awesome-quantum-compilers
Must read research papers and links on quantum compiler.


**This repo is still in the process of being edited**



## Contents

+ paper
  + Survey
  + Quantum Intermediate Representation
  + Program Representation
  + Instruction scheduling
  + Quantum Program Optimization
  + Quantum ISA
  + Qubit mapping
  + Quantum Compiler Framework
+ Books
+ Software
+ Benchmarks and Datasets
+ Conferences
+ Journals



## Papers

**Survey**
+ [Quantum Compiling](https://arxiv.org/abs/2112.00187) - Marco Maronese, Lorenzo Moro, Lorenzo Rocutto, Enrico Prati, 2021



**Quantum Intermediate Representation**
+ [InQuIR: Intermediate Representation for Interconnected Quantum Computers](https://arxiv.org/abs/2302.00267) - Shin Nishio, Ryo Wakizaka, 2023
+ [QSSA: an SSA-based IR for Quantum computing](https://arxiv.org/abs/2109.02409) - Anurudh Peduri, Siddharth Bhat, 2021
+ [Enabling Retargetable Optimizing Compilers for Quantum Accelerators via a Multi-Level Intermediate Representation](https://arxiv.org/abs/2109.00506) - Thien Nguyen, Alexander McCaskey, 2021
+ [A MLIR Dialect for Quantum Assembly Languages](https://arxiv.org/abs/2101.11365) - Alexander McCaskey, Thien Nguyen, 2021
+ [ScaffCC: A Framework for Compilation and Analysis of Quantum Computing Programs](https://arxiv.org/abs/1507.01902) - Ali JavadiAbhari, Shruti Patil, Daniel Kudrow, Jeff Heckey, Alexey Lvov, Frederic T. Chong, Margaret Martonosi, 2015
+ [Introducing Quantum Intermediate Representation (QIR)](https://devblogs.microsoft.com/qsharp/introducing-quantum-intermediate-representation-qir/)

**Program Representation**
+ [QIRO: A Static Single Assignment-based Quantum Program Representation for Optimization](https://dl.acm.org/doi/10.1145/3491247) - David Ittah, Thomas Häner, Vadym Kliuchnikov, Torsten Hoefler, ACM Transactions on Quantum Computing


**Instruction scheduling**
+ [Software-hardwareco-optimization for computational chemistry on superconducting quantum processors](https://arxiv.org/abs/2105.07127) - Gushu Li, Yunong Shi, Ali Javadi-Abhari, 2021, ISCA
+ [Let Each Quantum Bit Choose Its Basis Gates](https://arxiv.org/abs/2208.13380) - Sophia Fuhui Lin, Sara Sussman, Casey Duckering, Pranav S. Mundada, Jonathan M. Baker, Rohan S. Kumar, Andrew A. Houck, Frederic T. Chong, 2022, MICRO
+ [Software mitigation of crosstalk on noisy intermediate-scale quantum computers](https://arxiv.org/abs/2001.02826) - Prakash Murali, David C. McKay, Margaret Martonosi, Ali Javadi-Abhari, 2020, ASPLOS
+ [Error Mitigation in Quantum Computers through Instruction Scheduling](https://arxiv.org/abs/2105.01760) - Kaitlin N. Smith, Gokul Subramanian Ravi, Prakash Murali, Jonathan M. Baker, Nathan Earnest, Ali Javadi-Abhari, Frederic T. Chong, 2021
+ [EQC: ensembled quantum computing for variational quantum algorithms](https://arxiv.org/abs/2111.14940) - Samuel Stein, Yufei Ding, Nathan Wiebe, Bo Peng, Karol Kowalski, Nathan Baker, James Ang, Ang Li, 2021
+ [TILT: Achieving Higher Fidelity on a Trapped-Ion Linear-Tape Quantum Computing Architecture](https://arxiv.org/abs/2010.15876) - Xin-Chuan Wu, Dripto M. Debroy, Yongshan Ding, Jonathan M. Baker, Yuri Alexeev, Kenneth R. Brown, Frederic T. Chong, 2020
+ [DISQ: Dynamic Iteration Skipping for Variational Quantum Algorithms](https://arxiv.org/abs/2308.06634) - Junyao Zhang, Hanrui Wang, Gokul Subramanian Ravi, Frederic T. Chong, Song Han, Frank Mueller, Yiran Chen, 2023


**Quantum Program Optimization**
+ [SuperstaQ: Deep Optimization of Quantum Program](https://arxiv.org/abs/2309.05157) - Campbell, Colin, et al. ,IEEE QCE, 2023
+ [Enabling Dataflow Optimization for Quantum Programs](https://arxiv.org/abs/2101.11030) - David Ittah, Thomas Häner, Vadym Kliuchnikov, Torsten Hoefler, 2021
+ [A Meet-in-the-Middle Algorithm for Fast Synthesis of Depth Optimal Quantum Circuits](https://arxiv.org/abs/1206.0758) - Matthew Amy, Dmitri Maslov, Michele Mosca, Martin Roetteler, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2021
+ [Circuit for Shor’s Algorithm Using 2n+3 Qubits](https://arxiv.org/abs/quant-ph/0205095) - Stephane Beauregard, Quantum Information and Computation, 2002
+ [Exact synthesis of single-qubit unitaries over Clifford-cyclotomic gate sets](https://arxiv.org/abs/1501.04944) - Simon Forest, David Gosset, Vadym Kliuchnikov, David McKinnon, Journal of Mathematical Physics, 2015
+ [Polynomial-TimeT-Depth Optimization of Clifford+T Circuits Via Matroid Partitionin](https://arxiv.org/abs/1303.2042) - Matthew Amy, Dmitri Maslov, Michele Mosca, IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 2013
+ [Assertion-Based Optimization of Quantum Programs](https://arxiv.org/abs/1810.00375) - Häner, Thomas, Hoefler, Torsten, Troyer, Matthias, 2013
+ [A software methodology for compiling quantum programs](https://arxiv.org/abs/1604.01401) - Thomas Häner, Damian S. Steiger, Krysta Svore, Matthias Troyer, 2016
+ [Automated optimization of large quantum circuits with continuous parameters](https://arxiv.org/abs/1710.07345) - Yunseong Nam, Neil J. Ross, Yuan Su, Andrew M. Childs, Dmitri Maslov, Quantum Information, 2017
+ [Repeat-until-Success: Non-Deterministic Decomposition of Single-Qubit Unitaries](https://arxiv.org/abs/1311.1074) - Adam Paetznick, Krysta M. Svore, Quantum Information & Computation, 2013


**Quantum ISA**
+ [Open quantum assembly language](https://arxiv.org/abs/1707.03429)
+ [A Practical Quantum Instruction Set Architecture](https://arxiv.org/abs/1608.03355)



**Qubit mapping,** **Qubit allocation**
+ [Qubit Mapping Toward Quantum Advantage](https://arxiv.org/pdf/2210.01306v1.pdf)
+ [Time-optimal Qubit mapping](https://dl.acm.org/doi/pdf/10.1145/3445814.3446706)
+ [Not All Qubits Are Created Equal: A Case for Variability-Aware Policies for NISQ-Era Quantum Computers](https://dl.acm.org/doi/10.1145/3297858.3304007)
+ [Noise-adaptive compiler mappings for noisy intermediate-scale quantum computers.](https://arxiv.org/abs/1901.11054)
+ [Qubit Mapping and Routing via MaxSAT](https://arxiv.org/abs/2208.13679v1)
+ [QuCloud: A New Qubit Mapping Mechanism for Multi-programming Quantum Computing in Cloud Environment](https://ieeexplore.ieee.org/document/9407180)



**Quantum Compiler Framework**
+ [Bosehedral: Compiler Optimization for Bosonic Quantum Computing](https://arxiv.org/pdf/2402.02279.pdf)


**Distributed Quantum Computing**
+ [A Modular Quantum Compilation Framework for Distributed Quantum Computing](https://arxiv.org/abs/2305.02969)



## Software
[awesome-quantum-software](https://github.com/qosf/awesome-quantum-software?tab=readme-ov-file#quantum-compilers) - This section is based on this GitHub Repo.


C++
 + QCOR - C++ language extension and associated compiler implementation for hybrid quantum-classical programming.
 + ScaffCC - Compilation, analysis and optimization framework for the Scaffold quantum programming language.
 + tweedledum - C++17 library for analysis, compilation/synthesis, and optimization of quantum circuits.

Mathematica
 + UniversalQCompiler - Synthesis of isometries (including unitaries and state preparation), channels and POVMs.

Julia
 + QuantumCircuitOpt.jl - Julia package for provably optimal decompositions and compilations of quantum circuits

Python
 + Arline Benchmarks - Automated benchmarking platform for quantum compilers, quantum hardware and quantum algorithms.
 + BQSKit - Berkeley Quantum Synthesis Toolkit is an optimizing quantum compiler and related tool-set.
 + Mitiq - Cross-platform, error-mitigating quantum compiler from Unitary Fund.
 + NchooseK - Constraint-programming system that compiles to both circuit-model quantum computers and quantum annealers.
 + PyZX - Python library for quantum circuit rewriting and optimisation using the ZX-calculus.
 + QEDA - Quantum electronic design automation software for optical circuits using QASM.
 + QGL2 Compiler - Language compiler for imperative Quantum Gate Language (QGL).
 + Qiskit Terra - Python library for quantum circuit rewriting and optimization (supported by IBM).
 + Qubiter - Quantum compiler with Python wrapper for LAPACK's CS Decomposition to build a binary tree of matrices.
 + SAT Circuits Engine - Qiskit-based high-level quantum circuits synthesis engine for n-SAT problems.

Common Lisp
 + quilc - Rigetti's optimizing Quil compiler.


## BooKs

+ [Quantum Computer Systems Research for Noisy Intermediate-Scale Quantum Computers (Synthesis Lectures on Computer Architecture)-Morgan & Claypool Publishers (2020)](https://www.amazon.com/Quantum-Computer-Systems-Intermediate-Scale-Architecture/dp/168173866X/ref=sr_1_1?crid=2K59KWTC2A6IG&dib=eyJ2IjoiMSJ9.FgRSqqg5BPKkIMPcNZN4SDxi0rLadqKNi_gKEwfnfdbx3NVbf-QqRugr0cm0gkqz.IP3MXubP83FTCTx1iDY4mGPq-3PRGX21K_rEV4QrWHU&dib_tag=se&keywords=Quantum+Computer+Systems+Research+for+Noisy+Intermediate-Scale+Quantum+Computers&qid=1711388706&s=books&sprefix=quantum+computer+systems+research+for+noisy+intermediate-scale+quantum+computers%2Cstripbooks-intl-ship%2C337&sr=1-1)



## Benchmarks and Datasets



## Conference
CGO, CC, PACT, HPCA, ASPLOS


## Journal

