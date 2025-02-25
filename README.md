# 🔍 Autoencoder and Variational Autoencoder Experiments

This repository contains implementations of autoencoder architectures, including vanilla autoencoders, variational autoencoders (VAEs), and β-VAEs. The models are applied primarily to the MNIST dataset for unsupervised learning and image reconstruction tasks.

## 🚀 Project Structure

The following Jupyter notebooks highlight different architectures and training approaches:

1. **`autoencoder.ipynb`**  
   - Implements a simple autoencoder to compress and reconstruct MNIST images.  
   - Trained using PyTorch with visualization of reconstructed outputs.

2. **`VAEMNIST.ipynb`**  
   - Builds a Variational Autoencoder (VAE) for MNIST digit reconstruction.  
   - Includes KL divergence loss and visualizes latent space representations.

3. **`autoencodermnist.ipynb`**  
   - Similar to `autoencoder.ipynb`, with a focus on efficient training and GPU utilization.

4. **`betaVAE.ipynb`**  
   - Implements β-VAE, a variation of VAE that controls the trade-off between reconstruction and latent disentanglement using the β parameter.

5. **`unet.ipynb`**  
   - A U-Net architecture, typically used for image segmentation but adapted for reconstruction tasks.

## ⚙️ Installation

Ensure you have Python and the required packages installed.  
Create a virtual environment (optional but recommended):

# Create and activate virtual environment
python -m venv autoencoder-env
source autoencoder-env/bin/activate  # On Windows: autoencoder-env\Scripts\activate

# Install dependencies
pip install torch torchvision matplotlib jupyter

## 📊 Usage

To run the notebooks:

1. Clone the repository:  
git clone https://github.com/yourusername/autoencoder.git
cd autoencoder

2. Launch Jupyter Notebook:  
jupyter notebook

3. Open any `.ipynb` file and run the cells.

<!--## 🎨 Results

Sample reconstructed images from the autoencoder:

| Original | Reconstructed |
|---------|----------------|
| ![original](assets/original.png) | ![reconstructed](assets/reconstructed.png) |
-->
## 🛠️ Features

- Vanilla Autoencoder and VAE  
- β-VAE with configurable β parameter  
- GPU training for faster processing  
- Visualization of latent space and reconstructed images  

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, submit issues, or suggest improvements.

## 📜 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

💡 *Built with PyTorch and Jupyter Notebooks.*

