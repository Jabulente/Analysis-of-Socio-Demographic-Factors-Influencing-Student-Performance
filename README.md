<h1 align='center'>Survey-Based Analysis of Socio-Demographic Factors Influencing Student Performance</h1>

This project presents a comprehensive analysis of how various socio-demographic factors, collected through a structured survey, influence students’ academic performance in math, reading, and writing. Using Python, the project explores relationships between academic outcomes and categorical variables such as parental education, marital status, test preparation, weekly study hours, means of transport, ethnic group, and birth order (first child). The objective is to uncover statistically significant patterns that can guide educational policy, parental engagement, and student support services.

---

## 🧠 Objectives

1. **Explore socio-demographic variables** and their distribution among students.
2. **Identify patterns and relationships** between student performance and socio-demographic indicators using statistical and visual tools.
3. **Conduct statistical hypothesis testing**, including ANOVA and Tukey HSD, to evaluate the impact of categorical variables on academic scores.
4. **Generate actionable insights** that can be used by educators, institutions, and policymakers.

---

## 🗂️ Project Structure

```
📁 student-performance-analysis/
│
├── 📄 README.md
├── 📊 dataset/
│   └── student_survey_data.csv
│
├── 📂 notebooks/
│   ├── 01_data_cleaning_and_eda.ipynb
│   ├── 02_statistical_analysis.ipynb
│   └── 03_visualization_and_reporting.ipynb
│
├── 📂 scripts/
│   ├── data_loader.py
│   ├── stats_analysis.py
│   └── plotting_utils.py
│
├── 📈 outputs/
│   └── figures/
│       ├── boxplots.png
│       └── groupwise_comparisons.png
│
└── requirements.txt
```

---

## 📥 Dataset

The dataset is derived from a student survey and includes the following columns:

| Feature                   | Description                                 |
| ------------------------- | ------------------------------------------- |
| `gender`                  | Student gender                              |
| `ethnic_group`            | Student's ethnic background                 |
| `parental_education`      | Highest education level attained by parents |
| `marital_status`          | Marital status of parents                   |
| `test_preparation_course` | Completion status of test prep course       |
| `weekly_study_hours`      | Hours spent on studying weekly              |
| `means_of_transport`      | Main transport used by student to school    |
| `birth_order`             | Birth order (first child or not)            |
| `math_score`              | Math performance score                      |
| `reading_score`           | Reading performance score                   |
| `writing_score`           | Writing performance score                   |

---

## 🧪 Methods Used

* **Exploratory Data Analysis (EDA):**

  * Frequency distribution
  * Group-wise mean comparison
  * Correlation heatmaps

* **Statistical Testing:**

  * One-way ANOVA
  * Tukey’s Honest Significant Difference (HSD)
  * Compact Letter Display (CLD) for summarizing pairwise group differences

* **Visualization:**

  * Bar plots and box plots
  * Violin plots
  * Annotated statistical result plots (Tukey HSD output)

---

## 📊 Key Insights

* Students whose parents have higher education levels tend to perform better in reading and writing.
* Completion of a test preparation course is significantly associated with higher scores across all subjects.
* Birth order and ethnic group show nuanced but significant effects in specific subject areas.
* Means of transport and weekly study hours show potential as indirect predictors of academic success.

---

## 🛠️ Technologies Used

* **Python** (Pandas, NumPy, Matplotlib, Seaborn)
* **Statsmodels** – For ANOVA and Tukey’s HSD test
* **Scikit-learn** – For preprocessing and data encoding
* **Jupyter Notebook** – For prototyping and analysis

---

## 🚀 How to Run the Project

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/student-performance-analysis.git
   cd student-performance-analysis
   ```

2. **Create a virtual environment and install dependencies:**

   ```bash
   python -m venv venv
   source venv/bin/activate  # For Unix or Mac
   venv\Scripts\activate     # For Windows

   pip install -r requirements.txt
   ```

3. **Run the Notebooks:**

   Open `notebooks/01_data_cleaning_and_eda.ipynb` and run all cells in sequence.

---

## 📌 Recommendations

* **For Educators:** Tailor learning resources based on students’ home environments and provide extra support for those with less educated parents or who lack access to test prep.
* **For Policymakers:** Design interventions that target demographic groups shown to be at risk of underperforming.
* **For Parents:** Encourage consistent study habits and participate in test preparation opportunities offered by schools.

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋 Contact

For questions, suggestions, or contributions, feel free to contact:

<div align="center">  
    
[![GitHub](https://img.shields.io/badge/GitHub-Jabulente-black?logo=github)](https://github.com/Jabulente)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Jabulente-blue?logo=linkedin)](https://linkedin.com/in/jabulente-208019349)  [![Email](https://img.shields.io/badge/Email-jabulente@hotmail.com-red?logo=gmail)](mailto:Jabulente@hotmail.com)  

</div>
