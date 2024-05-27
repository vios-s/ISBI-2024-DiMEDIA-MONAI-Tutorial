# ISBI-2024-DiMEDIA-MONAI-Tutorial

Welcome to the DiMEDIA tutorial repository for ISBI 2024! 

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Setup](#setup)
- [Notebooks Overview](#notebooks-overview)
  - MONAI DDPM with MedNist
  - Classifier free guidance
- [Credits](#credits)
- [License](#license)

## Introduction
In this tutorial, we will explore diffusion models using the [MONAI](https://github.com/Project-MONAI/GenerativeModels) framework. This repository contains two Jupyter Notebooks:

1. Training and Inference of Denoising Diffusion Probabilistic Models (DDPM)
2. Accelerated Sampling and Classifier-Free Guided Conditioning using Denoising Diffusion Implicit Models (DDIM + classifier-free condition)

## Requirements
To run the notebooks in this repository, you will need the following:

- Python 3.8 or above
- Jupyter Notebook
- Required Python libraries (provided in the notebook)

## Setup
Clone the repository:
```
git clone https://github.com/vios-s/ISBI-2024-DiMEDIA-MONAI-Tutorial.git
cd ISBI-2024-DiMEDIA-MONAI-Tutorial
```

Create a virtual environment:

```
python3 -m venv env
source env/bin/activate  # For Windows use `env\Scripts\activate`
``` 
Launch Jupyter Notebook:

## Notebooks Overview

### DDPM Training and Inference

Notebook: MONAI DDPM with MedNist [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vios-s/ISBI-2024-DiMEDIA-MONAI-Tutorial/blob/main/1.MONAI%20DDPM%20with%20MedNist.ipynb)

In this notebook, we cover: 
  - The basics of Denoising Diffusion Probabilistic Models (DDPM).
  - Training a DDPM on a dataset of MedNIST.
  - Performing inference using the trained model to generate new samples.

### DDIM: Accelerated Sampling and Classifier-Free Guided Conditioning

Notebook: Classifier free guidance [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/vios-s/ISBI-2024-DiMEDIA-MONAI-Tutorial/blob/main/2.Classifier_free_guidance.ipynb)


In this notebook, we will explore: 
- How to use Denoising Diffusion Implicit Models (DDIM) for faster sampling.
- Implementing classifier-free guided conditioning to improve the quality of generated samples. 
- Comparing the performance and quality of DDIM with traditional DDPM.

## Credits
This tutorial is a collaborative effort by the team at [VIOS Group](https://vios.science) and is presented at ISBI 2024. Special thanks to the MONAI development team for their extensive documentation and support.

## License
This repository is licensed under the MIT License. See the LICENSE file for more details.

We hope you find this tutorial helpful and informative. If you have any questions or feedback, please feel free to open an issue.
