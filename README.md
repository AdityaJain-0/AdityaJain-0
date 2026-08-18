<h1 align="center">Hi, I'm Aditya</h1>
<p align="center">
  ML engineer with a research focus on neurotech, building systems that turn raw EEG signal into adaptive, real-time decisions.
</p>
<p align="center">
  Currently looking for <b>Summer 2027 internships</b> in ML/AI engineering and applied research
</p>

---

### What I work on

I build the full pipeline from signal to system: filtering and decoding raw EEG, training models on top of it (from spiking neural nets to LLM-based agents), and shipping them as working software, not just notebooks.

- **Neuroadaptive AI** - real-time EEG to engagement scoring to adaptive LLM behavior
- **Energy-efficient deep learning** - benchmarking spiking neural networks against standard ANN baselines on EEG decoding
- **Applied ML systems** - RL-driven decision systems, retrieval-augmented tooling, static and learned hybrid pipelines
- **Systems and software engineering** - C++, OOP design, simulation logic

---

### Featured projects

**[Conversational-Query-with-RAG](https://github.com/AdityaJain-0/Conversational-Query-with-RAG)** - Conversational RAG system with adaptive retrieval strategy selection. Instead of fixing retrieval to one method, classifies each question by type and uses an epsilon-greedy multi-armed bandit to learn which strategy (BM25, semantic, hybrid) works best for that question type. Ranks strategies by automatic groundedness scoring plus optional human feedback. Demonstrates learned hybrid retrieval pipelines; corpus is neurotech-focused (BCI, EEG, SNNs, signal processing). Full offline-runnable stack with Anthropic API or Ollama backend, no external vector DB required.
`Python` `Flask` `BM25` `Vector Embeddings` `Multi-Armed Bandit` `RAG`

**[NeuroChat](https://github.com/AdityaJain-0/NeuroChat)** - Real-time EEG middleware that reads engagement from a Muse 2 headset and adapts an LLM tutor's teaching depth, tone, and questioning style on the fly. Full signal processing pipeline (Butterworth filtering, FFT band power, calibrated engagement scoring) sitting behind a Flask proxy between Open WebUI and Ollama, containerized with Docker. Implements the approach from Baradari et al. (2025).
`Python` `Flask` `Docker` `Ollama` `Signal Processing`

**[SNN Energy-Efficiency Benchmarking](https://github.com/AdityaJain-0/SNN-Energy-Efficiency-Benchmarking)** - Benchmarks ATCNet, EEGNet, and ShallowConvNet against hybrid and fully spiking neural networks on 3-class EEG motor imagery (BNCI2014_001), comparing accuracy, F1, and estimated inference energy side by side. Rigorous evaluation across within-subject and leave-one-subject-out cross-validation.
`PyTorch` `SpikingJelly` `MOABB` `MNE`

**[Temporal Anomaly Detection with Adaptive Thresholding](https://github.com/AdityaJain-0/Temporal-Anomaly-Detection-CPU-Utilization)** - A TCN-based anomaly detector for server metrics (AWS CloudWatch CPU utilization, NAB benchmark) paired with a multi-armed bandit that learns the alerting threshold instead of using a fixed one. Includes a simulated alert-fatigue scenario where false-positive cost shifts mid-deployment, showing the adaptive bandit reconverging while a static threshold keeps losing reward.
`Python` `PyTorch` `Multi-Armed Bandit` `Time Series` `FastAPI`

**[Code Review Agent](https://github.com/AdityaJain-0/AI-Repo-Reviewer-and-Optimizer-)** - A GitHub Action that reviews PRs for N+1 queries, circular imports, and missing caching using deterministic static analysis, then explains and fixes each finding using examples retrieved from the repo's own PR history. Learns from comment feedback to suppress rejected suggestions and reinforce accepted ones.
`Python` `AST Analysis` `RAG` `Claude API` `GitHub Actions`

**[SimCity](https://github.com/AdityaJain-0/SimCity)** - A C++ simulation of city growth across industrial, residential, and commercial sectors, driven by configurable CSV layouts and custom growth/pollution rules. Started as a class project; I took it on independently afterward and have continued developing it solo.
`C++` `OOP` `Simulation`

---

### Skills

`Python` · `C++` · `NumPy` · `PyTorch` · `scikit-learn` · `Flask` · `Docker` · `MNE / EEG signal processing` · `Spiking Neural Networks`

---

<p align="center">
  Reach me at <i>hi2aditya@outlook.com</i> · <a href="https://www.linkedin.com/in/YOUR_LINKEDIN_HERE">hi2aditya</a>
</p>
