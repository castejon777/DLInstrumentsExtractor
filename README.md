# Instrument Track Extractor  
🎵 🎶 🎸 🎤 🪘

## Description
The **Instrument Track Extractor** is a Python-based IPython Notebook program designed for extracting instrument-specific audio tracks from the MUSDB dataset. It leverages deep learning architectures (with *PyTorch*), including Variational Autoencoder (VAE) and U-Net, for the purpose of instrument track separation.

This notebook provides step-by-step guidance on how to:

1. Gather audio data from the MUSDB dataset. Here a reduced set is used to simplify process and make training faster (leading to worse results).
2. Preprocess of the original audio data, converting each file into spectrogram as they are easier to deal with and provide better results.
3. Train a Variational Autoencoder (VAE) model for instrument track extraction.
4. Train a U-Net model for instrument track extraction.
5. Use the trained models to extract instrument tracks from audio files.

The program is intended for researchers, music enthusiasts, or anyone interested in isolating specific instrument tracks from mixed audio recordings.

## Usage

The notebook is designed to be interactive and easy to follow, making it accessible to users with varying levels of experience in Python and deep learning. You can run it on Google Colab.

