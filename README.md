# Diffusion-models-2dim
🦕 DDPM on 2D Dino Dataset

This repository contains a from-scratch implementation of a Denoising Diffusion Probabilistic Model (DDPM) trained on a 2D “Dino” dataset. The project demonstrates the core principles of diffusion models without using any diffusion libraries.

📌 Overview

The model learns to generate synthetic 2D points that match the distribution of the original dino-shaped dataset. The implementation focuses on clarity and fundamental understanding of diffusion-based generative modeling.

🧠 Approach

Visualized the original 2D dataset to understand the target distribution

Normalized data for stable diffusion behavior

Implemented forward diffusion with a custom noise schedule

Trained a neural network to predict added noise using MSE loss

Performed reverse diffusion to generate 1000 new samples

Overlaid generated samples with real data for evaluation

⭐ Bonus

Includes a conceptual explanation of score-based diffusion, highlighting its equivalence to DDPM noise prediction and providing a broader perspective on diffusion models.

🛠️ Tools Used

Python, PyTorch

NumPy, Matplotlib

Google Colab
