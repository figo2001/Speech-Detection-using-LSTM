# Hate Speech Detection Using LSTM

## Project Overview

This project implements a **Hate Speech Detection** model using **Long Short-Term Memory (LSTM)** networks. The aim is to classify text into categories such as hate speech, offensive language, or neither based on labeled data.

## Dataset

The dataset used in this project contains labeled tweets, categorized as:
- **Hate Speech**
- **Offensive Language**
- **Neither**

The dataset is sourced from Kaggle and includes tweet text along with labels.

## Dependencies

The project requires the following Python libraries:
- `pandas`
- `numpy`
- `sklearn`
- `tensorflow` or `keras`

You can install these via pip:

```bash
pip install pandas numpy scikit-learn tensorflow
```

## Project Structure

1. **Data Loading**: The dataset is loaded from a CSV file.
2. **Data Cleaning**: Unnecessary columns are removed, and text is preprocessed.
3. **Model Building**: A deep learning model based on LSTM is built using Keras/TensorFlow.
4. **Training**: The model is trained to classify tweets into three categories.
5. **Evaluation**: The model's performance is evaluated using accuracy, precision, recall, etc.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hate-speech-detection-lstm.git
   cd hate-speech-detection-lstm
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook or Python script to train and evaluate the model.

## Future Improvements

- Adding more advanced preprocessing techniques.
- Fine-tuning the LSTM model or exploring other architectures like transformers.
