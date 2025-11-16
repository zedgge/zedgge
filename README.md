## About

Software engineer and researcher specializing in **high-performance computation**, **quantization**, and **machine learning systems engineering**. I build real-time data systems, ML research infrastructure, simulation engines, and performance-critical applications across Python, Go, C++, and Rust.

My work focuses on systems that must operate under real constraints—**latency**, **throughput**, **memory pressure**, **numerical stability**, and **energy efficiency**. Current research centers on **precision-efficient ML** (INT8/INT4, mixed precision), memory-optimized computation, and instruction-level acceleration of neural networks.

---

## Research & Development

### Machine Learning & Quantization
Developing precision-efficient ML methods including INT8/INT4 quantization, mixed precision strategies, and cache-aware computational layouts. Research includes:

- Quantization-aware training and dynamic precision control  
- Memory locality, branch reduction, and cache-optimized kernels  
- Numerical stability improvements in low-precision inference  
- Energy-aware training and inference profiling  

### Quantitative Systems
Development of high-performance Monte Carlo engines using GPU acceleration, vectorized sampling, and advanced variance reduction. Work includes risk modeling, backtesting systems, and statistical simulation frameworks.

### Distributed Infrastructure
Building concurrent real-time data systems in Go. Focus on lock-efficient concurrency, scalable streaming, zero-copy data handling, and microservice reliability under high load.

### Backend & API Engineering
Designing low-latency API layers, distributed backends, and microservices with clean architecture, observability, and predictable performance characteristics.

---

## Projects

### No-Imports Neural Network (PyPy3-Optimized)
A neural network built **entirely from scratch with zero external libraries**, using only basic Python primitives. Implemented on **PyPy3** to bypass CPython interpreter overhead—resulting in **multi-x speedups** for tight numerical loops, matrix operations, and gradient propagation.  
Research areas: numerical stability, precision-efficient backprop, memory locality, and instruction-level optimization.

### Monte Carlo Risk Simulator
Production-grade simulation engine for portfolio risk modeling. Utilizes variance reduction strategies, GPU parallelization, and stress-scenario modeling. Includes automated reporting and batch-mode compute pipelines.

### MatrixPulse
High-throughput real-time analytics framework in Go. Built on lock-efficient concurrency primitives, zero-copy buffering, and streaming ML integration. Designed for ultra-low-latency data ingestion and processing.

---

## Technical Stack

**Languages**  
`Python (CPython + PyPy3)` · `Go` · `C++` · `Rust` · `JavaScript/TypeScript` · `SQL` · `Bash`

**ML & Scientific Computing**  
`PyTorch` · `TensorFlow` · `NumPy` · `Pandas` · `Polars` · `Scikit-learn`

**Backend & Data**  
`FastAPI` · `Flask` · `PostgreSQL` · `Redis` · `Snowflake` · `AWS` · `GCP`

**Infrastructure & Tools**  
`Docker` · `Git` · `GitHub Actions` · `Linux` · `Nginx` · `Jupyter` · `gdb` · `Valgrind`
