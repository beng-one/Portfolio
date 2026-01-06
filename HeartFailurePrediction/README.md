Heart Failure Prediction est un projet académique qui porte sur le développement d'une méthode de scoring utilisée pour prédire le décès d'un patient souffrant d'insuffisance cardiaque. 
Les modèles de scoring proposés sont issus de la thérorie d'apprentissage statistique. 

On retrouve des :
**Modèles d'apprentissage automatique non supervisé :** 
  - Classification Ascendante Hierarchique
  - K-Means
  - L'algorithme du plus proche voisin (KNN)
**Modèles d'apprentissage automatique supervisé :**
  - Arbre de décision
  - Analyse Discriminante
  - Random Forest
  - SVM

Quelques Résultats
==================

Statistic summary
==========================================================================
Statistic                 N     Mean      St. Dev.     Min         Max    
--------------------------------------------------------------------------
age                      299   60.834      11.895     40.000     95.000   
anaemia                  299    0.431      0.496        0           1     
creatinine_phosphokinase 299   581.839    970.288       23        7,861   
diabetes                 299    0.418      0.494        0           1     
ejection_fraction        299   38.084      11.835       14         80     
high_blood_pressure      299    0.351      0.478        0           1     
platelets                299 263,358.000 97,804.240 25,100.000 850,000.000
serum_creatinine         299    1.394      1.035      0.500       9.400   
serum_sodium             299   136.625     4.412       113         148    
sex                      299    0.649      0.478        0           1     
smoking                  299    0.321      0.468        0           1     
time                     299   130.261     77.614       4          285    
DEATH_EVENT              299    0.321      0.468        0           1     
--------------------------------------------------------------------------

Scatter plot
==============
<img width="770" height="475" alt="1" src="https://github.com/user-attachments/assets/ce1d6bb1-f9b4-4795-a0f4-dd80a66d3510" />

Correlation Matrix
==================
<img width="1920" height="1152" alt="2" src="https://github.com/user-attachments/assets/530d3d78-2c7a-40cf-b111-3aa058565632" />

Random Forest Error plot
=======================
<img width="770" height="475" alt="3" src="https://github.com/user-attachments/assets/9ae9cfbb-95d6-4b36-ad02-81b1643cd26f" />
