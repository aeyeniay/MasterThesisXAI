# Master Thesis: XAI Applications Based on Vehicle Characteristics

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Models Used](#models-used)
- [Explainable AI Methods](#explainable-ai-methods)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
This project aims to estimate carbon emissions based on vehicle characteristics using the Fuel Consumption Ratings datasets created by Natural Resources Canada. By employing various classical machine learning models and explainable artificial intelligence (XAI) methods, the study seeks to understand the key vehicle features influencing emissions and provide insights for decision-makers.

## Dataset
The datasets used in this study were created by Natural Resources Canada, an institution of the Canadian government. They include detailed information on fuel consumption ratings for various vehicle models.

## Installation
To run this project, you will need to install the required Python libraries. You can do this by installing the necessary libraries individually:

```bash
pip install pandas numpy scikit-learn shap lime alibi matplotlib seaborn
```
## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/aeyeniay/MasterThesisXAI
   cd MasterThesisXAI
   ```
   
2. Install the required packages:
   ```bash
   pip install pandas numpy scikit-learn shap lime alibi matplotlib seaborn 
   ```
3. Run the Jupyter notebook:
   ```bash
   jupyter notebook
   ```
4. Open the XAI_applications.ipynb notebook and follow the instructions to run the code cells.
  
## Models Used
The following machine learning models were used in this study:

- Random Forest
- Gradient Boosting
- Support Vector Regression (SVR)

## Explainable AI Methods
The following XAI methods were used to interpret the model predictions:

- SHAP (SHapley Additive exPlanations)
- LIME (Local Interpretable Model-agnostic Explanations)
- ALIBI (integrating Tree SHAP)

## Results
The models were evaluated using metrics such as Mean Squared Error (MSE), R-squared (R2), Mean Absolute Error (MAE), Explained Variance Score (EVS), and Root Mean Squared Error (RMSE). Combined Fuel Consumption emerged as the most significant feature influencing emissions. The XAI methods provided detailed insights into the positive and negative impacts of features on emissions, with LIME and SHAP (beeswarm plots) being the most effective in providing clear explanations.

## Conclusion
The study demonstrated that LIME and SHAP (using beeswarm plots) are the most effective XAI methods for providing clear and informative explanations for decision-makers. These methods allow for a better understanding of the factors driving carbon emissions, aiding in the development of strategies to reduce vehicle emissions.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
If you have any questions or suggestions, feel free to contact me at [aeyeniay@gmail.com].
