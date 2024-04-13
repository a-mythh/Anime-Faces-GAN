# Anime Face Generation using Generative Adversarial Networks (GAN)

## Overview
This repository contains a Generative Adversarial Network (GAN) implemented in TensorFlow for generating anime faces. The model is trained on a dataset containing over 23,000 anime faces.

## Model Architecture
### Generator
- **Parameters:** The Generator consists of over 6 million parameters.
- **Layers:** It comprises three 2D convolutional transpose layers followed by a final convolutional layer to generate the images.

### Discriminator
- **Parameters:** The Discriminator is a normal classification model with around 400,000 parameters.
- **Layers:** It consists of three convolutional layers.

## Training Details
- **Epochs:** The model was trained for 50 epochs.
- **Loss Function:** The GAN framework employs adversarial loss, with the Generator aiming to fool the Discriminator, while the Discriminator aims to distinguish real from fake images.

## Acknowledgements
This project draws inspiration from Anusha Ihalapathirana's project on anime face generation. Their project provided valuable insights that contributed to the development of this GAN model.

## Results
After training for 50 epochs, the model produced satisfactory results in generating anime faces. While not perfect, the generated images exhibit characteristics similar to those found in the training dataset.

## Dataset
The dataset used for training this model is sourced from the [Anime Face Dataset](https://www.kaggle.com/datasets/splcher/animefacedataset), containing over 63,000 anime faces but around 23,000 were used for this project.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes, subject to the terms and conditions of the license.
