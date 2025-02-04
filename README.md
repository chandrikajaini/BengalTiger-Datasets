# BengalTiger-Datasets
Training and Testing datasets
# Bengal Tiger Datasets

This repository contains two datasets related to Bengal Tigers: one for training and another for testing. These datasets can be used for machine learning models, such as Random Forest and Decision Trees, to predict the survival chances of Bengal tigers based on various attributes.

## Dataset Files

### 1. `BT_training_dataset.csv` (Training Data)
Download: https://drive.google.com/file/d/1i__wEpVlZftdpFNwTZbGhuTXjjAR0odm/view?usp=drive_link
- **Records:** 35
- **Description:** This dataset contains 35 records with different characteristics of Bengal tigers. It can be used for training predictive models.
- **Columns:**
  - `Age`: Age of the tiger (in years)
  - `Weight`: Weight of the tiger (in kg)
  - `Height`: Height of the tiger (in meters)
  - `Speed`: Speed of the tiger (in km/h)
  - `Claw_Length`: Claw length of the tiger (in cm)
  - `Region`: The habitat where the tiger is found (Sundarbans, Nepal, Assam, Bangladesh)
  - `Gender`: Male or Female
  - `Health_Status`: Health condition of the tiger (Healthy, Injured, Sick)
  - `Prey_Success_Rate`: Success rate of hunting (range from 0.3 to 0.9)
  - `Survival_Chance`: Target variable indicating the likelihood of survival (High, Medium, Low)

### 2. `BT_testing_dataset.csv` (Testing Data)
Download: https://drive.google.com/file/d/1noVZcPB03CFAnmMb0UZ1G9r_1qqknkT4/view?usp=drive_link
- **Records:** 10
- **Description:** This dataset contains 10 new records and can be used for evaluating model performance. It does not include any records from the training dataset.
- **Columns:**
  - `Age`, `Weight`, `Height`, `Speed`, `Claw_Length`, `Region`, `Gender`, `Health_Status`, `Prey_Success_Rate`, `Survival_Chance`
  - These columns are the same as in the training dataset.

## Modifications
- Removed columns `Territory_Size` and `Human_Conflict` to focus on other features.

## Usage
1. **Download the datasets** from this repository.
2. **Use `bengal_tiger_dataset.csv`** to train your machine learning models.
3. **Use `BT_testing.csv`** to evaluate model accuracy and performance.

## License
This dataset is available for public use. Feel free to use it for research, educational, and non-commercial purposes.

## Contributions
If you want to contribute by adding more data or improving the dataset, feel free to create a pull request or open an issue.

---
For any queries, contact the repository owner. Happy analyzing! 🐅

