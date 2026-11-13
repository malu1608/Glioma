# Glioma Grade Classification

Predicting whether a brain tumour is **lower-grade glioma (LGG)** or **glioblastoma (GBM)**, the most aggressive grade, from clinical and genetic mutation data (UCI *Glioma Grading Clinical and Mutation Features* dataset).

## What we did
- **Exploratory analysis** by age and sex, for example how GBM rates change above and below 50
- **Feature engineering**, such as grouping age into young, adult and elderly
- **Correlation analysis** and aggregation of highly correlated features (|r| > 0.8)
- **Model comparison:** Decision Tree, k-Nearest Neighbours and SVM, with classification reports for each

## Files
| File | What it contains |
|---|---|
| `Assignment2/src/Project.ipynb` | Full analysis and models |
| `Assignment2/src/reports/` | Classification reports |
| `Final Checkpoint.pptx` | Final presentation |

## Stack
Python · pandas · scikit-learn · matplotlib · seaborn · Jupyter

---
Academic project developed at FEUP (Faculty of Engineering, University of Porto), Artificial Intelligence 2022/23.
