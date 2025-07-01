# 🌡️ Temperature-checker-with-decision-tree-classifier
## 📌 Description:
This project presents a machine learning system designed to **classify types of temperature** based on real-world data using a **decision tree classifier**.

The main goal was to develop a model capable of analyzing temperature patterns and assigning them a corresponding label (e.g., *cold*, *normal*, *hot*), enabling automated classification in various contexts such as weather apps or IoT systems.

## 📌 First Part

| <img src="https://github.com/user-attachments/assets/f166c055-1bfa-4bb0-804f-3e61e5e67db5" width="200"/> | To begin with, a dataset from **Kaggle** was used, which contains temperature data across different times of the day and days of the week.  
The temperatures were then modified using **Excel formulas**, and each temperature value was assigned a specific label.  
This helped to create an approximate balance between all classes. |
|---|---|

## 📌 Second Part

| <img src="https://github.com/user-attachments/assets/9c22ec3d-9319-4f9e-90e0-0352da108222" width="200"/> | In the next stage of the project, a **Decision Tree Classifier** was used, which allows for the creation of detailed trees that help visualize how the model makes decisions.  
The classifier offers three splitting criteria, but in this case, two were used: **Entropy** and **Gini**.  
These models differ in the formulas they use. One may reach a decision faster but require more computational resources. |
|---|---|
