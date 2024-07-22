# Stocks-Price-Analysis-and-Recommendation
Analyzing and predicting the stock prices,multiple machine learning models, including LSTM (Long Short-Term Memory), Prophet, and others
### README.md

```markdown
# Sberbank Rossii,Koc Holding ,Medinet Nasr Housing,Minerva SABrazil,Pampa Energia, Cementos Argos,Impala Platinum,Dongkuk Steel Stock Price Analysis

This repository contains a Jupyter Notebook for analyzing and predicting the stock prices of Sberbank Rossii. The notebook utilizes multiple machine learning models, including LSTM (Long Short-Term Memory), Prophet, and others, to forecast stock prices and provide buy/sell/hold recommendations.

## Files

- `Sberbank Rossii.ipynb`:
- 'Koc Holding.ipynb':
- 'Medinet Nasr Housing.ipynb':
- 'Minerva SABrazil.ipynb':
- 'Cementos Argos.ipynb':
- 'Impala Platinum.ipynb':
- 'Dongkuk Steel.ipynb': Jupyter Notebook with the code for data preprocessing, model training, prediction, and recommendation generation.

## Installation

To run the notebook, you need to have Python installed along with the following libraries:

- numpy
- pandas
- tensorflow
- sklearn
- fbprophet

You can install the required libraries using pip:

```bash
pip install numpy pandas tensorflow scikit-learn fbprophet
```

#### Introduction

This technical report provides a detailed explanation of each block of code in the Jupyter Notebook titled "Sberbank Rossii 2.ipynb." The notebook aims to analyze and predict the stock prices of Sberbank Rossii using multiple machine learning models, including LSTM (Long Short-Term Memory), Prophet, and others. It also generates buy/sell/hold recommendations based on these predictions.

#### Table of Contents

1. Data Preprocessing
2. Model Training and Predictions
    - LSTM Model
    - Prophet Model
    - Other Models
3. Recommendation Generation

---

#### 1. Data Preprocessing

The data for Sberbank Rossii stock prices for the year 2020 and Q1 2021 is loaded into pandas DataFrames. The presence of missing values in the datasets is checked and handled using the forward fill method to maintain data continuity.

---

#### 2. Model Training and Predictions

**LSTM Model**

The LSTM model is created and trained on the 2020 data to predict future stock prices. The data is transformed into a format suitable for LSTM, scaled, and sequences are created for training. The model includes two LSTM layers followed by a Dense layer.

**Prophet Model**

The 2020 data is reformatted for use with the Prophet model, which is then trained on the 2020 data. The model generates future predictions for the next 90 days, corresponding to Q1 2021.

**Other Models**

Additional models are implemented for comparison and further analysis. These models include:

- Model without biological bonds.
- Three other models varying in complexity and methodology.

Each model is trained on the provided data and used to generate predictions for comparison.

---

#### 3. Recommendation Generation

The `generate_recommendations` function generates buy/sell/hold recommendations based on the predicted and actual stock prices. Recommendations are generated using the predictions from each of the models.



## Files

- `Sberbank Rossii.ipynb`:
- 'Koc Holding.ipynb':
- 'Medinet Nasr Housing.ipynb':
- 'Minerva SABrazil.ipynb':
- 'Cementos Argos.ipynb':
- 'Impala Platinum.ipynb':
- 'Dongkuk Steel.ipynb': Jupyter Notebook with the code for data preprocessing, model training, prediction, and recommendation generation.

## Installation

To run the notebook, you need to have Python installed along with the following libraries:

- numpy
- pandas
- tensorflow
- sklearn
- fbprophet

You can install the required libraries using pip:

```bash
pip install numpy pandas tensorflow scikit-learn fbprophet
```

## Usage

1. Clone this repository.
2. Open the `Sberbank Rossii 2.ipynb` notebook.
3. Follow the steps in the notebook to preprocess the data, train the models, and generate predictions.


## Contributing

Feel free to open issues or submit pull requests if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
```


