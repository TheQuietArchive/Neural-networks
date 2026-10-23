Program (10 punktów)

Dane
Wybierz notowania giełdowe wybranej spółki lub kursu walutowego, np. z https://stooq.com/.
Podziel dane chronologicznie na zbiory: treningowy, walidacyjny i testowy, np. 60/20/20.
Zastosuj normalizację danych oraz wykonaj analizę wstępną szeregu czasowego, uwzględniając trend, zmienność i ewentualną sezonowość.

Prosty model rekurencyjny RNN
Zaproponuj prosty model rekurencyjny, np. SimpleRNN w Keras.
Przygotuj sekwencje wejściowe, czyli okno czasowe obejmujące kilka lub kilkadziesiąt poprzednich obserwacji.
Dobierz podstawowe parametry modelu, np. długość okna czasowego, liczbę neuronów, liczbę epok i batch size.
Wybierz najlepszą konfigurację na podstawie błędu walidacyjnego.

Model rekurencyjny z komórkami pamięci: LSTM lub GRU
Zaproponuj bardziej zaawansowaną sieć rekurencyjną, np. LSTM lub GRU.
Uwzględnij sekwencje wejściowe, czyli okno czasowe.
Zastosuj techniki poprawy trenowania, takie jak dropout, skalowanie danych i early stopping.
Porównaj działanie modelu LSTM lub GRU z prostym modelem SimpleRNN.

Dane dodatkowe
Rozszerz model o dodatkowe cechy, np. wolumen, indeks giełdowy, kurs otwarcia, kurs najwyższy, kurs najniższy lub proste wskaźniki techniczne.
Sprawdź, czy dodanie nowych cech poprawia jakość predykcji.

Ewaluacja
Porównaj modele SimpleRNN oraz LSTM lub GRU.
Użyj metryk regresyjnych, np. MSE i MAE.
Zwizualizuj predykcje modeli względem wartości rzeczywistych na zbiorze testowym.

Analiza i wnioski
Oceń jakość modeli oraz ich zdolność do generalizacji.
Sprawdź, czy modele dobrze działają na danych testowych, a nie tylko na danych treningowych.
Wskaż najlepszy model i uzasadnij wybór na podstawie metryk oraz wykresów.


Pytania (4 punkty)

1. Jakie są założenia modelu autoregresyjnego (AR) i jakie ograniczenia wynikają z tych założeń?
2. W jaki sposób dobór rzędu modelu AR wpływa na jego zdolność do uogólniania (generalizacji)?
3. Czym różnią się architektury LSTM i GRU oraz w jakich sytuacjach każda z nich może być korzystniejsza?
4. Dlaczego normalizacja danych wejściowych jest istotna w trenowaniu modeli RNN?
5. Jakie znaczenie mają dodatkowe cechy (np. wskaźniki techniczne, wolumen) w modelowaniu szeregów czasowych?
6. Jak interpretować metryki MSE i MAE oraz jakie są ich zalety i wady w kontekście predykcji finansowych?