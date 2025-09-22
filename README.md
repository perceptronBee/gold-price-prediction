# Gold Price Prediction with LazyPredict

## 📌 Project Goal
The main objective of this project is to improve **Exploratory Data Analysis (EDA)** skills and to learn how to use the **LazyPredict** library.  
The project benchmarks multiple regression models on a financial dataset and analyzes their performance in predicting gold prices.  

## 📊 Dataset
- Source: [Kaggle - Financial Data](https://www.kaggle.com/datasets/franciscogcc/financial-data)  
- The dataset contains financial indicators and gold price values.  
- The target variable is the gold price, predicted using various financial features.  

## ⚙️ Methods
- Used **LazyPredict** to quickly train and evaluate multiple regression models.  
- Due to the dataset’s linear-like structure, **Linear Regression** achieved the best performance.  
- Regularization methods (Ridge, Lasso) and more complex models tended to distort predictions instead of improving them.  

## 📝 Key Learnings
- **EDA is crucial**: Understanding the dataset before model selection is essential.  
- **LazyPredict** is a powerful tool for fast benchmarking of ML models.  
- Sometimes **simpler models** (e.g., Linear Regression) can outperform more complex ones, especially on linear datasets.  

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/perceptronBee/gold-price-prediction.git
   
2. Run the notebook:
   ```bash
   jupyter notebook gold-price-prediction.ipynb



## 📈 Results

- **Best model:** Linear Regression
- Regularization and complex models did not improve performance.
- The results highlight the dataset’s strongly linear structure.

## 📚 Tools & Libraries

- Python 3
- Pandas
- Numpy
- Matplotlib
- scikit-learn
- LazyPredict

---

👤 **Author:** [perceptronBee](https://github.com/perceptronBee)  
🔗 **Twitter:** [@perceptronBee](https://x.com/perceptronBee)

