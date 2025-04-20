
This project uses a CycleGAN model to transform urban photos taken during the day into realistic nighttime versions — without needing paired training images.

Project Overview
The model was trained using the "Unpaired Day and Night City View" dataset from Kaggle.

It includes:

-Two Generators (Day→Night and Night→Day)

-Two Discriminators (for each domain)

-The goal is to preserve the structure of the image while changing its lighting and atmosphere.

Technologies Used
-TensorFlow (model building & training)

-Google Colab (training environment)

-Anvil (web app interface)

-Python (data preprocessing and model logic)

Features
-Image preprocessing: resizing, normalization, clipping, augmentation

-Trained with 35 epochs and fine-tuned hyperparameters (dropout, learning rate, lambda, etc.)

-Real-time image translation via an interactive web interface built with Anvil
