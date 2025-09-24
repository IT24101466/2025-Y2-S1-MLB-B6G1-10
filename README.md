# Lung Cancer Classification Preprocessing Pipeline

## Project Overview
This project implements a preprocessing pipeline. The Jupyter Notebook (`group_pipeline.ipynb`) processes a synthetic lung cancer dataset through stages including missing value handling, encoding, outlier removal, feature engineering, class balancing, normalization, feature selection, and PCA. The pipeline is designed to meet the 5-mark requirement for integration, logical flow, and collaboration evidence.

## Dataset Details
- **File**: `lcs_synthetic_20000.csv`
- **Description**: A synthetic dataset with 20,000 rows containing features 'GENDER', 'AGE', 'SMOKING', 'YELLOW_FINGERS', 'ANXIETY', 'PEER_PRESSURE', 'CHRONIC DISEASE', 'FATIGUE ', 'ALLERGY ', 'WHEEZING', 'ALCOHOL CONSUMING', 'COUGHING', 'SHORTNESS OF BREATH', 'SWALLOWING DIFFICULTY', 'CHEST PAIN', 'LUNG_CANCER' used to simulate lung cancer classification scenarios.

## Group Member Roles
- **IT24101397 Wickramasinghe W.A.P.J.S.D**: Encoding
- **IT24101291 Vidya .R**: Outlier Removal
- **IT24101347 Madushanka E D**: Feature Engineering
- **IT24101466 Akeeth W K A**: Balancing and Normalization
- **IT24101461 Hannadige A. K. L. F.**: Feature Selection
- **IT24103547 Oshadi J.A.A.**: PCA

## How to Run the Code
1. **Prerequisites**:
   - Python 3.x
   - Jupyter Notebook
   - Required libraries: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `imbalanced-learn`

2. **Installation**:
   - Clone the repository 
   - Install dependencies:
     ```bash
     pip install pandas matplotlib seaborn scikit-learn imbalanced-learn
3.. **Execution**:
   - Open `group_pipeline.ipynb` in Jupyter Notebook
   - Run all cells sequentially to execute the pipeline.
 
