# Mobile Price Classification using Machine Learning

Predicting mobile phone price ranges based on hardware specifications using KNN, SVM, and MLP.

## Dataset

- 2,000 samples, 20 features, 4 classes (Low / Medium / High / Very High)
- Balanced dataset: 500 samples per class
- Source: [Kaggle – Mobile Price Classification](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification)

## Models & Results

| Model | Accuracy |
|---|---|
| KNN (k=100) | 65.0% |
| MLP | 90.3% |
| SVM (Linear kernel) | 95.3% |

SVM with a linear kernel performed best, suggesting the data is approximately linearly separable in high-dimensional space.

## How to Run

1. Clone the repo
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open `Mobile-Price-Classification.ipynb` and run all cells

## Course

COE 292 – Introduction to Artificial Intelligence
