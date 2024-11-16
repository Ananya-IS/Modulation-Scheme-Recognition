# **Modulation Scheme Recognition**

This project leverages deep learning, specifically Convolutional Neural Networks (CNNs), to automatically recognize modulation schemes in wireless communication systems. It is designed to enhance spectrum efficiency and enable intelligent communication in real-world applications like cognitive radio networks.

---

## **Features**
- **Automatic Modulation Recognition (AMR):** Classifies analog and digital modulation schemes, including AM-DSB, BPSK, QPSK, QAM16, and more.
- **Deep Learning Models:** Utilizes CNN-based architectures for robust classification.
- **Noise Robustness:** Performs well under varying Signal-to-Noise Ratios (SNRs).
- **Real-World Dataset:** Trained on the RadioML dataset for diverse modulation schemes.

---

## **Project Structure**
Modulation-Scheme-Recognition/ ├── dataset/ # Dataset or data download instructions ├── models/ # Saved trained model files ├── scripts/ # Python scripts for training and evaluation │  # Model.py # Script to evaluate the trained model │ └── preprocess_data.py# Script to preprocess signal data ├── results/ # Plots, confusion matrices, and analysis outputs ├── README.md # Project documentation ├── requirements.txt # List of Python dependencies └── .gitignore # Files to ignore in the repository


---

Evaluate the Model to generate accuracy metrics and confusion matrices:

bash
Copy code
python scripts/Model.py

## Dataset
You can Find it Here- https://www.deepsig.ai/datasets/

## Results
Accuracy: Achieved X% accuracy on the RadioML dataset across various SNR levels.
Confusion Matrix: Demonstrates classification performance across modulation schemes.

Results:
Supported Modulation Types
Analog: AM-DSB, AM-SSB, WBFM
Digital: BPSK, QPSK, 8PSK, 16QAM, 64QAM, CPFSK, GFSK, PAM4
Future Improvements
Integrate hybrid architectures like CNN + RNN for improved temporal feature learning.
Optimize model performance for deployment on edge devices.
Extend the dataset to include more real-world conditions.


### Acknowledgments
Special thanks to the creators of the RadioML dataset.

### Contributing
Contributions are welcome! Please submit any issues or pull requests to help improve this project.
