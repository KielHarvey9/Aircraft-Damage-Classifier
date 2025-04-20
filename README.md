# Aircraft Damage Classification and Image Captioning 🛩️🔍🧠

This project combines deep learning image classification using **VGG16** with **image captioning and summarization** powered by a **BLIP pre-trained model**. It was developed as part of the [Coursera IBM Deep Learning Course Final Project](https://coursera.org).

## 📁 Project Structure

- `Final_Project_Classification_and_Captioning.ipynb`: Main notebook containing all tasks for the project.
- Dataset: Aircraft damage images categorized for training, validation, and testing (not included here due to size).
- Uses TensorFlow/Keras for image classification and HuggingFace Transformers for BLIP captioning.

## 🧠 Tasks Covered

### Part 1: Classification using VGG16
- Load and fine-tune a VGG16 model
- Prepare `train`, `validation`, and `test` image generators
- Compile and train the model using binary cross-entropy and Adam optimizer
- Visualize training vs validation accuracy
- Evaluate the model on the test dataset

### Part 2: Image Captioning and Summarization using BLIP
- Create a custom Keras layer to wrap the BLIP model
- Build a helper function `generate_text()` that supports both captioning and summarizing
- Load an image and use BLIP to generate:
  - A natural language caption describing the image
  - A brief summary describing the image content

## 💾 Getting Started

### 🔧 Requirements

- Python 3.8+
- TensorFlow
- Hugging Face `transformers` and `torch`
- PIL (Pillow)
- matplotlib

Install with:
```bash
pip install tensorflow transformers torch pillow matplotlib
