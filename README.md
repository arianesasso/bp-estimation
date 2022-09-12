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

For further analysis, you can use the notebooks under `analysis`.

# Datasets Information

**EVAL**: https://www.kaggle.com/mkachuee/noninvasivebp (original)

However, I processed it and used the following file as the input to the notebook: https://doi.org/10.6084/m9.figshare.12649691


**HYPE**: Available to the scientific community through a data agreement. Please fill in the following form: https://forms.gle/M8DDtuMeWGfT3k4y5

**LIANG**: [http://www.nature.com/articles/sdata201820](http://www.nature.com/articles/sdata201820)
