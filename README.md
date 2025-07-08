📊 Student Performance Analysis with Python

Welcome to this data analysis project where we dive deep into the Student Performance dataset using Python's data science stack. This notebook showcases data loading, preprocessing, analysis, and visualization to uncover insights into students' academic scores.


📁 Dataset Used

StudentsPerformance.csv
Contains information like:

Gender

Parental education level

Test preparation course

Math, Reading, and Writing scores


🧰 Libraries Used

pandas 🐼 – for data manipulation

numpy 🔢 – for numerical operations

matplotlib 📊 – for static visualizations

seaborn 🌈 – for beautiful, statistical visualizations


📝 What the Notebook Covers

1. 🔍 Data Loading & Exploration

Loaded using pandas.read_csv

Explored with .info(), .describe(), .isnull(), .duplicated()



2. 🧹 Data Cleaning

Checked for missing or duplicate values

Verified data types and structure


3. 🧠 Key Insights

🎓 Test preparation significantly improves students’ average scores.

👨‍👩‍👧‍👦 Parental education level shows varying influence on student performance.

👩‍🔬 Gender-based analysis reveals interesting trends in subject-specific performance.

🔗 Strong correlation exists between reading and writing scores, indicating intertwined skills.


4. 📊 Group-wise Analysis

Compared average scores by gender and test preparation course

Used groupby() to uncover patterns



5. ➕ Feature Engineering

Created a new column: Average Score = mean of Math, Reading, and Writing



6. 📈 Visualizations

Count Plot: Gender Distribution

Bar Plot: Test Preparation vs Average Score

Box Plot: Math Score by Gender

Heatmap: Score Correlations

Scatter, Violin, and Bar plots for multi-angle insights



7. 📁 Output

All charts are saved in the ../Output/Charts/ directory for reporting


8. 📌 Conclusion

This project highlights how effective data loading, cleaning, and visualization can turn raw CSV files into powerful insights. Whether you're exploring academic trends or sharpening your data science skills, this notebook gives a solid foundation in pandas, seaborn, and real-world data storytelling. 📚✨



📸 Sample Visuals

Gendist.png: Gender distribution

TestvsAvg.png: Prep course impact on scores

genmath.png: Gender-wise math score spread

corr.png: Correlation heatmap


🚀 How to Run

# Install dependencies
pip install pandas numpy matplotlib seaborn

# Open notebook
jupyter notebook Data_loading.ipynb
