# Data Science & Machine Learning Course

A step-by-step course in Jupyter notebooks, from Python basics to machine learning.

Start with **[Topic_00_All_Topics_Index.ipynb](Topic_00_All_Topics_Index.ipynb)** — every section of every lesson, with links.

## How the course is organised

Each topic has its own folder with two notebooks:

| Notebook | What's inside |
|---|---|
| `Topic_XX_Lesson.ipynb` | 📖 Explanations, worked examples, cheat sheet |
| `Topic_XX_Practice_Solutions.ipynb` | ✍️ Every practice problem → your answer cell → ✅ the solution right below it, plus the projects |

Read the lesson first, then work through the practice notebook.
After every 5 topics, take the **🎯 quiz** in the `Quiz_*` folder — 20 multiple-choice questions and 5 coding tasks, all checked automatically. Answers and solutions are in a separate `Quiz_N_Solutions.ipynb` next to each quiz.

The practice notebook's first code cell runs the lesson
in the background, so all the data and variables the problems use are ready.

## Lessons

| # | Topic | Lesson | Practice |
|---|---|---|---|
| 01 | Python Basics | [Lesson](Topic_01_Python_Basics/Topic_01_Lesson.ipynb) | [Practice & Solutions](Topic_01_Python_Basics/Topic_01_Practice_Solutions.ipynb) |
| 02 | Pandas DataFrame Basics | [Lesson](Topic_02_Pandas_DataFrame_Basics/Topic_02_Lesson.ipynb) | [Practice & Solutions](Topic_02_Pandas_DataFrame_Basics/Topic_02_Practice_Solutions.ipynb) |
| 03 | Handling Missing Values | [Lesson](Topic_03_Handling_Missing_Values/Topic_03_Lesson.ipynb) | [Practice & Solutions](Topic_03_Handling_Missing_Values/Topic_03_Practice_Solutions.ipynb) |
| 04 | Normalization & Standardization | [Lesson](Topic_04_Normalization_Standardization/Topic_04_Lesson.ipynb) | [Practice & Solutions](Topic_04_Normalization_Standardization/Topic_04_Practice_Solutions.ipynb) |
| 05 | Detecting & Treating Outliers | [Lesson](Topic_05_Outliers/Topic_05_Lesson.ipynb) | [Practice & Solutions](Topic_05_Outliers/Topic_05_Practice_Solutions.ipynb) |
| 🎯 | 🎯 Quiz 1 — Topics 01–05 | [Quiz 1](Quiz_1_Topics_01-05/Quiz_1.ipynb) | 20 MCQ + 5 coding tasks · [✅ Solutions](Quiz_1_Topics_01-05/Quiz_1_Solutions.ipynb) |
| 06 | Encoding Techniques | [Lesson](Topic_06_Encoding_Techniques/Topic_06_Lesson.ipynb) | [Practice & Solutions](Topic_06_Encoding_Techniques/Topic_06_Practice_Solutions.ipynb) |
| 07 | Exploratory Data Analysis (EDA) | [Lesson](Topic_07_Exploratory_Data_Analysis/Topic_07_Lesson.ipynb) | [Practice & Solutions](Topic_07_Exploratory_Data_Analysis/Topic_07_Practice_Solutions.ipynb) |
| 08 | Data Visualization | [Lesson](Topic_08_Data_Visualization/Topic_08_Lesson.ipynb) | [Practice & Solutions](Topic_08_Data_Visualization/Topic_08_Practice_Solutions.ipynb) |
| 09 | Pandas Data Manipulation | [Lesson](Topic_09_Pandas_Data_Manipulation/Topic_09_Lesson.ipynb) | [Practice & Solutions](Topic_09_Pandas_Data_Manipulation/Topic_09_Practice_Solutions.ipynb) |
| 10 | Combining DataFrames | [Lesson](Topic_10_Combining_DataFrames/Topic_10_Lesson.ipynb) | [Practice & Solutions](Topic_10_Combining_DataFrames/Topic_10_Practice_Solutions.ipynb) |
| 🎯 | 🎯 Quiz 2 — Topics 06–10 | [Quiz 2](Quiz_2_Topics_06-10/Quiz_2.ipynb) | 20 MCQ + 5 coding tasks · [✅ Solutions](Quiz_2_Topics_06-10/Quiz_2_Solutions.ipynb) |
| 11 | Feature Engineering | [Lesson](Topic_11_Feature_Engineering/Topic_11_Lesson.ipynb) | [Practice & Solutions](Topic_11_Feature_Engineering/Topic_11_Practice_Solutions.ipynb) |
| 11b | KBinsDiscretizer (Discretization) | [Lesson](Topic_11b_KBinsDiscretizer/Topic_11b_Lesson.ipynb) | [Practice & Solutions](Topic_11b_KBinsDiscretizer/Topic_11b_Practice_Solutions.ipynb) |
| 12 | Correlation & Multicollinearity | [Lesson](Topic_12_Correlation_Multicollinearity/Topic_12_Lesson.ipynb) | [Practice & Solutions](Topic_12_Correlation_Multicollinearity/Topic_12_Practice_Solutions.ipynb) |
| 13 | Data Transformation & Skewness | [Lesson](Topic_13_Data_Transformation_Skewness/Topic_13_Lesson.ipynb) | [Practice & Solutions](Topic_13_Data_Transformation_Skewness/Topic_13_Practice_Solutions.ipynb) |
| 14 | Statistics for Data Science | [Lesson](Topic_14_Statistics_for_Data_Science/Topic_14_Lesson.ipynb) | [Practice & Solutions](Topic_14_Statistics_for_Data_Science/Topic_14_Practice_Solutions.ipynb) |
| 🎯 | 🎯 Quiz 3 — Topics 11–14 | [Quiz 3](Quiz_3_Topics_11-14/Quiz_3.ipynb) | 20 MCQ + 5 coding tasks · [✅ Solutions](Quiz_3_Topics_11-14/Quiz_3_Solutions.ipynb) |
| 15 | Probability for Data Science & ML | [Lesson](Topic_15_Probability_for_Data_Science_ML/Topic_15_Lesson.ipynb) | [Practice & Solutions](Topic_15_Probability_for_Data_Science_ML/Topic_15_Practice_Solutions.ipynb) |
| 16 | Feature Selection | [Lesson](Topic_16_Feature_Selection/Topic_16_Lesson.ipynb) | [Practice & Solutions](Topic_16_Feature_Selection/Topic_16_Practice_Solutions.ipynb) |
| 17 | Machine Learning | [Lesson](Topic_17_Machine_Learning/Topic_17_Lesson.ipynb) | [Practice & Solutions](Topic_17_Machine_Learning/Topic_17_Practice_Solutions.ipynb) |
| 🎯 | 🏁 Final Quiz — Topics 15–17 | [Quiz 4](Quiz_4_Topics_15-17/Quiz_4.ipynb) | 20 MCQ + 5 coding tasks · [✅ Solutions](Quiz_4_Topics_15-17/Quiz_4_Solutions.ipynb) |

## Data

Datasets live in [`data/`](data); notebooks read them as `../data/...` from inside their topic folder.

- `winequality-red.csv` — red-wine quality (Topics 2, 4, 7, 16)
- `customer_sales_dirty.csv` / `customer_sales_clean.csv` — data-cleaning workflow (Topic 2)
- `sales_data.csv` — missing-value practice (Topic 3)
- `HR_comma_sep (1).csv` — HR employee dataset

## Requirements

Python 3 with `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`, `scikit-learn` and `jupyter`.
Open notebooks from inside their topic folder so the `../data/...` paths resolve.
