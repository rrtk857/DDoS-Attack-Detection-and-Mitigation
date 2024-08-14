# DDoS Attack Detection and Mitigation

## Project Overview

This project is designed to detect Distributed Denial of Service (DDoS) attacks within the same network interface. It monitors network traffic in real-time to identify and respond to suspicious activities originating from various IP addresses connected to the network. By leveraging advanced machine learning techniques, the system ensures proactive protection against potential DDoS attacks, safeguarding the integrity and availability of network resources.

## Project Phases

### Learning
Explored various machine learning algorithms to understand their potential application in anomaly detection.

### Research
- **Research Papers**: Thoroughly read research papers on DDoS attacks and network security.
- **Understanding Attacks**: Studied DoS and DDoS attacks in depth and learned how to simulate these attacks for testing purposes.

### Dataset
- **Database Preparation**: Prepared our original dataset files by sniffing network packets to collect real-time data.

### Detection
Implemented detection mechanisms using K-Means clustering and Random Forest classification to identify potential DDoS attacks.

### Mitigation
Developed a system to block IP addresses identified as sources of DDoS attacks to stop ongoing attacks.

## Algorithms Used

- **K-Means Clustering**: Used for unsupervised anomaly detection.
- **Random Forest**: Used for classification and detecting anomalies.
- **Isolation Forest**: Used for identifying outliers in the data.
- **Support Vector Machines (SVM)**: Used for binary classification tasks.
