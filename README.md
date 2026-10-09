# 🌿 Plant Disease Detection Using Deep Learning

## 📌 About the Project

Plant Disease Detection is a machine learning project developed as a second-year mini project. The main objective of this project is to identify plant diseases by analyzing images of plant leaves using image classification techniques.

Plant diseases can negatively affect crop quality and agricultural productivity. Early identification can help farmers take appropriate preventive measures and reduce potential crop losses. This project explores the application of deep learning and image classification techniques for automated plant disease detection.

## 🎯 Objectives

- To explore automated plant disease detection using leaf images.
- To preprocess plant images for model training and testing.
- To train a deep learning model for plant disease classification.
- To evaluate the model using testing data.
- To understand the application of artificial intelligence in agriculture.

## ⚙️ Project Workflow

1. **Dataset Preparation:** Prepare plant leaf images for training and testing.
2. **Image Preprocessing:** Process the images into a suitable format for the model.
3. **Model Training:** Train a deep learning image classification model using the training dataset.
4. **Model Testing:** Evaluate the trained model using testing data.
5. **Performance Evaluation:** Analyze the model's predictions and evaluation results.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Deep Learning
- Image Classification

*The exact deep learning framework, libraries, and model architecture can be documented after verifying the notebook code.*

## 📂 Project Structure

```text
Plant-Disease-Detection/
│
├── train.ipynb          # Model training notebook
├── test.ipynb           # Model testing and evaluation notebook
├── model.weights.h5     # Saved trained model weights
└── README.md            # Project documentation
```

## 📓 Project Files

### 1. train.ipynb

Contains the notebook for developing and training the plant disease classification model, including the training workflow implemented in the notebook.

### 2. test.ipynb

Contains the notebook for testing and evaluating the model using the testing workflow implemented in the notebook.

### 3. model.weights.h5

Contains the saved trained model weights. These weights can be loaded into the corresponding model architecture to restore the learned parameters for prediction.

**Note:** The model architecture and compatible configuration must be available to load the weights correctly.

## 📊 Dataset

The original plant disease image dataset is not included in this repository.

The notebooks document the project's training and testing workflow. To reproduce the complete training and evaluation process, the required dataset must be obtained separately and the dataset paths must be configured according to the notebook code.

## 🤖 Trained Model

The trained model weights are available in `model.weights.h5`.

The saved weights represent parameters learned during model training. To use them for prediction, the corresponding model architecture must be recreated or loaded, and the weights must be compatible with that architecture.

The trained model can then be used to classify plant leaf images after applying the same preprocessing steps used during training.

## 🚀 How to Run the Project

### Prerequisites

- Python
- Jupyter Notebook
- Required Python libraries used in the notebooks
- The original dataset for training and testing

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Plant-Disease-Detection.git
```

Replace `YOUR_USERNAME` with your GitHub username.

### Step 2: Navigate to the Project Directory

```bash
cd Plant-Disease-Detection
```

### Step 3: Install Jupyter Notebook

```bash
pip install notebook
```

Install the other dependencies required by the notebooks. For example, if the project uses TensorFlow/Keras, install the compatible framework version.

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebooks

Open `train.ipynb` to review the training workflow or `test.ipynb` to review the testing and evaluation workflow.

**Important:** Running the complete training or testing workflow requires the appropriate dataset, compatible dependencies, and correct file paths. Prediction using the saved weights additionally requires the corresponding model architecture.

## 🎓 Project Information

- **Project Title:** Plant Disease Detection Using Deep Learning
- **Project Type:** Second-Year Mini Project
- **Domain:** Machine Learning / Deep Learning
- **Application Area:** Agriculture

## 🔮 Future Enhancements

- Restore and organize the original plant disease image dataset.
- Document the model architecture and the plant disease classes supported.
- Add reproducible training and evaluation instructions.
- Develop a user-friendly interface for uploading plant leaf images.
- Display the predicted disease class for an uploaded image.
- Deploy the application as a web-based plant disease detection system.

## 👩‍💻 Author

Developed as an academic mini project to explore the use of deep learning and image classification for plant disease detection.

---

⭐ If you find this project interesting, feel free to explore the notebooks and learn about applying machine learning to agriculture.
