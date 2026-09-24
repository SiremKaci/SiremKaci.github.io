# Sirem Kaci

I’m an early-career data scientist working with Python, statistical analysis and machine learning. I like projects that start with messy, real-world data and require more than fitting a model: checking what the records mean, building a sound evaluation, and making the findings understandable.

I’m looking for a data science role where I can contribute across the full workflow, from data exploration to modeling and communication.

## Selected projects

### Canadian rental price prediction

Predicting residential rents across Canada. Repeated listing IDs revealed a risk of data leakage, so I changed the validation strategy to evaluate on **unseen listing groups**. The reported holdout result is **CAD 251 MAE** and **0.637 R²**.

`Python` · `pandas` · `scikit-learn` · `GitHub Actions`

### Los Angeles crime analysis

Analyzing **982,638 LAPD crime records** through data auditing, statistical exploration and interactive maps. I developed the work into a modular pipeline that also compares models for multiclass crime classification. The project connects the geographic and temporal patterns in the data with the limits of what can be predicted from the available records.

`Python` · `pandas` · `Folium` · `CatBoost`

### Glaucoma detection from retinal images

Classifying retinal fundus images with **ConvNeXt-Tiny** and transfer learning. The pipeline includes image preprocessing, augmentation and progressive fine-tuning. It reports **97.15% ROC-AUC** on the test set, alongside sensitivity and F1 to describe performance beyond a single metric.

`PyTorch` · `OpenCV` · `Albumentations`

## Other projects

- **Credit card fraud detection:** imbalanced classification with XGBoost, resampling comparisons and evaluation on a test set retaining the original class distribution.
- **Hepatitis survival analysis:** statistical tests and a comparison of classification models using clinical data.
