# SpaceX Falcon 9 First Stage Landing Prediction

## 🚀 Project Background
The goal of this project is to predict whether the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## 📋 Project Phases & Workflow
This project was completed in several structured stages:

1.  **Data Collection (API & Scraping):**
    *   Collected SpaceX launch data using the **SpaceX API**.
    *   Performed web scraping from Wikipedia to supplement historical launch information.

2.  **Data Wrangling:**
    *   Cleaned the data and handled missing values (specifically for the Payload Mass).
    *   Created a training label based on the landing outcome (1 for success, 0 for failure).

3.  **Exploratory Data Analysis (EDA):**
    *   Used **SQL** and **Pandas** to extract insights from the dataset.
    *   Visualized data using **Matplotlib** and **Seaborn** to find patterns in launch sites and flight distances.

4.  **Interactive Dashboard (Plotly Dash):**
    *   Built a real-time dashboard to filter data by launch site.
    *   Included a Range Slider to analyze the impact of Payload Mass on landing success.

5.  **Predictive Analysis (Machine Learning):**
    *   Trained and compared multiple models: Logistic Regression, SVM, Decision Tree, and K-Nearest Neighbors.
    *   Identified the best-performing model to predict future landing outcomes.

## 🛠️ Tools & Technologies Used
*   **Languages:** Python (Pandas, NumPy, Scikit-learn)
*   **Visualizations:** Matplotlib, Seaborn, Plotly Dash
  
## 📁 File Structure
*   `SpaceX_Data_Collection_API.ipynb`: Collecting data via API.
*   `SpaceX_Web_Scraping.ipynb`: Scraping data from Wikipedia.
*   `SpaceX_Data_Wrangling.ipynb`: Data cleaning and preprocessing.
*   `SpaceX_EDA_SQL.ipynb`: Analyzing data using SQL queries.
*   **`spacex_dash_app.py`**: The interactive Plotly Dash application.
*   `SpaceX_Machine_Learning_Prediction.ipynb`: Building and testing ML models.

---
*This project was developed as the final **Capstone Project** for the **IBM Data Science Professional Certificate**.*
