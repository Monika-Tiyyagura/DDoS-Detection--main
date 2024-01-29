# DDoS Detection using Machine Learning Models

## Overview

This project focuses on developing a real-time DDoS (Distributed Denial of Service) attack detection system using machine learning models. The goal is to enhance network security by leveraging machine learning algorithms for accurate detection and monitoring of abnormal traffic spikes.

## Features

- Real-time monitoring of network traffic.
- Detection of anomalous patterns associated with DDoS attacks.
- Utilization of machine learning models for accurate prediction.
- Integration with existing network security infrastructure.

## Technologies Used

- Programming Language: C++
- Machine Learning Libraries: scikit-learn, TensorFlow, PyTorch
- Networking Libraries: libpcap, WinPcap
- Other Tools: CMake, Git

## Project Structure

- **src/:** Contains the source code files.
- **models/:** Stores trained machine learning models.
- **data/:** Includes datasets for training and testing.
- **docs/:** Documentation files, including this README.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Monika-Tiyyagura/ddos-detection.git
   cd ddos-detection
2. **Build and Run:**
   ```bash
   cmake . && make && ./ddos_detection
3. **Configuration:**
4. **Training:**
   Prepare Data:
Place training dataset in `data/`
5. **Train Model:**
   ```bash
   python train_model.py
6. **Save Model:**
Model saved in `models/`

