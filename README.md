# 📊 Linear Regression: Predicting Housing Prices and Area

This project demonstrates a simple implementation of **Linear Regression** using two variables — `price` and `area` — to build a predictive model. The goal is to understand how one variable (e.g., price) can be used to predict another (e.g., area), using **gradient descent** implemented from scratch.

---

## 📁 Dataset

The dataset contains housing data with the following columns:

- `price`: Price of the house (in ₹)
- `area`: Area of the house (in square feet)

Make sure your data is clean and formatted correctly before training the model.

---

## 🧠 Features

- Manual implementation of **gradient descent**
- **Data normalization** to improve convergence
- Visualization using `matplotlib`
- Prediction for given house price
- Uses only `NumPy`, `Pandas`, and `Matplotlib`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Niirav213/linear_regression.git
cd linear_regression
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib
```

### 3. Run the Notebook

Open `linear_regression.ipynb` in **Jupyter Notebook** or **VS Code** and run all cells step-by-step.

---

## 🔍 Code Overview

### 🧮 Gradient Descent Function

```python
def gradient_descent(m_now, b_now, data, L):
    # Iterative update of slope and intercept
    return m, b
```

### 📈 Plotting the Regression Line

```python
plt.scatter(data['price'], data['area'], color='blue', label='Data Points')
plt.plot(data['price'], m * data['price'] + b, color='red', label='Regression Line')
plt.xlabel('Price')
plt.ylabel('Area')
plt.title('Linear Regression: Price vs Area')
plt.legend()
plt.show()
```

### 🔮 Prediction

```python
predicted_area = m * normalized_price + b
```

---

## ✅ Output Example

- ✅ Predicted area for price ₹5,000,000: **~1200 sq ft**
- 📉 Model fits linearly
- 📊 Regression line overlays data accurately

---

## 📚 Concepts Covered

- Mean Squared Error (MSE)
- Gradient Descent
- Data Normalization
- Linear Regression Intuition
- Vectorized Implementation (optional)

---

## 💡 Future Improvements

- Add support for multiple features
- Evaluate model performance (R², MAE)
- Add GUI using Streamlit or Flask

---

## 👨‍💻 Author

**Nirav Parmar**  
🔗 GitHub: [Niirav213](https://github.com/Niirav213)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
