# ✍️ Handwriting OCR with CRNN

This project is a Handwriting Recognition System that uses a deep learning model called **CRNN (Convolutional Recurrent Neural Network)** to read handwritten text from images.

It was developed as a graduation project at **Egyptian E-Learning University (EELU)**.

---

## 💡 What It Does

- Recognizes handwritten words in scanned images
- Uses a trained deep learning model with CNN, LSTM, and CTC loss
- Includes a desktop GUI app (built with Tkinter) to upload images and view predictions
- Allows exporting predicted text to file or clipboard

---

## 📁 Main Files

- `ocr_train.py` – trains the CRNN model using the IAM dataset
- `gui.py` – simple app to use the model for predictions
- `Models/` – contains the trained TorchScript model

---

## 🛠 Requirements

- Python 3.9+
- PyTorch
- torchvision
- datasets
- Pillow
- tkinter

Install them using:

```bash
pip install torch torchvision datasets pillow
