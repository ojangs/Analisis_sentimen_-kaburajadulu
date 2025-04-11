# Analisis_sentimen_kaburajadulu
Analisis sentimen menggunakan algoritma RandomForest

NOTE : MODEL TIDAK SEMPURNA

tuning yang dilakukan

param_grid = {
    'n_estimators': [100],
    'max_depth': [None, 500],
    'min_samples_split': [5,10],
    'max_features': ['sqrt',0.2],
    'class_weight': ['balanced']
}
