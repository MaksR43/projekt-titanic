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


## Dlaczego kontrola wersji i dobra struktura projektu mają znaczenie

Na studiach Data Science będę regularnie oddawał projekty i zadania, które
prowadzący będzie musiał uruchomić na SWOIM komputerze — często zupełnie
innym środowisku niż moje. Git i dobra struktura projektu rozwiązują kilka
konkretnych problemów:

1. **Odtwarzalność** — requirements.txt gwarantuje, że ktoś inny może
   zainstalować DOKŁADNIE te same wersje bibliotek, których użyłem, unikając
   sytuacji "u mnie działa, u niego nie" wynikającej z różnic w wersjach.

2. **Historia i bezpieczeństwo eksperymentowania** — dzięki commitom mogę
   swobodnie wprowadzać zmiany, wiedząc, że zawsze mogę wrócić do wcześniejszej,
   działającej wersji, jeśli coś zepsuję.

3. **Czytelność dla innych (i dla mnie za miesiąc)** — README.md i uporządkowana
   struktura folderów pozwalają szybko zrozumieć, co robi projekt, bez
   konieczności czytania całego kodu od zera.

4. **.gitignore** zapobiega przypadkowemu wrzuceniu do repozytorium dużych
   plików danych, które nie powinny tam trafić (limity rozmiaru na GitHub,
   niepotrzebne zaśmiecanie historii zmian).

5. **Kopia zapasowa** — repozytorium na GitHub istnieje niezależnie od mojego
   komputera, więc awaria dysku nie oznacza utraty całej pracy.

To są dokładnie te same praktyki, których będę używał w prawdziwej pracy
analitycznej — im wcześniej stają się nawykiem, tym mniej problemów będę
miał przy większych, bardziej złożonych projektach na studiach.