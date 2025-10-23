# Enhancing Anomaly Detection in IoT Systems with an Ensemble of Machine Learning Algorithms

## Introduction

**This project focuses on malicious traffic detection in IoT healthcare environments.** It utilizes machine learning models such as **Random Forest, SMOTE, Logistic Regression, Gradient Boosting Classifier, and Stacking Classifier** to enhance security.

## Datasets Used

This study employs two publicly available datasets to evaluate the proposed anomaly detection model:

### **1. IoT Healthcare Security Dataset**

A dataset simulating network traffic in an ICU environment, focusing on securing IoT patient monitoring devices. It includes:

* **patientMonitoring.csv:** Traffic data from ICU patient monitoring devices.
* **environmentMonitoring.csv:** Network activity logs from environmental sensors.

**Dataset Link:**
1. [IoT Healthcare Security Dataset (Kaggle)](https://www.kaggle.com/datasets/faisalmalik/iot-healthcare-security-dataset)

### **2. CIC-IDS-2017 / Network Intrusion Dataset**

A standard dataset for network intrusion detection, containing labeled traffic data that differentiates between normal and anomalous activities. It includes various network attacks such as:

* **FTP-Patator & SSH-Patator:** Brute-force attacks targeting FTP and SSH logins.
* **Infiltration:** Unauthorized network penetration to access sensitive data.
* **PortScan:** Scanning for open ports to identify vulnerabilities.
* **DDoS:** Overloading a server with traffic to disrupt services.

**Dataset Links:**
1. [Network Intrusion Dataset (Kaggle)](https://www.kaggle.com/datasets/chethuhn/network-intrusion-dataset)
2. [CIC-IDS2017 Dataset (Canadian Institute for Cybersecurity)](https://www.unb.ca/cic/datasets/ids-2017.html)

The model is tested on four CSV files from this dataset:

| File Name                                                      | Day      | Attack Types                     |
| -------------------------------------------------------------- | -------- | -------------------------------- |
| **Tuesday-WorkingHours.pcap_ISCX.csv**                         | Tuesday  | Benign, FTP-Patator, SSH-Patator |
| **Thursday-WorkingHours-Afternoon-Infiltration.pcap_ISCX.csv** | Thursday | Benign, Infiltration             |
| **Friday-WorkingHours-Afternoon-PortScan.pcap_ISCX.csv**       | Friday   | Benign, PortScan                 |
| **Friday-WorkingHours-Afternoon-DDoS.pcap_ISCX.csv**           | Friday   | Benign, DDoS                     |

## Objectives

1. **Develop an efficient framework** for detecting malicious activity.
2. **Enhance security** in IoT-enabled healthcare systems.
3. **Improve anomaly detection** for patient monitoring and environment tracking.

## Implementation

* **Data Preprocessing:** Handling missing values, feature scaling, and encoding categorical data.
* **Model Training:** Applying supervised and unsupervised learning techniques.
* **Evaluation Metrics:** Using accuracy, precision, recall, and F1-score.

## Conclusion

This project aims to provide a **robust security mechanism** for IoT healthcare applications by detecting malicious activities effectively.

## Contributors

Ishika Agarwal, Krishna Girish, Prarthna Puhan, Ramanathan L

## Conference Presentation

This paper was presented at the **Congress on Smart Computing Technologies (CSCT)** at **NIT Sikkim** in **December 2024**.


