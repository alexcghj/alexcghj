<h1 align="center">Aleksandr Kuleshov</h1>

<p align="center">
  CS student at Peter the Great St. Petersburg Polytechnic University ·
  Python & ML · AI security research
</p>

<p align="center">
  <a href="https://orcid.org/0009-0001-7197-8001">
    <img src="https://img.shields.io/badge/ORCID-0009--0001--7197--8001-A6CE39?logo=orcid&logoColor=white" alt="ORCID">
  </a>
</p>

---

I build things at two ends of the stack: low-level systems and algorithms in
**C**, and machine learning and LLM tooling in **Python**. Lately my focus has
been the **security of small language-model agents** — how they break, how to
measure it honestly, and how to defend them.

### What I work on

- **AI / LLM security.** Independent research on how quantization, model size,
  architecture, and attack style affect the vulnerability of small LLM agents
  to indirect prompt injection — 14 model configurations, 14k+ rollouts, real
  statistics, cross-checked on an external benchmark.
- **Machine learning.** Sequence models and prediction — e.g. LSTM-based
  trajectory forecasting on GPS data.
- **Systems & algorithms in C.** Data structures, text processing, and
  cryptography built from the ground up (AVL trees, GOST ciphers, custom
  sorting, RPN evaluation).

### Selected projects

| Project | What it is | Stack |
|---|---|---|
| **qllm-agent-security** | Systematic study of prompt-injection vulnerability in small LLM agents; full harness, 4-outcome scorer, statistics, paper | Python, Ollama |
| **geolife-lstm-prediction** | LSTM model for predicting GPS movement trajectories | Python, PyTorch |
| **password-manager (Magma & Kuznyechik)** | Password manager built on the Russian GOST block ciphers | C |
| **book-catalog (AVL tree)** | Book catalog backed by a self-balancing AVL tree | C |
| **large-volume-text-processing** | Efficient processing of large text volumes | C |
| **RPN calculator** | Expression calculator via reverse Polish notation | C |

### Tech

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)

### A bit more

- Interested in the intersection of **ML and security** — adversarial
  robustness, model compression, and the failure modes of LLM-based systems.
- Prior work includes an analysis of the Sponge Attack on ResNet-18
  (ICNK Science Week, 2025).
- Comfortable going deep: from bit-level cipher implementations in C to
  statistical evaluation of language models in Python.

