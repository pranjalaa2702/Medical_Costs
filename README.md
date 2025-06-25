# Medical Insurance Costs Predictor

🚀 Developed a machine learning model to estimate medical insurance costs using key demographic and health factors.

## 📥 Input Features

- **Age** – Age of the individual  
- **Sex** – Gender (male/female)  
- **BMI** – Body Mass Index  
- **Children** – Number of dependents  
- **Smoker** – Smoking status (yes/no)  
- **Region** – Residential region in the US

## 🎯 Output

- **Predicted Insurance Charges** – Estimated medical expenses based on the given input features

## 🔎 Key Insights

- **Smoking** and **high BMI** are the most significant factors increasing insurance costs.
- **Age** and **number of children** have a moderate effect.
- **Region** and **sex** have less influence.
- The model can be enhanced by including features such as **medical history** or **exercise frequency**.


## 🚀 Advantages: 
- The model helps understand how lifestyle choices and demographics impact insurance costs, providing insights for both individuals and insurance companies.

## 💻 How to Use

1. Open `Medical_Insurance_Costs.ipynb` in Jupyter Notebook.
2. Run the cells sequentially:
   - Data loading and exploration
   - Feature encoding and scaling
   - Model training and evaluation
3. Modify parameters or experiment with different models (e.g., Linear Regression, Random Forest) to improve accuracy.

## 📚 Model Training

- The model is trained on a labeled dataset with actual insurance charges.
- Evaluation metrics like **Mean Absolute Error** and **R² Score** are used to assess performance.

## ⚙️ Technologies Used

- Python  
- [scikit-learn](https://scikit-learn.org/)  
- [pandas](https://pandas.pydata.org/)  
- [numpy](https://numpy.org/)  
- [seaborn](https://seaborn.pydata.org/)  
- [matplotlib](https://matplotlib.org/)

## ⚡ Installation

Install dependencies with pip:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

## 📧 Contact
- For questions or support, reach out to pranjalaarai@gmail.com.