# 🧠 Micrograd (Rebuilt from Scratch)

This repo is a pure Python implementation of **Andrej Karpathy's Micrograd** — a tiny scalar-valued autograd engine and neural network built from scratch using only fundamental Python.

> 📹 Inspired by: [The spelled-out intro to neural networks and backpropagation](https://youtu.be/VMj-3S1tku0) by Andrej Karpathy

---

## 📚 Project Overview

Over 5 Jupyter notebooks, this project carefully recreates the building blocks of neural networks and automatic differentiation, eventually training a mini MLP model from scratch.

All components are explained, implemented, and visualized step-by-step to aid deep understanding.

---

## 🔁 File Breakdown

### ✅ `karpathy 001.ipynb` - Building the Engine
- Built the `Value` class from scratch.
- Implemented operator overloading: `+`, `*`, etc.
- Introduced the computational graph using Graphviz.
- Demonstrated a simple example of forward pass and manual gradient computation.

### ✅ `karpathy 002.ipynb` - Backprop from Scratch
- Implemented `.backward()` method for automatic differentiation.
- Explained backpropagation deeply using a simple computation graph.
- Walked through how gradients are calculated and flow backwards.

### ✅ `karpathy 003.ipynb` - Neuron by Neuron
- Defined a `Neuron` using the `Value` class.
- Implemented `tanh` activation function manually.
- Performed a manual forward + backward pass on a neuron.
- Encapsulated neuron logic for reuse.

### ✅ `karpathy 004.ipynb` - Math Extensions
- Added support for more operators: `-`, `/`, `**`, exponentiation.
- Reimplemented `tanh` using only basic math.
- Made the `Value` class behave like numbers for intuitive math chaining.

### ✅ `karpathy 005.ipynb` - Training a Neural Net
- Built:
  - `Neuron`
  - `Layer`
  - `MLP` (Multi-Layer Perceptron)
- Trained the MLP on a small dataset using manual gradient descent.
- All forward and backward passes handled via our own `Value` engine.
- Simulated PyTorch-style training loop using only NumPy + Python.

---

## 💡 Key Concepts

| Concept               | Covered ✅ |
|-----------------------|-----------|
| Forward Propagation   | ✅         |
| Backward Propagation  | ✅         |
| Autograd Engine       | ✅         |
| Activation Functions  | ✅ (tanh)  |
| Custom MLP Structure  | ✅         |
| Manual Loss + Updates | ✅         |

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/micrograd-clone.git
cd micrograd-clone
```

2. Open any `.ipynb` file in Jupyter or VSCode.
3. Run the cells in order to see the magic happen ✨

---

## 🙏 Credits

- 📺 [Andrej Karpathy](https://www.youtube.com/@karpathy)
- 🔗 [Original Micrograd Repo](https://github.com/karpathy/micrograd)
- 💻 Rebuilt step-by-step by **Taha Dahodwala**

> 🧠 “Understanding comes from building.” — This repo reflects that.

---

## 📅 Completed: June 25, 2025

