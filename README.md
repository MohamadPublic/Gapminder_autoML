# Setup
pip install h2o and import the necessary packages. This build is stable on Python 3.11.7.

Ensure that you have downloaded `gapminder.csv` and have placed it in the working directory.

# Explanation
This is a simple model that aims to predict $E[\text{life expectancy} | \text{infant mortality, fertility, population, gdp}]$ for the 2011 data in the gapminder dataset.

This project uses an AutoML package, H2O. The project also uses H2O functionality to explain the best chosen model:

![learning_curve](https://github.com/user-attachments/assets/f74ec658-0f17-49cb-befb-a45729728862)
![variable_importance](https://github.com/user-attachments/assets/bab9987a-c48d-4563-9a4d-53ffe9a43682)
![Individual_conditional_expectation](https://github.com/user-attachments/assets/f9fe9fa0-2b0e-4efd-a2c8-3cdf4e3e2c37)
