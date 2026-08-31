# Analiza danych Titanic

Projekt analityczny wykorzystujący klasyczny zbiór danych Titanic do:
- eksploracji i czyszczenia danych
- wizualizacji kluczowych zależności (płeć, klasa, przeżywalność)
- budowy modeli klasyfikacyjnych przewidujących przeżycie pasażerów

## Dane
Zbiór danych Titanic (Kaggle), 891 pasażerów, 12 cech.

## Główne wnioski
- Płeć jest najsilniejszym predyktorem przeżycia (test chi-kwadrat, p≈10^-58)
- Wyższa klasa pasażerska wiązała się z wyższą przeżywalnością
- Model regresji logistycznej (Age, Pclass, płeć, cena biletu) osiąga ~80% dokładności

## Wykorzystane narzędzia
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, SciPy
