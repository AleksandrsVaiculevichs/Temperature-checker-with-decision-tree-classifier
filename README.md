# 🌡️ Temperature-checker-with-decision-tree-classifier
## 📌 Description:
This project presents a machine learning system designed to **classify types of temperature** based on real-world data using a **decision tree classifier**.

The main goal was to develop a model capable of analyzing temperature patterns and assigning them a corresponding label (e.g., *cold*, *normal*, *hot*), enabling automated classification in various contexts such as weather apps or IoT systems.

## 📌 First part:
![alt text](https://github.com/user-attachments/assets/f166c055-1bfa-4bb0-804f-3e61e5e67db5)

To begin with, a dataset from Kaggle was used, which contains temperature data across different times of the day and days of the week. The temperatures were then modified using Excel formulas, and each temperature value was assigned a specific label. This helped to create an approximate balance between all classes.

## 📌 Second part:
![alt text](https://github.com/user-attachments/assets/9c22ec3d-9319-4f9e-90e0-0352da108222)

In the next stage of the project, a Decision Tree Classifier was used, which allows for the creation of detailed trees that make it possible to visualize how the model makes decisions. The Decision Tree Classifier offers three types of criteria, but in this case, two were used: Entropy and Gini. These models differ in the formulas they use for splitting nodes. As a result, one model may reach the goal faster, while the other may require more computational resources.

## 📌 Third part:
![image](https://github.com/user-attachments/assets/a79b9cbc-0446-4acf-bb4e-d8064222ddc6)
![image](https://github.com/user-attachments/assets/687c87ca-9553-4074-a12f-df9ca3834a33)

In the later stage, both models were trained on the dataset using an 80/20 split. During training, it became clear that the Gini model required at least 5 tree levels to achieve maximum performance across all classes, whereas the Entropy model needed only 4. As a result, two models were obtained, both capable of recognizing indoor temperature conditions.

