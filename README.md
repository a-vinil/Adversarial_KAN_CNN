# Adversarial Experiments on Convolutional Kolmogorov Arnold Networks

## Project Summary  
This project evaluates the robustness of Convolutional Kolmogorov-Arnold Networks (KAN-CNNs) against adversarial attacks using the Fast Gradient Sign Method (FGSM). Performance is analyzed across varying spline orders and grid sizes, key parameters in KAN’s function approximation. Results on MNIST Handwritten Digits dataset show that KAN-CNNs, despite their novel structure, remain vulnerable to adversarial perturbations, with adversarial training offering limited improvement. The findings underscore the need for advanced defenses to enhance KAN-CNN robustness.

---

## Contents  
The repository contains the following Jupyter notebooks:  
1. **`mnist_Adversarial_image_generator_FGSM.ipynb`**: Generates adversarial MNIST images using the FGSM technique.
2. **`mnist_normal_CNN_KAN.ipynb`**: Implements a standard KAN-CNN model trained and tested on normal MNIST images.
3. **`mnist_manip_CNN_KAN.ipynb`**: Simulates a KAN-CNN model trained on normal MNIST images and tested on adversarial images generated through FGSM.
4. **`mnist_secure_CNN_KAN.ipynb`**: Implements a secure KAN-CNN model trained and tested on combined normal and adversarial MNIST images.  


---

## Usage  
To run the notebooks:  
1. Clone this repository:  
   ```bash
   git clone https://github.com/a-vinil/Adversarial_KAN_CNN.git
   cd Adversarial_KAN_CNN

