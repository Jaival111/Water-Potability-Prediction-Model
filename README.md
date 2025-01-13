# Water-Potability-Prediction-Model

This repository contains a machine learning model that predicts if water is potable or not based on various input features. The model was built using **Claasifiaction** and trained on a dataset of water potability data. It has achieved **75% accuracy** on the training set and **64% accuracy** on the test set.

## Project Overview

The goal of this project is to develop a model that can predict if water is potable or not based on features such as ph, Hardness, Conductivity, and other relevant attributes. The dataset used for training and testing the model was carefully preprocessed to ensure the highest possible accuracy.

### Key Features:
- **Classification**: The model uses Linear Regression to find the best-fit line that predicts if water is potable or not based on input features.
- **Accuracy**: Achieved **75% accuracy** on the training data and **64% accuracy** on the test data.

## Dataset

The dataset contains the following columns:
- `pH Value`: pH is an important parameter in evaluating the acid-base balance of water. It is also acidic or alkaline condition of water status. WHO has recommended maximum permissible limit of ph from 6.5 to 8.5. The current investigation ranges were 6.52-6.83 which are in the range of WHO standards.
- `Hardness`: Hardness is mainly caused by calcium and magnesium salts. These salts are dissolved from geologicdeposits through which water travels. The length of time water is in contact with hardness producing material helps determine how much hardness there is in raw water. Hardness was originally defined as the capacity of water to precipitae soap caused by calcium and magnesium.
- `Solids (Total Dissolved Solids-TDS)`: Water has ability to dissolve a wide range of inorganic and some organic materials or salts such as potassium, calcium, sodium, bicarbonates, chlorides, magnesium, sulfates etc. These minerals produced unwanted taste and diluted color in appearance of water. This is the important parameter for use of water. The water with high TDS value indicates that water is highly mineralized. Desirable limit for TDS is 500 mg/l and maximum limit is 1000 mg/l which is prescribed for drinking purpose.
- `Chloramines`: Chlorine and chloramine are the major disinfectants used in public water systems. Chloramines are most commonly formed when ammonia is added to chlorine to treat drinking water. Chlorine levels up to 4 milligrams per liter (mg/L or 4 parts per million (ppm)) are considered safe in drinking water.
- `Sulfate` : Sulfates are naturally occurring substances that are found in minerals, soil, and rocks. They are present in ambient air, groundwater, plants, and food. The principal commercial use of sulfate is in the chemical industry. Sulfate concentration in seawater is about 2,700 milligrams per liter (mg/L). It ranges from 3 to 30 mg/L in most freshwater supplies, although much higher concentrations (1000 mg/L) are found in some geographic locations.
- `Conductivity`: Pure water is not a good conductor of electric current; rather, it is a good insulator. An increase in ion concentration enhances the electrical conductivity of water. Generally, the amount of dissolved solids in water determines the electrical conductivity. Electrical conductivity (EC) actually measures the ionic process of a solution that enables it to transmit current. According to WHO standards, EC value should not exceed 400 µS/cm.
- `Organic_carbon`: Total Organic Carbon (TOC) in source waters comes from decaying natural organic matter (NOM) as well as 
synthetic sources. TOC is a measure of the total amount of carbon in organic compounds in pure water. According to US EPA < 2 mg/L as TOC in treated / drinking water, and < 4 mg/Lit in source water which is use for treatment.
- `Trihalomethanes`: THMs are chemicals which may be found in water treated with chlorine. The concentration of THMs in drinking 
water varies according to the level of organic material in the water, the amount of chlorine required to treat the water, and the temperature of the water that is being treated. THM levels up to 80 ppm is considered safe in drinking water.
- `Turbidity`: The turbidity of water depends on the quantity of solid matter present in the suspended state. It is a measure of light emitting properties of water and the test is used to indicate the quality of waste discharge with respect to colloidal matter. The mean turbidity value obtained for Wondo Genet Campus (0.98 NTU) is lower than the WHO recommended value of 5.00 NTU.
- `Potability`: Indicates if water is safe for human consumption where 1 means Potable and 0 means Not potable.

> Note: Ensure that the data is clean and free from any missing values before running the model.

## Installation

To run the house price prediction model, you need to have Python installed on your machine along with the necessary dependencies. You can set up the environment using the following steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Jaival111/Water-Potability-Prediction-Model.git
    cd Water-Potability-Prediction-Model
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To use the model, you can refer to the jupyter file:

1. Download and prepare the dataset (if not already included).
2. Run the below script:
    ```bash
    jupyter notebook
    ```

## Model Evaluation

The model was evaluated based on the following metrics:
- **Training Accuracy**: 75%
- **Test Accuracy**: 64%

The model generalizes well to unseen data, indicating that the Gradient Boosting approach was effective for this particular dataset.


## Dependencies

The project requires the following Python libraries:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`

Install all dependencies by running:
```bash
pip install -r requirements.txt


