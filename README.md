# House Price Prediction

A simple machine learning project to predict house prices based on features like size, location, and number of rooms.

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
```

2. Install required packages
```bash
pip install -r requirements.txt
```

## Required Packages

- pandas
- numpy
- scikit-learn
- matplotlib

## How to Use

1. Prepare your data in CSV format with columns:
   - price
   - square_feet
   - bedrooms
   - bathrooms
   - location
   - year_built

2. Train the model:
```python
python train.py
```

3. Make predictions:
```python
python predict.py
```

## File Structure

```
house-price-prediction/
├── data/
│   ├── house_data.csv
│   └── test_data.csv
├── train.py
├── predict.py
├── model.py
└── README.md
```
