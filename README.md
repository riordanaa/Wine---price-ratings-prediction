# Wine Price and Ratings Prediction

This project uses machine learning to predict wine prices and ratings based on various features including sentiment analysis of wine reviews. The project implements multiple approaches including XGBoost and Neural Networks with embeddings.

## Dataset

The dataset used in this project is not included in the repository due to licensing. The analysis uses a proprietary wine retail dataset that includes:
- Wine reviews and descriptions
- Pricing information
- Ratings and scores
- Other wine characteristics

## Project Structure

```
├── notebooks/
│   ├── Wine Retail Dataset - Sentiment + XGboost.ipynb
│   ├── Wine Retail Dataset - Neural Network Embeddings.ipynb
│   ├── Wine Retail Dataset - XGBoost - main approach.ipynb
│   └── Wine Retail Dataset - Sentiment + XGboost - Andrew Berg
│   └── Wine Retail Dataset - Custom Embeddings + Custom CNN - Andrew Berg
├── requirements.txt
├── pyproject.toml
└── README.md
```

## Setup

1. Create a Python virtual environment (Python 3.11+ required):
```bash
python -m venv .venv
```

2. Activate the virtual environment:
- Windows:
```bash
.venv\Scripts\activate
```
- Unix/MacOS:
```bash
source .venv/bin/activate
```

3. Install dependencies using UV (recommended) or pip:
```bash
# Using UV (faster, more reliable)
uv pip install -r requirements.txt

# Or using pip
pip install -r requirements.txt
```

## Key Features

- Sentiment analysis of wine reviews using TextBlob
- XGBoost regression models for price prediction
- Neural Network models with text embeddings
- Comprehensive data preprocessing and feature engineering

## Dependencies

Major dependencies include:
- PyTorch (with CUDA support for non-MacOS systems)
- XGBoost
- scikit-learn
- pandas
- TextBlob
- Transformers
- matplotlib/seaborn for visualization

For a complete list of dependencies, see `requirements.txt` or `pyproject.toml`.

## License

This project is licensed under the terms included in the LICENSE file.

## Contributors

> TODO

## Note

The dataset used in this analysis is not publicly available. To run the notebooks, you'll need to obtain the appropriate wine retail dataset and place it in the correct location as referenced in the notebooks.
