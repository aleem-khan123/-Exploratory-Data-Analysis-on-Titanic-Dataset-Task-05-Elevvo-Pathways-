# -Exploratory-Data-Analysis-on-Titanic-Dataset-Task-05-Elevvo-Pathways-
#  Exploratory Data Analysis on Titanic Dataset (Task 05)

## ** Project Overview**
This project is part of the **Elevvo Pathways Internship 2025**.  
The Titanic dataset is a classic dataset used in **data analysis and machine learning**.  
The main objective was to perform **Exploratory Data Analysis (EDA)** to understand **survival patterns** based on passenger attributes.

---

## ** Objectives**
- Perform data cleaning (handle missing values, encode categorical features)  
- Generate summary statistics for numerical features  
- Explore survival insights by gender, passenger class, and age  
- Visualize survival patterns with plots and heatmaps  
- Save cleaned dataset and grouped outputs for further analysis  

---

## ** Steps Performed**
###  1. Data Cleaning
- Filled missing **Age** values with the median  
- Filled missing **Embarked** values with the most frequent category  
- Dropped **Cabin** column (too many missing values)  
- Encoded categorical variables (**Sex, Embarked**) into numeric form  
- Checked for duplicates → none found  
- Saved cleaned dataset → `Titanic_Cleaned.csv`  

###  2. Feature Engineering
- Created **FamilySize = SibSp + Parch + 1**  
- Created **IsAlone** flag for passengers traveling alone  
- Created **AgeBand** (Child, Teen, YoungAdult, Adult, Senior)  

###  3. Summary Statistics
- Generated descriptive stats for **Age, Fare, SibSp, Parch, FamilySize**  

###  4. Group-Based Insights
- **Survival by Sex** → Females: ~74%, Males: ~19%  
- **Survival by Passenger Class** → 1st Class: highest survival, 3rd Class: lowest  
- **Survival by Age Band** → Children had the highest survival, Seniors the lowest  

###  5. Visualizations
- Bar plots of survival counts by **Sex, Class, Embarked**  
- Histograms of **Age** and **Fare** by survival status  
- Correlation heatmap of numerical features  

###  6. Exported Outputs
- `Titanic_Cleaned.csv` (clean dataset)  
- `survival_by_sex.csv`, `survival_by_pclass.csv`, `survival_by_ageband.csv`  
- Visualization plots (survival trends & heatmap)  

---

## ** Key Findings**
- **Gender** played the biggest role → women had a much higher chance of survival  
- **Passenger Class** strongly influenced survival → first-class passengers had higher chances  
- **Age Factor** → children survived more than teens and adults  
- **Fare & Class** showed strong correlation with survival outcomes  

---

## ** Conclusion**
This task successfully:  
- Cleaned and prepared the Titanic dataset  
- Engineered meaningful new features  
- Extracted insights on **gender, class, and age** impacts on survival  
- Created clear visualizations for survival analysis  

The analysis highlights how **social and economic factors influenced survival during the Titanic disaster**.  
 ## Author

- Aleem Shoukat
- Gmail- aleemshoukat91@gmail.com
- Linked in-www.linkedin.com/in/aleem-shoukat-9bb3b6356

⭐ If you found this project useful, feel free to star this repository!

