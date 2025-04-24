# SalesForecast

## Table of Contents
- [Project Overview](#project-overview)
- [Setup & Installation](#setup--installation)
- [Contributors](#contributors)

## Project Overview
SalesForecast is an advanced machine learning solution designed to tackle the challenging problem of retail sales forecasting. By leveraging historical sales data, store metadata, and external factors, our system provides accurate daily sales predictions to optimize inventory management and maximize retail efficiency.

## Setup

### Application Setup

1. **Clone Repository**
```bash
git clone https://github.com/mjengert/SalesForecast.git
cd SalesForecast
cd src
```

2. **Install Required Packages**
```bash
pip install "pandas>=1.5.0" "numpy>=1.23.0" "matplotlib>=3.6.0" "scikit-learn>=1.2.0"
```

3. **Download Dataset from Kaggle**
```bash
kaggle competitions download -c store-sales-time-series-forecasting
```

```bash
unzip store-sales-time-series-forecasting.zip -d store-sales-time-series-forecasting
```

5. **Run Model Notebook**
```bash
jupyter notebook MLP.ipynb
```

## Contributors
- Nicholas
- Ahmed
- Maralynn
- Duncan
