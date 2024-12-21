# Analysis of Food Data Ingredients

This project focuses on the analysis and classification of food data, including ingredient composition and its various attributes. Inspired by detailed research methodologies, the project employs Python’s powerful data analysis libraries to deliver insights through data manipulation, visualization, and statistical methods.

---

## Features

- **Data Analysis:** Leverage `pandas` and `numpy` for efficient data manipulation and computation.
- **Visualization:** Use `matplotlib` and `seaborn` to create informative and aesthetically pleasing visualizations of the data.
- **Precision Handling:** Customize data display with fine-tuned precision settings in `pandas`.

---

## Food Classification Groups and Formulas

### 1. Grain
- **Exchange Unit**: 23g of carbohydrate.
#### Calculation Formula:
- **I-1**: Cg (carbohydrate per 100g food) / 23
- **I-2**: 100g / (Number of exchanges)

### 2. Meat
- **Exchange Unit**: 8g of protein, with varying lipid and energy values:
  - Low: 2g lipid, 50 kcal
  - Medium: 5g lipid, 75 kcal
  - High: 8g lipid, 100 kcal
#### Calculation Formula:
- **I-1**: Pg (protein per 100g food) / 8
- **I-2**: 100g / (Number of exchanges)

### 3. Vegetables
- **Exchange Unit**: 3g carbohydrate, 2g protein, 20 kcal energy.
#### Calculation Formula:
- **I-1**: Cg (carbohydrate per 100g food) / 3
- **I-2**: 100g / (Number of exchanges)

### 4. Fats and Oils
- **Exchange Unit**: 5g of fat, 45 kcal energy.
#### Calculation Formula:
- **I-1**: Fg (fat per 100g food) / 5
- **I-2**: 100g / (Number of exchanges)

### 5. Milk
- **Exchange Unit**: 11g carbohydrate, 6g protein, 6g fat, 125 kcal energy.
#### Calculation Formula:
- **I-1**: Cg (carbohydrate per 100g food) / 11
- **I-2**: 100g / (Number of exchanges)

### 6. Fruits
- **Exchange Unit**: 12g of sugar, 50 kcal energy.
#### Calculation Formula:
- **I-1**: Cg (carbohydrate per 100g food) / 12
- **I-2**: 100g / (Number of exchanges)

---

## Installation

To get started, clone the repository and ensure you have the required Python libraries installed. You can install them using `pip`:

```bash
pip install numpy pandas matplotlib seaborn
```

---

## Usage

Import the necessary libraries and load your food data into a `pandas` DataFrame. Perform various analyses or customize the code for your specific dataset.

### Example Setup
```python
import numpy as np
import pandas as pd
pd.plotting.register_matplotlib_converters()
import matplotlib.pyplot as plt
%matplotlib inline
import seaborn as sns

pd.set_option("display.precision", 2)
```

---

## Dataset and Documentation

- This project uses a detailed dataset on food components to calculate exchange values for each group.
- **Dataset Link**: [Download Here](https://example.com)

---

## Contributions

Contributions are welcome! Feel free to fork this repository and submit a pull request with your improvements or additional features.

---

## License

This project is licensed under Salaki Reynaldo Joshua.

---

## Contact

For questions or collaboration opportunities, feel free to reach out.

