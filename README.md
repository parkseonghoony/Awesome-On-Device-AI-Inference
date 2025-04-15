# Awesome-On-Device-AI-Inference 🔍📲
This list highlights academic work focused on running AI models efficiently on resource-constrained mobile devices, including (1) **edge devices** (e.g., NVIDIA Jetson), (2) **smartphones** (e.g., Snapdragon/Exynos), (3) and **microcontrollers** for energy-harvesting or batteryless IoT devices, with a primary focus on research conducted for edge devices & smartphones. Just so you know, this repo references [Awesome-On-Device-AI-Systems](https://github.com/jeho-lee/Awesome-On-Device-AI-Systems) by [Jeho Lee](https://jeho-lee.github.io/). 

### A-1. Single-DNN Inference on Single Mobile Processors
**Application-specific tasks**
* [AAAI 2025] E4: Energy-Efficient DNN Inference for Edge Video Analytics Via Early Exiting and DVFS [(Paper)](https://ojs.aaai.org/index.php/AAAI/article/view/32104)
  * Video analytics; Edge devices; GPU
* [MobiCom 2024] Panopticus: Omnidirectional 3D Object Detection on Resource-constrained Edge Devices [(Paper)](https://arxiv.org/abs/2410.01270)
  * 3D object detection; Edge devices; GPU
* [MobiSys 2023] OmniLive: Super-Resolution Enhanced 360° Video Live Streaming for Mobile Devices [(Paper)](https://dl.acm.org/doi/abs/10.1145/3581791.3596851)
  * Video super-resolution; Smartphones; GPU
* [IEEE TMC 2023] NAWQ-SR: A Hybrid-Precision NPU Engine for Efficient On-Device Super-Resolution [(Paper)](https://ieeexplore.ieee.org/iel7/7755/4358975/10066526)
  * Single-image super-resolution; Smartphones; NPU
* [UbiComp 2022] Efficient On-Device Visual Question Answering [(Paper)](https://dl.acm.org/doi/10.1145/3534619)
  * Visual question answering; Edge devices & smartphones; GPU
* [MobiCom 2021] Flexible High-Resolution Object Detection on Edge Devices with Tunable Latency [(Paper)](https://dl.acm.org/doi/10.1145/3447993.3483274)
  * Object detection; Edge devices; GPU
* [MobiCom 2020] NEMO: enabling neural-enhanced video streaming on commodity mobile devices [(Paper)](https://dl.acm.org/doi/abs/10.1145/3372224.3419185)
  * Video super-resolution; Smartphones; GPU

**Traditional DNNs**
* [TMC 2025] NeuroBalancer: Balancing System Frequencies With Punctual Laziness for Timely and Energy-Efficient DNN Inferences [(Paper)](https://ieeexplore.ieee.org/abstract/document/10819653)
  * Smartphones; GPU
* [MobiCom 2022] Romou: Rapidly Generate High-Performance Tensor Kernels for Mobile GPUs [(Paper)](https://dl.acm.org/doi/10.1145/3495243.3517020)
  * Smartphones; GPU
* [MobiCom 2022] NeuLens: Spatial-based Dynamic Acceleration of Convolutional Neural Networks on Edge [(Paper)](https://dl.acm.org/doi/abs/10.1145/3495243.3560528)
  * Edge devices; GPU
* [MobiCom 2021] AsyMo: Scalable and Efficient Deep-Learning Inference on Asymmetric Mobile CPUs [(Paper)](https://dl.acm.org/doi/10.1145/3447993.3448625)
  * Smartphones; CPU

**Transformer-based models**
* [MLSys 2025] MAS-Attention: Memory-Aware Stream Processing for Attention Acceleration on Resource-Constrained Edge Devices [(Paper)](https://arxiv.org/abs/2411.17720)
  * Edge devices; NPU
* [MLSys 2025] Efficient LLM Inference using Dynamic Input Pruning and Cache-Aware Masking [(Paper)](https://arxiv.org/abs/2412.01380)
  * LLM; Smartphones; NPU (Simulation)
* [ASPLOS 2025] Fast On-device LLM Inference with NPUs [(Paper)](https://dl.acm.org/doi/10.1145/3669940.3707239)
  * LLM; Smartphones; NPU
* [ASPLOS 2024] SmartMem: Layout Transformation Elimination and Adaptation for Efficient DNN Execution on Mobile [(Paper)](https://dl.acm.org/doi/10.1145/3620666.3651384)
  * Smartphones; GPU
* [MobiCom 2024] Mobile Foundation Model as Firmware [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3649361)
  * Edge devices & smartphones; CPU or GPU


### A-2. Single-DNN Inference on Heterogeneous Mobile Processors
**Application-specific tasks**
* [MobiCom 2024] Perceptual-Centric Image Super-Resolution using Heterogeneous Processors on Mobile Devices [(Paper)](https://dl.acm.org/doi/10.1145/3636534.3690698)
  * Single-image super-resolution; Smartphones; GPU + NPU
* [IPSN 2023] PointSplit: Towards On-device 3D Object Detection with Heterogeneous Low-power Accelerators [(Paper)](https://dl.acm.org/doi/abs/10.1145/3583120.3587045)
  * 3D object detection; Edge devices; GPU + NPU
* [MobiCom 2019] MobiSR: Efficient On-Device Super-Resolution through Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/10.1145/3300061.3345455)
  * Single-image super-resolution; Smartphones; CPU + GPU + DSP (NPU)

**Traditional DNNs**
* [EuroSys 2025] Flex: Fast, Accurate DNN Inference on Low-Cost Edges Using Heterogeneous Accelerator Execution [(Paper)](https://dl.acm.org/doi/10.1145/3689031.3696067)
  * Smartphones; CPU + GPU + NPU (TPU/DSP)
* [IEEE TMC 2024] Thermal-Aware Scheduling for Deep Learning on Mobile Devices with NPU [(Paper)](https://ieeexplore.ieee.org/document/10478860)
  * Smartphones; GPU + NPU 
* [ATC 2023] Decentralized Application-Level Adaptive Scheduling for Multi-Instance DNNs on Open Mobile Devices [(Paper)](https://www.usenix.org/system/files/atc23-sung.pdf)
  * Smartphones; CPU + GPU 
* [IPSN 2021] Efficient Execution of Deep Neural Networks on Mobile Devices with NPU [(Paper)](https://dl.acm.org/doi/10.1145/3412382.3458272)
  * Smartphones; CPU + NPU 

**Transformer-based vision/language models**
* [INFOCOM 2024] Galaxy: A Resource-Efficient Collaborative Edge AI System for In-situ Transformer Inference [(Paper)](https://ieeexplore.ieee.org/abstract/document/10621342)
  * Smartphones; CPU + GPU
* [arXiv 2025] HeteroLLM: Accelerating Large Language Model Inference on Mobile SoCs with Heterogeneous AI Accelerators [(Paper)](https://arxiv.org/abs/2501.14794)
  * LLM; Smartphones; CPU + GPU + NPU
* [arXiv 2024] PowerInfer-2: Fast Large Language Model Inference on a Smartphone [(Paper)](https://arxiv.org/abs/2406.06282)
  * LLM; Smartphones; CPU + NPU

### B-1. Multi-DNN Inference on Single Mobile Processors
**Application-specific tasks**
* [MobiCom 2020] Heimdall: Mobile GPU Coordination Platform for Augmented Reality Applications [(Paper)](https://dl.acm.org/doi/10.1145/3372224.3419192)
  * Augmented reality; Smartphones; GPU

**Traditional DNNs**
* [MobiSys 2024] Pantheon: Preemptible Multi-DNN Inference on Mobile Edge GPUs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3643832.3661878)
  * Edge devices; GPU
* [SenSys 2023] Miriam: Exploiting Elastic Kernels for Real-time Multi-DNN Inference on Edge GPU [(Paper)](https://dl.acm.org/doi/10.1145/3625687.3625789)
  * Edge devices; GPU
* [HPCA 2021] Layerweaver: Maximizing Resource Utilization of Neural Processing Units via Layer-Wise Scheduling [(Paper)](https://ieeexplore.ieee.org/document/9407236)
  * NPU (Simulation)
* [MobiCom 2021] LegoDNN: Block-grained Scaling of Deep Neural Networks for Mobile Vision [(Paper)](https://arxiv.org/abs/2112.09852)
  * Edge devices & smartphones; CPU or GPU

### B-2. Multiple DNN Inference on Heterogeneous Mobile Processors
**Application-specific tasks**
* [MobiSys 2025] ARIA: Optimizing Vision Foundation Model Inference on Heterogeneous Mobile Processors for Augmented Reality [(Paper)]()
  * Vision foundation model for augmented reality; Smartphones

**Traditional DNNs**
* [PPoPP 2024] Shared Memory-contention-aware Concurrent DNN Execution for Diversely Heterogeneous SoCs [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3627535.3638502)
  * Edge devices; GPU + DLA (NPU)
* [MobiSys 2023] NN-Stretch: Automatic Neural Network Branching for Parallel Inference on Heterogeneous Multi-Processors [(Paper)](https://dl.acm.org/doi/abs/10.1145/3581791.3596870)
  * Smartphones; CPU + GPU + DSP (NPU)
* [MobiSys 2022] Band: Coordinated Multi-DNN Inference on Heterogeneous Mobile Processors [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538948)
  * Smartphones; CPU + GPU + DSP + NPU
* [MobiSys 2022] CoDL: efficient CPU-GPU co-execution for deep learning inference on mobile devices [(Paper)](https://dl.acm.org/doi/pdf/10.1145/3498361.3538932)
  * Smartphones; CPU + GPU
* [SenSys 2022] BlastNet: Exploiting Duo-Blocks for Cross-Processor Real-Time DNN Inference [(Paper)](https://dl.acm.org/doi/10.1145/3560905.3568520)
  * Edge devices; CPU + GPU

### C. Single-DNN Inference on Microcontrollers
* [SenSys 2025] Lupe: Integrating the Top-down Approach with DNN Execution on Ultra-Low-Power Devices [(Paper)](https://people.cs.uchicago.edu/~myxiang/papers/lupe.pdf)
* [SenSys 2024] Intermittent Inference: Trading a 1% Accuracy Loss for a 1.9 x Throughput Speedup [(Paper)](https://dl.acm.org/doi/10.1145/3666025.3699364)
* [SenSys 2024] Fast-Inf: Ultra-Fast Embedded Intelligence on the Batteryless Edge [(Paper)](https://dl.acm.org/doi/abs/10.1145/3666025.3699335)
* [MobiSys 2023] HarvNet: Resource-Optimized Operation of Multi-Exit Deep Neural Networks on Energy Harvesting Devices [(Paper)](https://dl.acm.org/doi/10.1145/3581791.3596845)

### Challenges
* [Mobile AI Workshop](https://ai-benchmark.com/workshops/mai/2025/)
