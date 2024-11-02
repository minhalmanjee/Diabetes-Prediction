# Diabetes_prediction
Preview of the Project
![Alt text](https://github.com/minhalmanjee/Diabetes-Prediction/blob/main/Images/1.PNG)
![](images/2.PNG)
![](images/3.PNG)
![](images/4.PNG)

This project is a **Streamlit-based web application** designed to help users assess the risk of diabetes based on user-inputted medical data. The app leverages **machine learning**, specifically a **Random Forest Classifier**, trained on the **PIMA Indian Diabetes dataset**. Below is a detailed summary of the project components:

### 1. **Project Overview**
The application provides an intuitive and interactive interface where users can input relevant medical data such as **glucose levels, blood pressure, BMI**, and other health indicators to generate a report on their diabetes risk. The application uses visual graphs to compare the user's data with the dataset, providing an educational tool to help users better understand their health status.

### 2. **Technologies and Libraries Used**
- **Python** as the programming language.
- **Streamlit** for building the interactive web interface.
- **Pandas** for data handling and analysis.
- **Seaborn** and **Matplotlib** for data visualization.
- **Scikit-learn** for machine learning, including training and evaluation.
- **PIL (Python Imaging Library)** and **NumPy** for additional data processing tasks.
- **Plotly** for potential interactive visualizations.

### 3. **Data Processing**
The project uses the PIMA Indian Diabetes dataset, which includes features such as:
- **Pregnancies**
- **Glucose**
- **Blood Pressure**
- **Skin Thickness**
- **Insulin**
- **BMI**
- **Diabetes Pedigree Function (DPF)**
- **Age**

The dataset is split into training and test sets using an 80-20 ratio for training the **Random Forest Classifier**.

### 4. **Model Training and Evaluation**
The **Random Forest Classifier** is trained on the training set and evaluated using the test set to ensure the model’s accuracy. The model’s prediction is displayed alongside the test set accuracy to inform the user about its performance.

### 5. **User Input and Report Generation**
The user provides medical details through the **sidebar input widgets** in the Streamlit interface. The input is processed and displayed as a dataframe. The trained model then makes a prediction on the input data, which is:
- Displayed as a clear message indicating whether the user is likely diabetic or not.
- Accompanied by a calculated **accuracy score** of the model.

### 6. **Visualizations**
To make the experience more engaging, the app includes visualizations:
- **Scatter plots** showing user data in comparison to the dataset across different parameters like **Age vs. Glucose**, **Age vs. BMI**, etc.
- Custom color-coded markers distinguish the user's data from the dataset.
- Visual cues help users understand where they stand relative to healthy and diabetic outcomes.

### 7. **Outcome**
Users receive an easy-to-understand report indicating whether they are diabetic, coupled with visual feedback. The application provides an accessible way for users to check their diabetes risk and enhances their understanding through interactive and educational visual content.

### **Conclusion**
This project offers an effective demonstration of integrating **machine learning** and **web application development** to create practical, user-friendly health tools. It combines data science and visualization techniques to provide an interactive experience that can raise awareness and facilitate better understanding of health data.
