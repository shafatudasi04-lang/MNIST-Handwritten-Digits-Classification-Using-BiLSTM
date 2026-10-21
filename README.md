# MNIST Handwritten Digits Classification Using Bidirectional LSTM

## 📌 Project Overview
This project uses a **Bidirectional Long Short-Term Memory (BiLSTM)** neural network to classify handwritten digits from 0 to 9 using the MNIST dataset. The model is developed with TensorFlow and Keras in Google Colab.

## 🎯 Objectives
- Classify handwritten digits from 0 to 9.
- Build a deep learning model using Bidirectional LSTM.
- Visualize training accuracy and loss.
- Evaluate the model using a confusion matrix and classification report.
- Compare actual and predicted labels.
- Export predictions to a CSV file.

## 📂 Dataset
**MNIST Handwritten Digits Dataset**

- Training images: 60,000
- Testing images: 10,000
- Image dimensions: 28 × 28 pixels
- Number of classes: 10 (digits 0–9)
- Pixel values are normalized to the range 0–1.

The dataset is loaded directly using TensorFlow. Manual ZIP downloads and Kaggle API credentials are not required.

## 🛠️ Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## 🧠 Model Architecture
The model includes:
1. Input layer for 28 × 28 pixel images
2. Bidirectional LSTM layer
3. Layer Normalization
4. Dropout layers to reduce overfitting
5. Second Bidirectional LSTM layer
6. Fully connected Dense layer
7. Softmax output layer with 10 classes

## ⚙️ Model Training
- **Model:** Bidirectional LSTM
- **Optimizer:** Adam
- **Loss Function:** Sparse Categorical Crossentropy
- **Epochs:** 10
- **Batch Size:** 128
- **Learning Rate Adjustment:** ReduceLROnPlateau
- **Validation:** 10% of the training data

## 📊 Evaluation and Visualization
The project generates:
- Training and validation accuracy graph
- Training and validation loss graph
- Test accuracy and loss
- Confusion matrix
- Classification report
- Actual vs. predicted digit visualization
- Predictions CSV file

## 📁 Project Files
Recommended repository structure:

```text
MNIST-Handwritten-Digits-Classification-Using-BiLSTM/
├── MNIST_Bidirectional_LSTM.ipynb
├── MNIST_Bidirectional_LSTM_Project_Documentation.pdf
├── mnist_lstm_predictions.csv
└── README.md
```

The notebook and PDF documentation should be uploaded to GitHub. The predictions CSV is optional.

## 🚀 How to Run
1. Open the notebook in Google Colab.
2. Run the cells sequentially from top to bottom.
3. Allow TensorFlow to download the MNIST dataset.
4. Train the BiLSTM model.
5. Review the evaluation metrics and graphs.
6. Generate and save the predictions CSV file.

## 💾 Output Files
- `mnist_bidirectional_lstm.keras` — trained model
- `mnist_lstm_predictions.csv` — actual and predicted digit labels
- Accuracy and loss graphs
- Confusion matrix and classification report

## 🔮 Future Improvements
- Compare BiLSTM with CNN and other neural network models.
- Tune hyperparameters to improve performance.
- Add a user interface for predicting digits from uploaded images.
- Save and deploy the trained model as a web application.

## 👨‍💻 Author
**Shafaat Ullah**

GitHub: [shafatudasi04-lang](https://github.com/shafatudasi04-lang)

## 📄 License
This project is intended for educational and learning purposes. Add a suitable open-source license if you want others to reuse and distribute your code.

---
*Built with Python, TensorFlow, and Keras.*
