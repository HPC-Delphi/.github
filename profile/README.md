# HPC-Delphi

Welcome to the **HPC-Delphi** organization. This workspace hosts a collection of open-source libraries, wrappers, and benchmarking suites designed to bring High-Performance Computing (HPC) capabilities to Delphi Pascal applications.

This ecosystem bridges the gap between native Delphi applications and highly optimized C-based infrastructure, including SIMD vectorization, OpenMP multi-threading, and Message Passing Interface (MPI) for distributed systems.

## 🔬 Academic Research
The software in this organization has been developed and published in collaboration with the **Universidad de Murcia**. It serves as the foundational architecture for evaluating the performance and viability of Delphi in compute-intensive and numerical algebraic domains.

## 📦 Core Ecosystem

Our architecture is highly modular, separating low-level hardware optimizations from the high-level benchmarking logic:

* 📊 **[DelphiMatrixBenchmark](https://github.com/HPC-Delphi/DelphiMatrixBenchmark)**: The core reproducibility suite. Orchestrates, validates, and measures the performance of all underlying algorithms (Sequential, OpenMP, SIMD, MPI, MKL).
* 🧮 **[offc_delphi](https://github.com/HPC-Delphi/offc_delphi)**: Standard C matrix operations and OpenMP implementations.
* 🚀 **[vector_simd_delphi](https://github.com/HPC-Delphi/vector_simd_delphi)**: Hardware-accelerated mathematical operations using Intel AVX/SSE2 intrinsics.
* 🌐 **[mpi_delphi](https://github.com/HPC-Delphi/mpi_delphi)**: Microsoft MPI (MSMPI) wrappers for distributed-memory parallelism.
* 🔵 **[mkl_delphi](https://github.com/HPC-Delphi/mkl_delphi)**: Integration with the industry-standard Intel Math Kernel Library (CBLAS).

## 📖 Citation & Usage
All repositories are open-source and licensed under the MIT License. If you use this software suite in your academic work, please refer to the `CITATION.cff` file located in the root of each repository to cite the specific modules used.

---
*Maintained by Daniel Galdo.*
