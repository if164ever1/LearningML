# 🚀 ML & Data Science Learning Repository

> A comprehensive learning journey through Machine Learning and Data Science with Python

## 📚 Overview

Welcome to the **ML Data Science Bootcamp** repository! This project serves as a hands-on learning platform for mastering fundamental concepts in Data Science and Machine Learning using Python. Through practical exercises and real-world datasets, you'll build a solid foundation in data manipulation, analysis, and machine learning techniques.

---

## 🎯 Learning Objectives

By working through this repository, you will:

- ✅ Master **pandas** for data manipulation and analysis
- ✅ Understand **data cleaning** and missing data handling
- ✅ Perform **exploratory data analysis** (EDA)
- ✅ Learn **feature engineering** techniques
- ✅ Build practical **machine learning models**
- ✅ Work with **real-world datasets**
- ✅ Develop strong **Python programming skills**

---

## 📁 Repository Structure

```
ML_Data_Science_Bootcamp/
├── pandas-exercises.ipynb              # Core pandas practice exercises
├── Introduction_to_pandas.ipynb        # Pandas fundamentals guide
├── example_notebook.ipynb              # Example ML project templates
│
├── 📊 Datasets
│   ├── car-sales.csv                   # Clean car sales dataset
│   ├── car-sales-missing-data.csv      # Dataset with missing values
│   ├── car_sales_missing_dropped.csv   # Dataset after handling missing data
│   ├── heart-disease.csv               # Heart disease prediction dataset
│   ├── exported-car-sales.csv          # Exported processed data
│   └── cars_frame_test.csv             # Test dataframe output
│
├── env/                                # Python virtual environment
└── README.md                           # This file
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3.x** | Programming language |
| **Pandas** | Data manipulation & analysis |
| **NumPy** | Numerical computing |
| **Scikit-learn** | Machine learning algorithms |
| **Matplotlib/Seaborn** | Data visualization |
| **Jupyter Notebook** | Interactive coding & learning |

---

## 📖 Key Topics Covered

### 1. **Pandas Fundamentals**
- Creating Series and DataFrames
- Reading and exporting CSV files
- Data type inspection and conversion
- Column and row selection (.loc, .iloc)
- Data aggregation and grouping

### 2. **Data Cleaning & Preprocessing**
- Identifying missing values
- Handling missing data (filling, dropping)
- Data type conversion
- Column renaming and manipulation
- Data normalization

### 3. **Exploratory Data Analysis**
- Descriptive statistics (.describe(), .info())
- Data visualization (histograms, plots)
- Correlation analysis
- Crosstab analysis
- Groupby operations

### 4. **Data Transformation**
- Lambda functions for column operations
- String manipulation
- Creating new features
- Shuffling and resampling data
- Index management

### 5. **Real-World Datasets**
- **Car Sales Data**: Vehicle pricing, specifications, and usage patterns
- **Heart Disease Data**: Health metrics for disease prediction

---

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- pip or conda package manager
- Jupyter Notebook

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/if164ever1/LearningML.git
   cd LearningML/sample_project
   ```

