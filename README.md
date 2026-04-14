# CADD Molecule Property Prediction

##  Overview
This project focuses on predicting molecular properties from SMILES strings using Machine Learning and RDKit. It demonstrates a basic Computer-Aided Drug Design (CADD) workflow by extracting molecular descriptors and applying regression models.

---

##  Objective
To build a machine learning model that predicts molecular properties from chemical structures represented as SMILES.

---

##  Tools & Technologies
- Python
- Pandas
- RDKit
- Scikit-learn

---

##  Workflow
1. Load dataset containing SMILES strings  
2. Validate molecules using RDKit  
3. Extract molecular descriptors:
   - Molecular Weight  
   - Number of Atoms  
   - Number of Bonds  
4. Create structured dataset  
5. Split data into training and testing sets  
6. Apply feature scaling  
7. Train a Linear Regression model  
8. Predict molecular properties  
9. Evaluate model performance  

---

##  Features Used
- Molecular Weight  
- Number of Atoms  
- Number of Bonds  

---

##  Model Used
- Linear Regression

---

##  Evaluation Metrics
- Mean Squared Error (MSE)  
- R² Score  

---

##  Project Structure

cadd-molecule-property-prediction/
│
├── data/
│ └── cadd.csv
│
├── notebook/
│ └── cadd_molecule_property_prediction.ipynb
│
├── README.md


---

##  Results
The model successfully learns relationships between molecular descriptors and predicts target properties with good performance on the test dataset.

---

##  Future Improvements
- Use larger and real-world molecular datasets  
- Add more RDKit descriptors  
- Try advanced models (Random Forest, XGBoost)  
- Build a Streamlit web application  
- Deploy the project  

---

##  Key Learning
- Understanding of SMILES and molecular structures  
- Feature extraction using RDKit  
- Machine Learning pipeline implementation  
- Model evaluation techniques  

---

##  Author
P.Divyadharshini
