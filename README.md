# Yale University Graduation Rate Prediction

This project explores the use of linear regression models to predict graduation rates of colleges in the United States based on institutional features. Using a cleaned dataset of over 700 institutions, I aimed to identify significant predictors and build models that are interpretable and accurate.

The final model was used to estimate the graduation rate of Yale University.

## Project Objective

The goal of this project was to:
- Investigate which factors (e.g., acceptance rates, student demographics, tuition costs) influence college graduation rates.
- Build both full and reduced linear regression models using BIC-based stepwise selection.
- Evaluate the performance of the models.
- Predict the expected graduation rate for Yale University.

## Tools and Technologies

- **Python**
- **Pandas** for data wrangling
- **Seaborn** for data visualization
- **Statsmodels** for regression modeling
- **Matplotlib** for charts

## Key Steps

- Imported and explored the dataset (`College.csv`)
- Visualized distributions and relationships using pair plots and correlation matrices
- Built a full linear regression model with all predictors
- Applied backward stepwise selection using BIC to derive a simpler model
- Interpreted coefficients and checked diagnostic plots
- Predicted the graduation rate for Yale University using the reduced model

## Results

- The reduced model retained high explanatory power while simplifying interpretation.
- The **predicted graduation rate for Yale University** was approximately **88.85%**, closely aligned with its actual performance.


## How to Run

1. Clone the repository.
2. Install dependencies using pip or conda.
3. Open `college predict.ipynb` in Jupyter Notebook.
4. Run the cells step by step to view analysis, modeling, and predictions.

## License

This project is licensed under the MIT License.


