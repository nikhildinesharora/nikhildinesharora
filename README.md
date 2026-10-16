# Hi, I'm Nikhil Arora

I build software and machine-learning systems that are measurable, debuggable, and useful beyond a demo.

I recently completed an M.S. in Computer Engineering at NYU. My work spans distributed training, GPU performance, retrieval and evaluation, backend/data workflows, and embedded systems. I am currently looking for early-career software engineering, ML systems, applied AI, and data infrastructure roles.

## Selected work

| Project | What I built | Evidence |
| --- | --- | --- |
| [Distributed ML Training](https://github.com/nikhildinesharora/Distributed_AI_Training) | Cross-platform leader/worker training with registration, heartbeats, reconnection, benchmark-weighted sharding, and synchronized PyTorch Distributed execution. | macOS and Windows workers; federated and distributed modes |
| [GPU-Efficient BERT Fine-Tuning](https://github.com/nikhildinesharora/BERT-FineTuning-SQuAD-CUDA) | Controlled SQuAD v2 experiments across SDPA, `torch.compile`, dynamic padding, LoRA, BitFit, layer freezing, 8-bit AdamW, and checkpointing. | Throughput: **43.9 to 51.6 samples/s**; dev F1: **76.6 to 77.2**; peak VRAM: **up to 32% lower** |
| [Net-RAG](https://github.com/nikhildinesharora/Net-RAG) | Open-set intrusion detection with calibrated classifiers, Chroma retrieval, reranking, and evidence-grounded local LLM explanations. | Held-out-family recall: **1.6% to 68.8%**, with the false-unknown tradeoff reported |
| [Egocentric World Memory](https://github.com/nikhildinesharora/Egocentric-World-Memory) | Pose-aligned OpenCLIP memory over real and NeRF-rendered views for language-based spatial retrieval. | Doorway-query concentration at K=5: **0.106 real vs. 0.357 random baseline** |
| [RV32I Processor Simulator](https://github.com/nikhildinesharora/Risc-V-Simulator) | Single-stage and five-stage processor simulation with forwarding, hazard handling, cycle traces, and CPI/IPC reporting. | Reproducible sample programs and reference outputs |
| [Embedded Sentry](https://github.com/nikhildinesharora/Embedded-Sentry) | Gesture-based access control on an STM32F429I using gyroscope input, a touchscreen interface, multithreaded sensor handling, and LED feedback. | Mbed/PlatformIO implementation and hardware demo |

## Tools I use

- **Languages:** Python, SQL, Java, C/C++, Bash
- **ML and systems:** PyTorch, PyTorch Distributed, CUDA, Hugging Face, scikit-learn, Spark
- **Backend and data:** FastAPI, Flask, PostgreSQL, pandas, NumPy, REST APIs
- **Infrastructure:** Git, Docker, Linux, AWS fundamentals, Tailscale

## How I work

I like experiments with explicit baselines, failure checks, and honest tradeoffs. That means keeping negative results when they teach something, validating model gains against leakage, and treating reliability and observability as part of the system rather than cleanup work.

Based in New York and open to relocation. Connect with me on [LinkedIn](https://www.linkedin.com/in/nikhildinesharora).
