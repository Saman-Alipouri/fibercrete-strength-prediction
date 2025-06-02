# Fibercrete Strength Prediction

This project uses machine learning to predict the **compressive strength of fiber-reinforced concrete** containing **waste rubber particles** and **polypropylene fibers**, based on experimental mix design data from a civil engineering research thesis.

---

## 🧪 Dataset

The dataset includes various mix designs, including:
- **Control** concrete
- Concrete with **rubber aggregate substitution**
- Concrete with **polypropylene fibers**
- Combined rubber and fiber concrete

Each sample includes mix proportions and curing temperature, with corresponding compressive strength after 28 days.

---

## 📊 Features

| Feature             | Description                            |
|---------------------|----------------------------------------|
| Cement              | Cement content (kg/m³)                 |
| Microsilica         | Microsilica content (kg/m³)            |
| Rubber              | Rubber particles (kg/m³)               |
| Fiber               | Polypropylene fibers (kg/m³)           |
| Water               | Water (kg/m³)                          |
| Superplasticizer    | Admixture content (kg/m³)              |
| CoarseAggregate     | Coarse aggregate (kg/m³)               |
| FineAggregate       | Fine aggregate (kg/m³)                 |
| CuringTemp          | Curing temperature (°C)                |
| **Target**          | **Compressive Strength (MPa)**         |

---

## 🤖 Models Used

- `Linear Regression`
- `Random Forest Regressor`
- `XGBoost Regressor`

All models are evaluated using:
- **R² Score**
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

---

## 📁 Project Structure

```
fibercrete-strength-prediction/
├── concrete_mix.csv        # Dataset
├── modeling.ipynb          # Jupyter Notebook (model training + results)
├── final_model.pkl         # Trained ML model
└── README.md               # Project documentation
```

---

## 📈 Results Summary

The XGBoost model demonstrated the best performance on the test set with:
- High R² score (close to 1)
- Low MAE and RMSE
- Good fit between actual and predicted strengths

You can view the scatter plot comparing **actual vs. predicted** strengths in the notebook.

---

## ✍️ Author

This dataset and analysis were part of a Master's thesis in **Construction Management (Civil Engineering)**.

---

## 📌 License

This project is licensed for educational and research purposes.
