# Breast Cancer Prediction using Artificial Neural Networks

This project is a web-based application developed using **Streamlit**, which predicts the likelihood of breast cancer based on user input. It leverages an **Artificial Neural Network (ANN)** trained on the **Breast Cancer Wisconsin dataset** from scikit-learn to classify data into benign or malignant categories.

---

## Features

- **Data Loading and Exploration**: View and understand the structure of the dataset.
- **Feature Selection**: Select the most relevant features for training using the `SelectKBest` method.
- **Model Customization**: Configure the ANN (e.g., hidden layers, activation function).
- **Model Training and Evaluation**: Train the model interactively and view evaluation metrics like accuracy, confusion matrix, and classification report.
- **Visualization**: Display results using confusion matrix heatmaps and performance summaries.

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Python 3.9 or later
- pip (Python package manager)

### Steps to Install
1. Clone this repository:
   ```bash
   git clone https://github.com/Sangavisambathkumar/breastcancer_analysis.git
   ```

2. Create and activate a virtual environment:
   - **Windows**:
     ```bash
     python -m venv venv
     .\venv\Scripts\activate
     ```
   - **MacOS/Linux**:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

---

## Usage

1. Open the application in your browser. The default URL is: `[http://localhost:8501](http://localhost:8506/)`.
2. Use the sidebar to navigate through the app:
   - **Dataset**: Explore the Breast Cancer Wisconsin dataset.
   - **Feature Selection**: Choose the number of top features to use in training.
   - **Model Training**: Customize and train the ANN model.
   - **Evaluation**: View the confusion matrix, classification report, and accuracy metrics.

---

## File Structure

- **app.py**: Main Streamlit application file.
- **model.pkl**: Pre-trained ANN model saved using Pickle.
- **scaler.pkl**: Scaler used for normalizing input data.
- **requirements.txt**: List of Python dependencies.

---

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Framework for building interactive web applications.
- **scikit-learn**: For dataset handling, feature selection, and model training.
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation.
- **Seaborn**: For visualizing confusion matrices.

---

