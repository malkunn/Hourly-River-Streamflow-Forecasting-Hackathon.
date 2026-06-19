# 🌊 Hourly River Streamflow Forecasting Hackathon

## 📌 Project Overview

This repository contains the code and workflow for the **Hourly River Streamflow Forecasting Hackathon** hosted on Kaggle.

The objective of this project is to build a machine learning or deep learning model that can forecast **hourly river streamflow** using historical hydrological data.

Accurate streamflow forecasting is important for:

* Flood prediction
* Water resource management
* Hydrological monitoring
* Disaster risk reduction
* Environmental planning

---

## 🏆 Kaggle Competition

This project is based on the Kaggle competition below:

🔗 **Competition Link:**
[Hourly River Streamflow Forecasting Hackathon](https://www.kaggle.com/competitions/hourly-streamflow-forecasting-hackathon)

---

## 📂 Dataset

The dataset is provided by Kaggle and is **not uploaded to this repository** due to file size limitations and competition rules.

Please download the dataset manually from the Kaggle competition page:

👉 [Download Dataset from Kaggle](https://www.kaggle.com/competitions/hourly-streamflow-forecasting-hackathon/data)

After downloading, place the dataset inside the `data/` folder.

Required file path:

```text
data/trainTrackA.csv
```

Example folder structure:

```text
Hourly-River-Streamflow-Forecasting-Hackathon/
│
├── data/
│   ├── trainTrackA.csv
│   ├── testTrackA.csv
│   ├── trainTrackB.csv
│   ├── testTrackB.csv
│   └── example_submission.csv
│
├── notebooks/
│   └── model_training.ipynb
│
├── outputs/
│   └── submission.csv
│
├── README.md
└── requirements.txt
```

---

## 🎯 Project Objective

The goal of this project is to develop a forecasting model that can predict hourly river streamflow values with the lowest possible prediction error.

The model performance is evaluated using **Root Mean Squared Error (RMSE)**.

A lower RMSE value means the model prediction is better.

---

## 🧠 Methodology

The project workflow includes:

1. **Data Loading**
   Load the training and testing datasets from Kaggle.

2. **Exploratory Data Analysis**
   Analyze the streamflow pattern, missing values, trend, seasonality, and peak flow behavior.

3. **Data Preprocessing**
   Clean the dataset, scale numerical values, and prepare time-series sequences for model training.

4. **Model Development**
   Train and compare forecasting models such as:

   * Baseline model
   * LSTM
   * GRU
   * Bidirectional LSTM
   * Hybrid deep learning model

5. **Model Evaluation**
   Evaluate the model using RMSE and compare the performance between different model versions.

6. **Kaggle Submission**
   Generate the final `submission.csv` file and upload it to Kaggle.

---

## 📊 Evaluation Metric

The main evaluation metric used in this competition is:

**Root Mean Squared Error (RMSE)**

RMSE formula:

```text
RMSE = sqrt(mean((actual - predicted)^2))
```

The objective is to minimize the RMSE score.

---

## 🚀 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Hourly-River-Streamflow-Forecasting-Hackathon.git
cd Hourly-River-Streamflow-Forecasting-Hackathon
```

### 2. Download the Dataset

Download the dataset from Kaggle:

[Download Dataset](https://www.kaggle.com/competitions/hourly-streamflow-forecasting-hackathon/data)

Then place the files inside the `data/` folder.

Example:

```text
data/trainTrackA.csv
data/testTrackA.csv
data/sample_submission.csv
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Run the Notebook

Open and run the notebook:

```text
notebooks/model_training.ipynb
```

---

## 🛠️ Tools and Libraries

This project may use the following tools and libraries:

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras
* PyTorch
* Google Colab
* Kaggle API

---

## 📈 Model Development Progress

| Stage        | Model / Method               | Description                                                               |
| ------------ | ---------------------------- | ------------------------------------------------------------------------- |
| Assessment 1 | Baseline Model               | Initial model used as the starting benchmark                              |
| Assessment 2 | Improved Deep Learning Model | Improved preprocessing and sequence learning                              |
| Assessment 3 | Final Model                  | Final tuned model with better feature handling and submission preparation |

---

## 🔍 Key Challenges

Some challenges in this competition include:

* River streamflow has strong time-series dependency.
* Peak flow events are difficult to predict accurately.
* Hydrological patterns can change over time.
* Deep learning models require careful tuning.
* Large datasets may cause memory issues in Google Colab.

---

## 📌 Results

The final model aims to reduce RMSE and improve prediction accuracy compared to the baseline model.

| Model          | RMSE Score    |
| -------------- | ------------- |
| Baseline Model | To be updated |
| Improved Model | To be updated |
| Final Model    | To be updated |

---

## 📤 Submission

The final prediction file should follow the format provided in:

```text
sample_submission.csv
```

Final output file:

```text
submission.csv
```

Upload the submission file here:

🔗 [Submit on Kaggle](https://www.kaggle.com/competitions/hourly-streamflow-forecasting-hackathon/submissions)

---

## ⚠️ Important Note

The dataset is not included in this repository.

Please download the dataset manually from Kaggle and place it in the correct folder before running the notebook.

Required path:

```text
data/trainTrackA.csv
```

---

## 🙋‍♂️ Author

**Ahmad Hazami**

GitHub: [@hazami-razip](https://github.com/hazami-razip)
         [@malkunn](https://github.com/malkunn)

---

## 📜 License

This project is created for educational and competition purposes.

Please follow Kaggle’s competition rules and dataset usage policy.
