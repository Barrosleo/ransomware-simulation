# Ransomware Simulation

This project simulates ransomware behavior to understand its impact and test defensive measures.

## Table of Contents
- Introduction
- Features
- Technologies Used
- Setup Instructions
- Usage


## Introduction
Ransomware is a type of malware that encrypts files and demands a ransom for their decryption. This project simulates ransomware behavior in a controlled environment to help understand its impact and test defensive measures.

## Features
- **File Encryption**: Encrypts files in a specified directory using a password.
- **File Decryption**: Decrypts previously encrypted files using the same password.
- **Simulation**: Simulates ransomware behavior in a controlled environment.

## Technologies Used
- **Python**: Programming language used for the tool.
- **Cryptography**: PyCryptodome library for encryption and decryption.
- **System Security**: Understanding of system security principles.

## Setup Instructions
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/ransomware-simulation.git
    cd ransomware-simulation
    ```

2. **Install Dependencies**:
    ```bash
    pip install cryptography
    ```

## Usage
1. **Run the Python Script**:
    ```bash
    python ransomware_simulation.py
    ```

2. **Simulate Ransomware Behavior**:
    - Choose the option to encrypt files.
    - Enter the directory to target and the password.
    - The script will encrypt and remove the files in the specified directory.

3. **Simulate Decryption**:
    - Choose the option to decrypt files.
    - Enter the directory to target and the password.
    - The script will decrypt and remove the encrypted files in the specified directory.

