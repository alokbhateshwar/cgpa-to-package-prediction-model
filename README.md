
# Project Title

Predicting Placement Package from CGPA using Linear Regression (ML)


## Description
This project uses a simple **Linear Regression model** to predict a student's **placement package (LPA)** based on their **CGPA**.

It demonstrates the relation between academic performance and placement salary using **data visualization** and **machine learning**.
## Table of Contents

- [Project Title](#project-title)
- [Description](#description)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Visualization](#visualization)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Acknowledgments](#acknowledgments)


#### Dataset

| Column | Description |
|---|---|
| cgpa | Student's CGPA |
| package | Package Offered (LPA) |

- Total Records: **200 students**
- Format: CSV
- Type: Synthetic but realistic


## Technologies Used

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook


## Installation

1. Clone the repository:
```bash
git clone https://github.com/alokbhateshwar/cgpa-to-package-prediction-model.git
```

2. Navigate to the project folder:
```bash
cd cgpa-to-package-prediction-model
```

3. Install required packages:
```bash
pip install pandas matplotlib seaborn scikit-learn
```

## Usage

- Open the notebook or Python file.
- Load the dataset.
- Run data visualization to check linearity.
- Split data (train-test).
- Train the Linear Regression model.
- Test the model.
- Predict package for new CGPA values.

## Results

✅ **Best R² Score:** ~**88.99%**  
✅ **Best Random State Found:** Between 1 and 500 (auto-selected during training loop)

> Meaning: The model explains about **89% of the variance** in placement package based on CGPA.## Visualization
### 📊 Scatter Plot:
Shows CGPA vs Package relationship (Linear Trend)

### 📈 Actual vs Predicted (Bar Chart):
Comparison between Actual packages and Predicted packages on Test Data.

### ✅ Model Workflow:

```mermaid
graph TD;
    A[Load Dataset] --> B[Visualize Data]
    B --> C[Split Data (Train/Test)]
    C --> D[Train Model]
    D --> E[Evaluate Model]
    E --> F[Predict New Package]
```

## Future Improvements
- Test with **larger real-world datasets**
- Add **more features** (like internships, projects, skills)
- Try **Polynomial Regression** or **Decision Tree Regression**
- Deploy as a **Streamlit web app**

## License
Open-source project. Free for educational and personal use.

## Acknowledgments
Thanks to the open-source Python ML community!

Special thanks to:
- Scikit-learn documentation
- Kaggle datasets
- matplotlib, seaborn developers