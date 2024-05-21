# Wav-KAN
The codes to replicate the simulations of the paper :"Wav-KAN: Wavelet Kolmogorov-Arnold Networks". Here is the abstract of the paper:
In this paper, we introduce Wav-KAN, an innovative neural network architecture that leverages the Wavelet Kolmogorov-Arnold Networks (Wav-KAN) framework to enhance interpretability and performance. Traditional multilayer perceptrons (MLPs) and even recent advancements like Spl-KAN \cite{kan} face challenges related to interpretability, training speed, robustness, computational efficiency, and performance. Wav-KAN addresses these limitations by incorporating wavelet functions into the Kolmogorov-Arnold network structure, enabling the network to capture both high-frequency and low-frequency components of the input data efficiently. Wavelet-based approximations employ orthogonal or semi-orthogonal basis and also maintains a balance between accurately representing the underlying data structure and avoiding overfitting to the noise. Analogous to how water conforms to the shape of its container, Wav-KAN adapts to the data structure, resulting in enhanced accuracy, faster training speeds, and increased robustness compared to Spl-KAN and MLPs. Our results highlight the potential of Wav-KAN as a powerful tool for developing interpretable and high-performance neural networks, with applications spanning various fields. This work sets the stage for further exploration and implementation of Wav-KAN in frameworks such as PyTorch, TensorFlow, and also it makes wavelet in KAN in wide-spread usage like nowadays activation functions like ReLU, sigmoid in universal approximation theory (UAT).

Keywords: Kolmogorov-Arnold Networks (KAN), Wavelet, Wav-KAN, Neural Networks.

Currently available at:
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4835325

For now, we just added the codes to replicate MNIST train and test; we will add more to it.

