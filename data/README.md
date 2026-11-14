# Data

`processed.cleveland.data` is the processed Cleveland subset of the Heart
Disease dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease). It has 303 patient records and 14 columns.

## Variables

| Column | Description |
|--------|-------------|
| age | Age in years |
| sex | 1 = male, 0 = female |
| cp | Chest pain type (1 to 4) |
| trestbps | Resting blood pressure (mm Hg) |
| chol | Serum cholesterol (mg/dl) |
| fbs | Fasting blood sugar above 120 mg/dl (1 = true) |
| restecg | Resting ECG results (0 to 2) |
| thalach | Maximum heart rate achieved |
| exang | Exercise-induced angina (1 = yes) |
| oldpeak | ST depression induced by exercise relative to rest |
| slope | Slope of the peak exercise ST segment |
| ca | Number of major vessels coloured by fluoroscopy (0 to 3) |
| thal | Thalassemia result (3 = normal, 6 = fixed defect, 7 = reversible defect) |
| target | Diagnosis of heart disease, from 0 (none) to 4 |

The target is not used during clustering. It is used only at the end, as a
binary label (0 = no disease, 1 to 4 = disease), to evaluate the clusters.