# Tutorial: from Backpropagation to Predictive Coding

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cgoemaere/Predictive_Coding_tutorial_ipynb/blob/main/PC_intro_student.ipynb)

A hands-on notebook that takes you from a standard MLP trained with backpropagation to Predictive Coding (PC), a local, energy-based learning algorithm. Implemented from scratch in PyTorch.

## What you'll learn

- **How `.backward()` works internally**: write it by hand and compare against autograd
- **The problems with backprop** that make it a bad fit for efficient analog hardware
- **What Predictive Coding is**: learn about states, predictions, errors, energy functions, and the two-phase learning loop.
- **Implement PC in PyTorch**, and train an MLP on a small classification task (two-moons)
- Find out for yourself **why PC is great for analog hardware**

## How to use it

- The boilerplate code (dataset loading, model definition, plotting) is already in place. **Your only task: implementing the training algorithm**
- **Code it yourself**: exercises are marked `# === EXERCISE ===` and each comes with an auto-checked test.
- **Think** questions have hidden hints and answers.
- **Run it**: click the **[Open In Colab](https://colab.research.google.com/github/cgoemaere/Predictive_Coding_tutorial_ipynb/blob/main/PC_intro_student.ipynb)** badge above (or open `PC_intro_student.ipynb` locally). Everything runs on CPU in a few minutes.

---

*A companion notebook to a Master's thesis on physics-based hardware for Predictive Coding.*
