# SpaceX
Summary
Predict SpaceX launch price & first stage reuse using ML.

Solution
 

Analyzed SpaceX launch data to predict first-stage rocket reusability, a key factor in cost reduction. Employed four machine learning models—KNN, SVM, Logistic Regression, and Decision Tree—optimizing each with GridSearchCV for maximum accuracy. The best-performing model can help determine launch costs.


Approach
 

Data Prep: Loaded, explored, scaled data. Split into train/test sets.

Model Train: Trained 4 models (LR, SVM, DT, KNN) using GridSearchCV.

Evaluation: Compared models using accuracy, precision, recall & F1.

Best Model: Selected top-performing model for reuse prediction.

Pricing Model: Developed pricing using features like payload & reuse.

Visualized: Compared models with a bar chart


