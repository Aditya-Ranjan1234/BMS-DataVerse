# Dataverse: Energy Efficiency Analysis  

## Project Overview  
Dataverse is an 8-hour datathon organised by BMSCE, Bangalore where participants analyze data from energy audits to identify inefficiencies and suggest improvements. Our team aimed to build a machine learning model that predicts the Energy Efficiency Rating of buildings and provide actionable recommendations for reducing energy wastage. This aligns with SDG-7: Clean and Affordable Energy.  

### Key Goals  
- **Predict Energy Efficiency:** Use machine learning models to classify buildings into energy efficiency rating categories (A, B, C, D).  
- **Identify Inefficiencies:** Highlight buildings with high energy consumption or inefficiencies.  
- **Generate Insights:** Provide actionable recommendations for improving energy efficiency, such as reducing peak hour consumption or improving insulation.  

## Team Members  
- **Aditya Ranjan**  
- **Gnanendra Naidu N**  

## Tools & Techniques  
1. **Data Preprocessing:** Cleaning, handling missing values, normalization, and feature engineering.  
2. **Machine Learning Models:**  
   - Best Results:  
     - K-Nearest Neighbors  
     - Linear Discriminant Analysis  
     - Ridge Classifier  
     - XGBoost  
   - Suggestion Models:  
     - Qwen 32B  
     - GPT-4.0  

3. **Evaluation Metric:** F1-Score to balance precision and recall across energy efficiency ratings.  

## Results  
- **Best Results Models:**  
  1. K-Nearest Neighbors  
  2. Linear Discriminant Analysis  
  3. Ridge Classifier  
  4. XGBoost  

- **Position:** Our team secured **Third Place** in the competition.  

## Key Insights  
- **Correlation Analysis:**  
  Explored relationships between energy consumption, renewable usage, peak hours, floor area, and occupants.  
- **Actionable Recommendations:**  
  - Reduce peak hour consumption.  
  - Improve insulation for buildings with high energy inefficiency.  
  - Increase renewable energy utilization.  

## Files in the Repository  
1. **BMS_Datathon_Dataverse.ipynb:** Implementation of multiple ML models and suggestions using LLMs.  
2. **Analysis_Correlation.ipynb:** Detailed analysis of correlations between features.  
3. **Dataverse.ipynb:** Refinement of models by dropping less impactful parameters like floor area.  

## License  
This project is licensed under the GNU General Public License v3.0.   
