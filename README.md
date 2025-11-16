## About

Software engineer and researcher specializing in high performance computation, quantization methods, and machine learning systems engineering. I build real time data systems, ML research infrastructure, simulation engines, and performance focused applications using Python, Go, C++, and Rust.

My work focuses on systems that operate under real constraints such as latency, throughput, memory pressure, numerical stability, and energy efficiency. Current research includes precision efficient ML, memory optimized computation, and instruction level acceleration of neural networks.

## Research and Development

### Machine Learning and Quantization
Work in precision efficient ML including INT8 and INT4 quantization, mixed precision methods, and cache aware computational layouts. Research areas include:

- Quantization aware training and dynamic precision control
- Memory locality, branch reduction, and cache optimized kernels
- Improvements to numerical stability in low precision inference
- Energy aware training and inference profiling

### Quantitative Systems
Development of high performance Monte Carlo engines with GPU acceleration, vectorized sampling, and variance reduction. Additional work in risk modeling, backtesting systems, and statistical simulation frameworks.

### Distributed Infrastructure
Building concurrent real time data systems in Go. Focus on lock efficient concurrency, scalable streaming, zero copy data handling, and reliable microservice behavior under load.

### Backend and API Engineering
Designing low latency API layers and distributed backends with clean architecture, predictable performance, and strong observability.

## Projects

### No Imports Neural Network (PyPy3 Based)
A neural network implementation written entirely from scratch with no external libraries. The system uses PyPy3 to avoid CPython interpreter overhead which provides large speedups for inner numerical loops, matrix operations, and gradient propagation. Research areas include numerical stability, precision efficient backpropagation, memory locality, and low level optimization.

### Monte Carlo Risk Simulator
Simulation engine for portfolio risk modeling using variance reduction, GPU parallelism, and stress scenario modeling. Includes automated reporting and batch compute pipelines.

### MatrixPulse
Real time analytics framework written in Go using lock efficient concurrency, zero copy buffering, and streaming ML integration. Designed for very low latency data ingestion and processing.

## Technical Stack

Languages  
Python (CPython and PyPy3), Go, C++, Rust, JavaScript, TypeScript, SQL, Bash

ML and Scientific Computing  
PyTorch, TensorFlow, NumPy, Pandas, Polars, Scikit learn

Backend and Data  
FastAPI, Flask, PostgreSQL, Redis, Snowflake, AWS, GCP

Infrastructure and Tools  
Docker, Git, GitHub Actions, Linux, Nginx, Jupyter, gdb, Valgrind
