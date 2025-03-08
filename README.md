# ☕ Emre-Cavus-DSA-210-Project 💤📊
This repository contains my **Data Science and Analytics** project, which focuses on analyzing the correlation between **daily caffeine consumption**, **sleep duration**, and **concentration levels**. Using **accurate data collection** and **Machine Learning models**, this project aims to determine whether these factors truly influence concentration and productivity.

---

# Project Outline
1. **Motivation**:
   - As someone who **loves coffee**, I have always believed that after a certain threshold (in terms of cups per day), **sleep quality and duration** are significantly affected. One of my main motivations for this project is to **validate or challenge this assumption** through data analysis.
   - Another key motivation is to find whether there is a **correlation between the combination of daily caffeine levels, and sleep duration and the daily concentration levels** (which will be measured by the time I allocate to studying and the time I allocate to exercises).
   - If there is a correlation between them, then my greatest motivation will be to **find the optimal amount of the combination of caffeine consumption and sleep duration** to produce the **maximum amount of productivity and concentration**, that I will use for myself later on.
  
2. **Data Collection**:
   - **Caffeine Consumption ☕**  
      -  The data that I will be using to represent the daily caffeine levels will mainly have two parts: **the amount of coffee that I consume (cups)**, **and the amount of tea I consume(cups)**. This is because coffee and tea are the two sources of caffeine I consume the most, and I hardly ever consume other types of products that include high levels of caffeine (like coke, energy drinks, supplements...).
   -  **Sleep Duration 💤**  
      -  The sleep duration will be a little less precise compared to the daily levels of caffeine and concentration levels, because **I won't take the time that I spend in bed, but the amount that I actually sleep**.    Because, most of the time when I go to my bed, there are some **distractions** around me that prohibits a good quality sleep. Thus, I will predict the time that I start sleeping with a good quality and calculate it from there which may decrease the accuracy of the data by a small portion.
   -  **Concentration Levels 🎯**  
      -  The daily concentration levels will be based on the duration of two activities that I believe requires the most amounts of concentration and indicators of productivity: daily duration of studying and the amount of time I spend on doing sports. The duration of studying will not involve the lectures and recitations that I am attending as they are my responsibilities at some point, but any other type of studying activity will be included. This can be spending time with my friends for a certain project, or individual studies.

3. **Plan**
   - I will collect these data between the dates **9 March** and **18 April**, 2025.
   - After 18 April, I will transition to the **data analysis phase**, which will involve **statistical interpretations** and **Machine Learning models** to uncover patterns and insights.  
   - 🔍 **Exploratory Data Analysis (EDA) 📊**  
      - **Data Cleaning & Preprocessing**: Handle missing values, remove inconsistencies, and normalize caffeine intake & sleep data.  
      - **Descriptive Statistics**: Calculate mean, median, standard deviation, and other key metrics for each variable.  
      - **Visualization & Trends 📈**:  
        - Use **histograms** to understand the distribution of caffeine intake, sleep, and concentration levels.  
        - Create **scatter plots** to examine relationships between caffeine, sleep, and productivity.  
        - Apply **correlation heatmaps** to detect possible associations between variables.
  - 🤖 **Machine Learning Phase (ML) 🔬**  
      - **Regression Models** (e.g., **Linear Regression, Random Forest Regressor**) to predict concentration levels based on caffeine & sleep data.
      - **Classification Models** (e.g., **Decision Trees, Logistic Regression**) to categorize days into "High Focus" vs. "Low Focus" based on caffeine and sleep habits.  
      - Evaluate model performance using **RMSE (Root Mean Square Error)** and **accuracy scores**.  

