
# Overview
This project presents a robust solution for the detection of trojan viruses and anomaly trojan threats in power system networks. The approach combines Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) models for trojan detection and employs a Generative Adversarial Network (GAN) for identifying anomaly trojan threats. The resulting model is both highly accurate and lightweight, making it well-suited for real-world applications in the field of power system security.

This project was originally developed as part of the Smart India Hackathon event, organized by the Government of India, in response to the increasing vulnerability of automated power system networks to malicious attacks. With the growing dependence on software for various purposes, including SCADA, Head End System, Meter Data Management System, Billing System, and more, securing these systems against trojans and other threats is paramount.

# Problem Statement
The power system networks are becoming increasingly automated, and various software components are utilized for critical functions. These software systems are often deployed in demilitarized zones, making it challenging to perform regular patch updates and penetration tests. This leaves these systems vulnerable to attacks by hackers who exploit various vectors. The primary challenge addressed in this project is the validation of the presence of malicious code in these software systems, which could potentially be used in specific attacks, including zero-day exploits.

# Key Features
Hybrid Model: Our approach combines the strengths of CNN and LSTM models to detect trojan viruses effectively. CNNs are employed for feature extraction, while LSTMs capture sequential dependencies in the data.

GAN for Anomaly Detection: We use a Generative Adversarial Network (GAN) to identify anomaly trojan threats that may not fit the typical trojan patterns.

High Accuracy: The model exhibits exceptional accuracy in detecting trojan viruses and anomaly threats, reducing false positives and negatives.

Lightweight Design: The model is optimized to be lightweight, ensuring it can be deployed efficiently in power system networks with minimal computational resources.