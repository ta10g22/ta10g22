# 👋 Hi, I'm Tochi

I'm an **MSc Computer Science student at the University of Edinburgh** and a First-Class Electronic & Electrical Engineering graduate interested in **machine learning systems, high-performance C++, computer architecture, and hardware acceleration**.

I'm particularly interested in understanding and improving how **machine learning models move from frameworks through runtimes, compilers, kernels, and ultimately onto hardware**.

## 🧠 About Me

* Building **ML inference and systems software in C++**
* Interested in **ML runtimes, compilers, computer architecture, and performance engineering**
* Background in **RISC-V, RTL design, embedded systems, and hardware acceleration**
* Currently exploring:

  * ML inference runtimes and computational graphs
  * CPU kernel optimisation and multithreading
  * Compiler and graph optimisations
  * Memory-efficient model execution
  * Hardware/software co-design for AI acceleration

## 🚀 Projects

### TinyInfer — C++ Machine Learning Inference Runtime

Building a lightweight **machine learning inference runtime from scratch in C++** to explore how models are represented, optimised, and efficiently executed on hardware.

Current work includes:

* **ONNX model and weight loading**
* Computational graph construction and execution
* Modular tensor and operator implementations
* Linear, ReLU, Softmax and matrix multiplication operators
* **Cache-blocked and multithreaded GEMM kernels**
* Graph optimisations including **operator fusion, constant folding, and dead-code elimination**
* Benchmarking custom kernels against established ML frameworks
* Exploring profiling, memory planning, and buffer reuse for efficient inference

The project is designed to develop a deeper understanding of the full ML execution stack:

`Model → Graph → Optimisation → Runtime → Kernels → Hardware`

### RISC-V Sparse Matrix Accelerator

Designed a custom accelerator for sparse matrix operations integrated with a **RISC-V system**, exploring hardware/software co-design for efficient computation.

* Developed synthesizable hardware
* Created a memory-mapped software interface
* Wrote bare-metal C firmware to control the accelerator
* Explored hardware acceleration for sparse workloads

### MIPS 5-Stage Pipeline Simulator

Built a **C++ simulator for a pipelined MIPS processor** with:

* 5-stage instruction pipeline
* Data forwarding
* Hazard detection
* Load-use stalls
* Branch handling
* Per-cycle pipeline tracing
* Two-pass assembler

## 🛠️ Technologies

**Languages:** C++, Python, C, SystemVerilog

**ML / Systems:** ONNX, PyTorch, ML inference, computational graphs, multithreading, performance optimisation

**Hardware:** RISC-V, RTL Design, FPGA Development, Computer Architecture

**Tools:** Git, GitHub, CMake, ModelSim, Quartus, VS Code

## 🎯 Current Interests

* Machine Learning Systems
* ML Runtimes & Compilers
* High-Performance C++
* CPU / GPU Compute
* Computer Architecture
* AI Accelerators
* Performance Engineering
* Hardware/Software Co-design

## 📫 Connect

* [LinkedIn](https://www.linkedin.com/in/tochi-anyanwu-34600b253/)
* Email: [tochipartnerships@gmail.com](mailto:tochipartnerships@gmail.com)
