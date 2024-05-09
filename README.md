# ConvLSTM-Cloud-Prediction

## Table of Contents

1. [About](#about)
2. [Features](#features)
3. [Installation](#installation)
4. [License](#license)
5. [Sources](#sources)

## About

ConvLSTM-Cloud-Prediction is a project aimed at predicting cloud movements using Convolutional Long Short-Term Memory (ConvLSTM) networks. It was developed as part of a bachelor's thesis focusing on cloud forecasting from radar data using neural networks.

## Features

- Utilizes ConvLSTM architecture for cloud movement prediction.
- Training and evaluation conducted using PyTorch.
- Pretrained models available in the `Models` directory.
- Output files in MP4 format located in the `Output_files` directory.
- Commented code provided in `convlstm.ipynb`.
- Bachelor thesis titled "Cloud Forecasting from Radar Data Using Neural Networks" is available in PDF format as `bakalarka.pdf`.
- Hardware used for training: 
  - Processor: AMD EPYC 7543P
  - RAM: 512 GB
  - GPUs: 2x NVIDIA A100 with 40 GB memory

## Installation

To install the project, follow these steps:

1. Clone the repository.
2. Navigate to the project directory.
3. Install dependencies using `pip install -r requirements.txt`.


## License

This project is licensed under the [MIT License](LICENSE).

## Sources

The architecture source code was inspired by [Video Frame Prediction using ConvLSTM Network in PyTorch](https://sladewinter.medium.com/video-frame-prediction-using-convlstm-network-in-pytorch-b5210a6ce582).
