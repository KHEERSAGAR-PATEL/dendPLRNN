

# 🚀 **Stabilizing Tractable Dendritic RNNs — Hybrid Regularization (MAR + TSD + ALN)**

*A clean and reproducible implementation of dendPLRNN with hybrid regularizers.*

This repository contains a forked and extended version of the ICML 2022 **dendPLRNN** framework, enhanced with **three new stability-oriented regularizers**:

* **MAR** — Manifold-Attractor Regularization
* **TSD** — Temporal Self-Distillation
* **ALN** — Adaptive Latent Noise

The implementation is modular, safe, and fully compatible with the original dendPLRNN architecture—requiring only a **single insertion point** in the BPTT training loop.

This repo also includes fully runnable **ECG experiments**, **ablation scripts**, and **Jupyter notebooks** for training and visualization.

---

# 📦 **1. Repository Structure**

```
dendPLRNN-Hybrid/
│
├── notebooks/
│   ├── ECG_Training.ipynb     # Full training pipeline (Kaggle/Colab friendly)
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

# 🔧 **2. Requirements**

Save the following as `requirements.txt`:

```
torch>=1.13
numpy>=1.21
scipy>=1.8
scikit-learn>=1.0
matplotlib>=3.5
tqdm>=4.60
pandas>=1.3
jupyter
seaborn
```

Optional but recommended:

```
pyyaml
wandb
einops
```

---

# 🧪 **3. Installation**

### **Clone the forked repository:**

```bash
git clone https://github.com/your-username/dendPLRNN-Hybrid.git
cd dendPLRNN-Hybrid
```

### **Install dependencies:**

```bash
pip install -r requirements.txt
```

---

# ☁️ **4. Running on Kaggle or Google Colab**

Both Kaggle and Colab only need:

```python
!git clone https://github.com/your-username/dendPLRNN-Hybrid.git
%cd dendPLRNN-Hybrid
!pip install -r requirements.txt
```

Then open:

```
notebooks/ECG_Training.ipynb
```

All paths are relative and work automatically.

---

# 🧠 **5. How to Train Models (ECG Example)**

Your notebook already contains the pipeline.



# 🎯 **6. Key Features of This Repo**

✔ Fully reproducible hybrid-regularized dendPLRNN implementation
✔ Kaggle/Colab-ready notebooks
✔ Modular code with defensive checks
✔ Architecture-agnostic regularizers
✔ Clean ablation framework
✔ Capability to analyze:

* Jacobians
* Latent attractors
* Long-horizon rollouts

---

# 🙏 **Acknowledgments**

This work builds directly on:

* Brenner et al., *ICML 2022 — dendPLRNN*
* Durstewitz et al., *PLRNN theory*

Official code included under open-source license.

---

# 📬 **Questions or Issues?**

Feel free to open an issue or email:

**[kheersagar@iitbhilai.ac.in](mailto:kheersagar@iitbhilai.ac.in)**


