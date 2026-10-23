Program (10 punktów)

1. Dane
   Użyj zbioru “CIFAR10 small image classification” z biblioteki Keras.
   Podziel dane na zbiory: treningowy, walidacyjny i testowy (np. 60/20/20).
   Zastosuj normalizację danych oraz podstawową augmentację (np. rotacja, flip).
2. Model CNN
   Zaproponuj klasyfikator CNN dla 10 klas.
   Przetestuj co najmniej dwie architektury (np. różna liczba warstw konwolucyjnych).
3. Trenowanie
   Wytrenuj modele i zapisz przebieg uczenia: strata zbioru treningowego i walidacyjnego vs. epoki (loss train and validation vs. epochs) na wykresie
4. Ewaluacja
   Wyświetl: confusion matrix, accuracy danych testowych.
   Porównaj wyniki dla różnych modeli.
5. Analiza
   Oceń overfitting/underfitting na podstawie wykresów.
   Przeanalizuj błędne klasyfikacje.
6. Wnioski
   Wskaż najlepszy model i uzasadnij wybór.

Liczba punktów zależy od dokładności (accuracy) na danych testowych:
 0.6 < accuracy  < 0.7   ->   6 points
0.7 < accuracy  < 0.8   ->   8 points
0.8 < accuracy              ->   10 points


Pytania (4 punkty)
1. Jakie są główne komponenty sieci konwolucyjnej (CNN) i jakie pełnią funkcje?
2. W jaki sposób augmentacja danych poprawia uogólnianie modelu i redukuje overfitting?
3. Jaki jest cel podziału danych na zbiory treningowy, walidacyjny i testowy?
4. Jak liczba warstw konwolucyjnych wpływa na ekstrakcję cech i jakość modelu?
5. Co to jest overfitting w CNN i jak można go wykryć na podstawie wykresów treningowych i walidacyjnych?
6. Jakie informacje dostarcza macierz pomyłek i jak można ją wykorzystać do analizy działania modelu?