2. **Create a virtual environment** (optional but recommended)
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install required packages**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```

4. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

5. **Open a notebook**
   - Navigate to `pandas-exercises.ipynb` to start with core exercises
   - Or open `Introduction_to_pandas.ipynb` for fundamentals

---

## 📝 Exercises & Notebooks

### 🎓 Pandas Exercises (`pandas-exercises.ipynb`)

A comprehensive collection of exercises covering:

| Exercise # | Topic | Concepts |
|------------|-------|----------|
| 1-5 | Series Creation | Creating and viewing pandas Series |
| 6-8 | DataFrame Operations | Combining Series, reading CSVs, exporting |
| 9-12 | Data Inspection | dtypes, describe(), info(), head(), tail() |
| 13-15 | Indexing | .loc, .iloc, column selection |
| 16-18 | Aggregation | mean(), sum(), groupby(), crosstab() |
| 19-20 | Visualization | Histograms, plots |
| 21-22 | String Operations | String manipulation, case conversion |
| 23-25 | Missing Data | Handling missing values, fillna(), dropna() |
| 26-30 | Feature Engineering | Creating columns, shuffling, dropping |
| 31-32 | Data Transformation | Lambda functions, renaming columns |

### 🏠 Introduction to Pandas (`Introduction_to_pandas.ipynb`)

Foundational guide covering:
- Pandas basics and data structures
- Essential methods and operations
- Best practices and tips

### 📂 Example Notebooks

Templates and examples for building your own projects.

---

## 💡 Key Pandas Methods Reference

### Data Selection
```python
df.loc[3]                          # Select row by label
df.iloc[3]                         # Select row by position
df["column_name"]                  # Select column
df[df["column"] > value]           # Boolean indexing
```

### Data Manipulation
```python
df.rename(columns={...})           # Rename columns
df.drop("column", axis=1)          # Drop column
df["new_col"] = values             # Add column
df.apply(lambda x: x/1.6)          # Apply function
```

### Data Cleaning
```python
df.fillna(value)                   # Fill missing values
df.dropna()                        # Drop missing values
df.dtypes                          # Check data types
```

### Data Analysis
```python
df.describe()                      # Statistical summary
df.info()                          # Dataset info
df.groupby("col").mean()           # Group and aggregate
pd.crosstab(df["col1"], df["col2"]) # Cross tabulation
```

---

## 📊 Sample Dataset: Car Sales

The repository includes a car sales dataset with the following features:

| Column | Description |
|--------|-------------|
| **Make** | Car manufacturer (Toyota, Honda, BMW, etc.) |
| **Colour** | Vehicle color |
| **Odometer (KM)** | Distance traveled in kilometers |
| **Doors** | Number of doors |
| **Price** | Vehicle price in USD |

**Use Cases:**
- Price prediction modeling
- Feature correlation analysis
- Data cleaning practice
- Aggregation and grouping exercises

---

## 🎯 Learning Path

```
Start Here
    ↓
Introduction_to_pandas.ipynb (Fundamentals)
    ↓
pandas-exercises.ipynb (Hands-on Practice)
    ↓
Data Cleaning & Feature Engineering
    ↓
Exploratory Data Analysis (EDA)
    ↓
Building ML Models (Next Phase)
    ↓
Real-World Projects
```

---

## 🔧 Tips for Success

1. **Run Each Cell**: Execute every cell and understand the output
2. **Experiment**: Modify code and see what happens
3. **Document**: Add comments explaining your understanding
4. **Practice**: Don't just read, code along actively
5. **Challenge Yourself**: Try variations of exercises
6. **Ask Questions**: Use print statements and .info() liberally

---

## 📚 Additional Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Jupyter Notebook Documentation](https://jupyter-notebook.readthedocs.io/)

---

## 🐛 Troubleshooting

### Common Issues

**Q: Import Error - pandas not found**
```bash
pip install pandas
```

**Q: Dataset not found**
- Ensure notebooks are in the same directory as CSV files
- Check file paths in your read_csv() statements

**Q: Jupyter kernel keeps dying**
```bash
pip install --upgrade jupyter ipykernel
python -m ipykernel install --user
```

**Q: Virtual environment not activating**
```bash
# Linux/Mac
source env/bin/activate

# Windows
env\Scripts\activate
```

---

## 📈 Progress Tracking

Track your progress through the bootcamp:

- [ ] Setup Python environment
- [ ] Install required packages
- [ ] Complete Introduction to Pandas
- [ ] Complete all pandas exercises
- [ ] Data cleaning exercises
- [ ] EDA on car-sales dataset
- [ ] EDA on heart-disease dataset
- [ ] Feature engineering practice
- [ ] Build first ML model
- [ ] Document learnings in portfolio

---

## 🤝 Contributing

This is a personal learning repository, but feel free to:
- Create your own branches for experiments
- Document your learning process
- Share insights in markdown files

---

## 📄 License

This repository is for educational purposes.

---

## 🎓 About This Bootcamp

This ML & Data Science Bootcamp is designed for learners who want to:
- Build strong foundations in data manipulation
- Understand data science workflows
- Transition to machine learning
- Develop professional coding practices

**Remember**: Consistency is more important than intensity. Code a little bit every day! 💪

---

## 📞 Questions & Support

- Refer to the official documentation links above
- Check Jupyter notebooks for inline comments
- Experiment with datasets independently
- Build projects to reinforce learning

---

**Happy Learning! 🚀 Let's master Data Science together!**

---

*Last Updated: January 2026*
*Repository: [LearningML](https://github.com/if164ever1/LearningML)*
