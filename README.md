# NeurIPS 2023 Machine Unlearning Challenge

Welcome to our solution for the NeurIPS 2023 Machine Unlearning Challenge. In this project, we present an unlearning approach based on fine-tuning a deep neural network to forget specific knowledge while retaining the rest. We utilize a dataset containing images of individuals grouped into age categories.

## Table of Contents
- [Introduction](#introduction)
- [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Unlearning Process](#unlearning-process)
- [Evaluation](#evaluation)
- [Results](#results)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Introduction

The NeurIPS 2023 Machine Unlearning Challenge tasks participants with developing an unlearning strategy for a deep learning model. Unlearning is the process of making a model forget specific knowledge or information it has learned previously. Our solution focuses on forgetting information related to the age of individuals in the dataset.

## Requirements

To run this project, you will need the following requirements and dependencies:

- Python (>=3.6)
- PyTorch
- torchvision
- Pandas
- torch
- torch.utils.data
- CUDA-compatible GPU (recommended)
- Kaggle environment (if using for the challenge)

## Getting Started

To get started with our project, follow these steps:

1. Install the required dependencies using `pip install -r requirements.txt`.
2. Set up your environment with a CUDA-compatible GPU for faster training (recommended).
3. Download the dataset provided for the challenge.

## Unlearning Process

Our unlearning approach involves fine-tuning a deep neural network using a Retain and Forget mechanism. This mechanism allows the model to retain knowledge that is relevant while forgetting specific aspects, such as age-related information.

We use a dataset containing images of individuals categorized by age groups. The process includes loading the original model, fine-tuning it on the retained knowledge, and creating multiple checkpoints to represent different stages of unlearning.

## Evaluation

The effectiveness of our unlearning process is evaluated based on the performance of the model. We assess the model's accuracy and loss during the unlearning process. The goal is to minimize the impact of age-related knowledge while preserving the model's overall performance.

## Results

Our results demonstrate the feasibility of the unlearning approach. By comparing the model's performance before and after unlearning, we showcase the successful reduction in the model's reliance on age-related features.

## License

This project is released under the MIT License. Feel free to use, modify, or distribute it according to the terms of the license.

## Acknowledgments

We would like to thank the NeurIPS 2023 Machine Unlearning Challenge organizers for creating this stimulating competition and providing the dataset for our research.
# Machine-Unlearning
