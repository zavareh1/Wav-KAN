# Wav-KAN
The codes to replicate the simulations of the paper:"Wav-KAN: Wavelet Kolmogorov-Arnold Networks". 

Images

![View on X](images/wav-kan.jpg) 

Available at:
https://arxiv.org/abs/2405.12832
and also:
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4835325

For now, we just added the codes to replicate MNIST train and test; we will add more codes to this repositroy.



Here is the abstract of the paper:


In this paper, we introduce Wav-KAN, an innovative neural network architecture that leverages the Wavelet Kolmogorov-Arnold Networks (Wav-KAN) framework to enhance interpretability and performance. Traditional multilayer perceptrons (MLPs) and even recent advancements like Spl-KAN face challenges related to interpretability, training speed, robustness, computational efficiency, and performance. Wav-KAN addresses these limitations by incorporating wavelet functions into the Kolmogorov-Arnold network structure, enabling the network to capture both high-frequency and low-frequency components of the input data efficiently. Wavelet-based approximations employ orthogonal or semi-orthogonal basis and maintain a balance between accurately representing the underlying data structure and avoiding overfitting to the noise. While continuous wavelet transform (CWT) has a lot of potentials, we also employed discrete wavelet transform (DWT) for multiresolution analysis, which obviated the need for recalculation of the previous steps in finding the details. Analogous to how water conforms to the shape of its container, Wav-KAN adapts to the data structure, resulting in enhanced accuracy, faster training speeds, and increased robustness compared to Spl-KAN and MLPs. Our results highlight the potential of Wav-KAN as a powerful tool for developing interpretable and high-performance neural networks, with applications spanning various fields. This work sets the stage for further exploration and implementation of Wav-KAN in frameworks such as PyTorch and TensorFlow, aiming to make wavelets in KAN as widespread as activation functions like ReLU and sigmoid in universal approximation theory (UAT). The codes to replicate the simulations are available at this https URL.
