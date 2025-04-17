# GANL_4_079 – Exploring GAN Loss Functions

This repository explores the impact of different loss functions on the training and performance of Generative Adversarial Networks (GANs). It includes implementations of multiple GAN types, experiment results, and visual comparisons.

---

## 📁 Repository Structure

```
GANL_4_079/
├── GANL_4_079.ipynb                # Main experiment notebook
├── models/                         # GAN model implementations
│   ├── standard_gan.py
│   ├── lsgan.py
│   ├── wgan.py
│   └── wgan_gp.py
├── samples/                        # Generated images, logs, plots
│   ├── generated_images/
│   ├── loss_plots/
│   └── training_logs/
├── requirements.txt                # Python dependencies
└── README.md                       # Project overview
```

---

##  Implemented GAN Variants

Each model uses a different loss function, implemented using PyTorch:

- **Standard GAN (Minimax Loss)**
- **Least Squares GAN (LS-GAN)**
- **Wasserstein GAN (WGAN)**
- **Wasserstein GAN with Gradient Penalty (WGAN-GP)**

These variations help demonstrate how loss functions influence:

- Convergence stability  
- Sample quality  
- Training dynamics

---

##  Samples & Logs

- `samples/generated_images/`: Images from different GAN variants
- `samples/loss_plots/`: Training curves of G & D losses
- `samples/training_logs/`: Logs and metrics for each model

---

##  Getting Started

### Prerequisites

- Python 3.x
- PyTorch (or TensorFlow, based on your implementation)
- NumPy, OpenCV, Matplotlib
- Jupyter Notebook

###  Installation

```bash
git clone https://github.com/your-username/GANL_4_079.git
cd GANL_4_079
pip install -r requirements.txt
```

###  Run

```bash
jupyter notebook GANL_4_079.ipynb
```

You can switch between models by modifying the code in the notebook or the `models/` folder.

---

##  Contributions

Pull requests for new GAN types or training enhancements are welcome. Please ensure any contributions are well-documented and tested.

---

##  License

This repository is available for educational and research purposes under the MIT License.

