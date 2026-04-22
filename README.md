# **Student-Exam-Performance-Analysis**

A data analysis project that explores how various demographic and socioeconomic factors influence student performance in Math, Reading, and Writing exams — using Python for end-to-end data cleaning, analysis, and visualization.

📌 **Overview**

This project performs exploratory data analysis (EDA) on the Students Performance in Exams dataset from Kaggle. It uncovers patterns related to gender, parental education level, and academic scores — and exports a filtered dataset of high-achieving students for further use.

🔍 **Key Findings**

Gender differences exist in average Math, Reading, and Writing scores

Parental level of education has a measurable impact on student math performance

Reading and Writing scores are strongly positively correlated

Students scoring above 80 in Math form a distinct high-performing group

A filtered export of students scoring above 90 in Math is saved for downstream analysis

🛠️ **Tech Stack**

Python --> Core programming language

Pandas --> Data loading, cleaning, filtering, and aggregation

NumPy --> Numerical operations

Matplotlib --> Histograms and scatter plots

Seaborn --> Boxplots, bar charts, and heatmaps

📊 **Visualizations Included**

Histogram — Distribution of Math scores across all students

Boxplot — Outlier detection in Reading scores

Scatter Plot — Relationship between Reading and Writing scores

Bar Chart — Average Math score grouped by gender

Correlation Heatmap — Correlation between Math, Reading, and Writing scores

🗂️** Project Structure**

student-performance-analysis/

├── project1.ipynb               # Main Jupyter Notebook

├── exams.csv                    # Raw dataset (input)

└── high_math_students.csv       # Filtered output (Math score > 90)
