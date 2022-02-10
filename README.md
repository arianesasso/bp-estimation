# Thesis

This repository relates to the following chapter of my thesis:

**Evaluating Machine Learning Models for Blood Pressure Estimation from PPG Data Beyond Intensive Care**

----
For running the notebooks:

```
pipenv install
pipenv shell
pipenv run jupyter notebook
```

The notebooks in `features` process raw PPG data and predict blood pressure for 3 different datasets:

`HYPE`: extract_features_and_predict_bp_from_ppg_hype.ipynb

`EVAL`: extract_features_and_predict_bp_from_ppg_eval.ipynb

`LIANG`: extract_features_and_predict_bp_from_ppg_liang.ipynb

For the code related to secion `3.4` please refer to this repository:
[PPG-to-BP-Prediction-convnets](https://github.com/suparno89/PPG-to-BP-Prediction-convnets)

For the analysis related to `section 4` (results), you can use the notebooks under `analysis`:

`4.1`: hype_analysis.ipynb

`4.2, 4.3 and 4.4`: hype_analysis.ipynb

# Datasets Information

**EVAL**: https://www.kaggle.com/mkachuee/noninvasivebp (original)

However, we processed it and used the following file as the input to our notebook: https://doi.org/10.6084/m9.figshare.12649691


**HYPE**: Available to the scientific community through a data agreement. Please fill in the following form: https://forms.gle/M8DDtuMeWGfT3k4y5

**LIANG**: [http://www.nature.com/articles/sdata201820](http://www.nature.com/articles/sdata201820)
