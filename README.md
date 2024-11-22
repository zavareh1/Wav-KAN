# Wav-KAN
The codes to replicate the simulations of the paper:"Wav-KAN: Wavelet Kolmogorov-Arnold Networks". 


![View on X](Images/wav-kan.jpg) 

Available at:
https://arxiv.org/abs/2405.12832
and also:
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4835325

# Wav-KAN: Wavelet Kolmogorov-Arnold Networks

## Links to the Paper
- Available at: [arXiv](https://arxiv.org/abs/2405.12832)
- Also available at: [SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4835325)

## Current Contents
- **MNIST Training and Testing**:
  - The repository currently contains the codes required to replicate MNIST training and testing.
  - More codes and examples will be added in future updates.

## Abstract
In this paper, we introduce **Wav-KAN**, an innovative neural network architecture that leverages the **Wavelet Kolmogorov-Arnold Networks (Wav-KAN)** framework to enhance interpretability and performance.

Traditional multilayer perceptrons (MLPs) and even recent advancements like Spl-KAN face challenges such as:
- Interpretability
- Training speed
- Robustness
- Computational efficiency
- Performance limitations

### Wav-KAN addresses these issues by:
- Incorporating **wavelet functions** into the Kolmogorov-Arnold network structure.
- Efficiently capturing both **high-frequency** and **low-frequency components** of input data.
- Using **discrete wavelet transforms (DWT)** for multiresolution analysis, eliminating the need for recalculations in detail extraction.

### Key Features:
- Wavelet-based approximations employ **orthogonal or semi-orthogonal bases**, balancing data structure representation and noise reduction.
- Enhanced accuracy, faster training speeds, and increased robustness compared to Spl-KAN and MLPs.
- Adaptability to the data structure, akin to how water conforms to its container.

Our results highlight the potential of Wav-KAN as a **powerful tool** for developing interpretable and high-performance neural networks, with applications across various fields. This work paves the way for further exploration and implementation of Wav-KAN in frameworks such as **PyTorch** and **TensorFlow**, aspiring to make wavelets in KAN as common as activation functions like **ReLU** and **sigmoid** in universal approximation theory (UAT).

## Future Updates
- Additional code implementations and simulations for Wav-KAN.
- Integration with **PyTorch** and **TensorFlow** for ease of use in modern neural network frameworks.

---

Stay tuned for updates! Feedback and contributions are welcome. 🚀

