# Bankruptcy_prediction

## Bankruptcy Prediction Project

## Project Overview
This project is focused on predicting bankruptcy risk using machine learning techniques. The model was developed to analyze financial data and help organizations assess the probability of bankruptcy for a given entity. The primary model, **AdaBoost**, was selected for deployment after a thorough comparison with several other classifiers. The project also includes insights into feature importance, model performance, and visualization techniques.

## Project Structure
- **Dataset**: Contains the data used to train and evaluate the model.
  - `Bankruptcy Prediction.csv`: Dataset with financial indicators related to bankruptcy risk.
- **Code**: Jupyter notebook with all steps from data processing to model evaluation and selection.
  - `project(Bankruptcy).ipynb`: Code notebook implementing data preprocessing, feature engineering, model comparison, and evaluation.
- **Deployment**: Code and links for deploying the model.
  - `deployment link.url`: Direct link to the live deployment on Streamlit.
  - `Project2_exeler.zip`: Deployment scripts and additional configurations.
- **Presentation**: PowerPoint presentation explaining the project, methodology, and results.
  - `Bankruptcy-Prediction-Model (2).pptx`: Detailed project presentation.
- **Demo Video**: Video demo showcasing the functionality and deployment of the model.
  - `project video.mp4`: Visual walkthrough of the project, including model insights and the deployed web app.

## Key Features
- **Data Preprocessing**: Handled outliers, missing values, and scaling.
- **Model Selection**: Compared various machine learning models (Logistic Regression, Decision Tree, Random Forest, SVC, KNN, Naive Bayes, AdaBoost, Gradient Boosting, XGBoost, Voting Classifier, LightGBM) based on accuracy, AUC-ROC, and precision.
- **Visualization**: ROC curves for model performance, feature importance plots, and other visual insights.
- **Deployment**: The AdaBoost model was deployed using Streamlit for real-time predictions accessible online.

## Installation
1. Clone the repository:
   ```bash
   git deepikareddy2107 https://github.com/yourusername/bankruptcy-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bankruptcy-prediction
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Run the Notebook**: Start `project(Bankruptcy).ipynb` to explore data processing, model training, and evaluation.
2. **View the Deployment**: Open the Streamlit deployment at [Bankruptcy Prediction App](https://bankruptcyriskprediction-lvmajggzc3styhkpgai62h.streamlit.app/).
3. **Watch the Demo**: The video `project video.mp4` offers a walkthrough of the model’s features and the web application.

## Results
The best model, **AdaBoost**, achieved high performance across several metrics, making it well-suited for deployment. Key insights on feature importance and decision-making support are presented in the PPT file and the notebook.

## Resources
- **Dataset**: [Bankruptcy Prediction.csv](data/Bankruptcy%20Prediction.csv)
- **Model Deployment**: [Streamlit Link](https://bankruptcyriskprediction-lvmajggzc3styhkpgai62h.streamlit.app/)
- **Demo Video**: Accessible in the repository as `project video.mp4`

## License
This project is licensed under the MIT License.

---

Feel free to replace `yourusername` in the GitHub clone command with your GitHub username. This README should now align with your project’s structure and goals, making it easy for others to navigate and understand your work.
