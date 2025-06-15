# Text Mining - Stock Sentiment Analysis

This project implements a text mining solution for stock sentiment analysis using various machine learning and deep learning approaches.

## Project Structure

```
├── tm_final_01.ipynb           # Final Model Notebook
├── tm_tests1_01.ipynb          # Main Work Notebook
├── tm_tests2_01.ipynb          # Extra Work Notebook 1
├── tm_tests3_01.ipynb          # Extra Work Notebook 2
├── Project Data-20250518/      # Dataset directory
│   ├── train.csv               # Training data
│   └── test.csv                # Test data
├── Test Predictions/           # Model predictions
│   └── pred_01.csv             # Prediction results
├── requirements.txt            # Python dependencies
└── README.md                   # This file
```

## Results

Model predictions are saved in `Test Predictions/` with the latest results as `pred_01.csv`.

## Requirements

### Core Libraries
- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Data visualization
- **seaborn** - Statistical data visualization

### Natural Language Processing
- **nltk** - Natural Language Toolkit
- **wordcloud** - Word cloud generation
- **vaderSentiment** - Sentiment analysis
- **gensim** - Topic modeling and word embeddings

### Machine Learning
- **scikit-learn** - Machine learning algorithms
- **tensorflow** - Deep learning framework
- **keras-tuner** - Hyperparameter optimization

### Additional Libraries
- **transformers** - Hugging Face transformers
- **sentence-transformers** - Sentence embeddings
- **torch** - PyTorch deep learning framework
- **xgboost** - Gradient boosting framework
- **openai** - OpenAI API integration

## Usage

1. **Main Analysis**: Run `tm_tests1_01.ipynb` for the primary sentiment analysis workflow
2. **Final Model**: Use `tm_final_01.ipynb` for the optimized final model
3. **Additional Experiments**: Explore `tm_tests2_01.ipynb` and `tm_tests3_01.ipynb` for extended analysis

