# Toxicity-Detection-System

A Deep Learning based NLP project that detects toxic comments from user input using a trained neural network model.
The system classifies text into different categories of toxicity such as:

* Toxic
* Severe Toxic
* Obscene
* Threat
* Insult
* Identity Hate

## Features

* Text preprocessing using NLP techniques
* Multi-label toxicity classification
* Deep Learning model trained on toxic comment dataset
* Real-time toxicity prediction
* Jupyter Notebook implementation
* Pre-trained `.h5` model included

## Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Scikit-learn
* NLP

## Installation

Clone the repository:

```bash
git clone https://github.com/Priyam0730/toxicity-detection-system.git
cd toxicity-detection-system
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Project

Open the notebook:

```bash
jupyter notebook Toxicity.ipynb
```

Run all cells to train/test the model or use the saved model for predictions.

## Model

The trained model is stored as:

```bash
toxicity.h5
```

It is built using Deep Learning techniques for multi-label text classification.

## Example Prediction

Input:

```text
"You are useless and stupid"
```

Output:

```text
Toxic: True
Insult: True
Threat: False
```



