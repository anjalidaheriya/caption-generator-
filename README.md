# 🖼️ Image Caption Generator

This project implements an **Image Caption Generator** using deep learning. It combines **Convolutional Neural Networks (CNNs)** for image feature extraction and **Recurrent Neural Networks (RNNs)**, specifically LSTM, for generating textual descriptions of images.

> 🚀 Try it directly on [Google Colab](https://colab.research.google.com/drive/1niJhd97ljdab_7N23KNdkzgNG7ku0iW_?usp=sharing)

---

## 📌 Project Description

The goal of this project is to automatically generate captions for input images. It follows the encoder-decoder architecture:

- **Encoder**: A pretrained CNN (like InceptionV3 or VGG16) is used to extract features from images.
- **Decoder**: An LSTM-based RNN is used to generate sequences of words based on the extracted image features and trained text data.
- **Tokenizer & Preprocessing**: The dataset captions are cleaned, tokenized, and converted to sequences.
- **Training**: The model is trained on paired image-caption datasets to learn how to generate natural-language descriptions.

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- CNN (e.g., InceptionV3)
- LSTM
- NumPy / Matplotlib / PIL
- Google Colab

---

## 🧠 Model Output Examples

- 🖼️ _Image of a dog running_ → "a dog is running on the grass"
- 🖼️ _Image of a man riding a bike_ → "a man riding a bike on a street"

> The generated captions are probabilistic and may vary depending on the model’s training and sampling method.

---

## 📌 Future Work

- Improve vocabulary size and training epochs
- Fine-tune CNN backbone on the dataset
- Experiment with attention mechanisms
- Deploy as a web or mobile application

---

## 🔗 Colab Notebook

You can view and run the complete project here:  
[🔗 Google Colab Notebook](https://colab.research.google.com/drive/1niJhd97ljdab_7N23KNdkzgNG7ku0iW_?usp=sharing)

---

## 👩‍💻 Author

**Anjali Daheriya**  
Feel free to connect or contribute to the project!

