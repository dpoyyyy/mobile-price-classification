# Mobile Price Range Classification

This project classifies mobile phones into four price ranges based on their features using a **Support Vector Machine (SVM)** model.

## Dataset

The dataset (`mobile_prices.csv`) includes various features of mobile phones, such as:
- `battery_power`: Battery capacity in mAh
- `blue`: Bluetooth support (1 = Yes, 0 = No)
- `clock_speed`: Speed of the processor in GHz
- `dual_sim`: Dual SIM support (1 = Yes, 0 = No)
- `fc`: Front camera resolution in megapixels
- `four_g`: 4G support (1 = Yes, 0 = No)
- ...and more.

The `price_range` column is the target variable:
- `0`: Low cost
- `1`: Medium cost
- `2`: High cost
- `3`: Very high cost

## Installation
 Clone the repository:
   ```bash
   git clone https://github.com/dpoyyyy/svm.git
   cd svm
   ```

## Usage

1. Open and run `SVM.ipynb` to load the data, preprocess it, train the SVM model, and evaluate its performance.
2. Visualize model performance metrics using the plots in the notebook.

## Results

The notebook provides insights into the classification accuracy and performance of the SVM model in predicting mobile phone price ranges.
