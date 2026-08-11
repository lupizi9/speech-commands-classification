# Speech Commands Classification

Deep learning project focused on exploring different audio representations and neural network architectures for automatic recognition of short spoken commands.

## Overview

This project explores and compares different strategies for representing and modeling short speech commands using **artificial neural networks**.

The project uses Google's **Speech Commands** dataset, which contains thousands of recordings of spoken words from different speakers. The task focuses on recognizing ten basic English commands:

`yes`, `no`, `up`, `down`, `left`, `right`, `on`, `off`, `stop`, `go`.

The main objective is to analyze how different design decisions, such as the representation of the audio signal, neural network architecture, activation function, and optimization method, affect the model's ability to learn and generalize.

Two different input representations are explored: **raw WAV waveforms**, which directly represent the audio signal over time, and **log-Mel spectrograms**, which represent the energy of the signal across frequencies using a scale that is more relevant to human auditory perception.

The project implements and evaluates **Multilayer Perceptrons (MLP)** and **Convolutional Neural Networks (CNN)** using **PyTorch**. Experiments are tracked with **Weights & Biases (W&B)**, enabling systematic comparison of different training configurations based on validation accuracy and loss.

The final objective is to identify configurations that provide a balance between computational efficiency, training stability, and generalization, while gaining a deeper understanding of how different representations and architectures affect speech recognition performance.

## Academic Context

This project was developed as part of **TD6 – Artificial Intelligence** at Universidad Torcuato Di Tella.
