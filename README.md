Hi, I'm Dimitrije, a software engineering student at Curtin University in Perth interested in
C++ and low-level programming.
[Contact](mailto:dimitrijesmc@gmail.com)

## PAST — CubeSat Telemetry Validation

A bare-metal STM32L4 firmware that encodes and transmits telemetry packets over UART,
paired with a Python receiver that parses frames 
[Dim-Sim7/PAST-CubeSat-Telemetry-Validation](https://github.com/Dim-Sim7/PAST-CubeSat-Telemetry-Validation

## Order Book

A client-server order book matching engine written in C++. The server maintains
a live book of limit and market orders, matching incoming orders against resting
ones using price-time priority.
[Dim-Sim7/client_server_orderbook](https://github.com/Dim-Sim7/client_server_orderbook)

## Ring Buffer

A lock-free SPSC ring buffer in C++, built across six iterations each introducing
one optimisation: thread safety, cache-line alignment to eliminate false sharing,
acquire/release memory ordering to reduce synchronisation overhead, and cached
index reads to cut cross-core atomic loads. Each version is benchmarked with
`perf` to measure the impact.  
[Dim-Sim7/Ring-Buffer](https://github.com/Dim-Sim7/Ring-Buffer)

## CUDA GPU Renderer

A 3D software rasterizer implemented twice - once on the CPU with OpenMP across
6 cores, once on the GPU with CUDA using tile-based deferred rendering across
262,144 threads.
[Dim-Sim7/CUDA-GPU-Renderer](https://github.com/Dim-Sim7/CUDA-GPU-Renderer)
