Program (10 punktów)

1. Wczytanie i podział danych
   Wczytaj dane z pliku `daneXX.txt`. Wybierz dane z folderu public/mmajew/MIW/07 NN/Dane
   Zaproponuj i zrealizuj podział danych na zbiory treningowy i testowy.

2. Projektowanie i trenowanie sieci neuronowej
   Zaproponuj optymalną sieć neuronową aproksymującą wczytane dane.
   Napisz własną klasę sieci neuronowej korzystając z biblioteki numpy.
   Użyj nieliniowej funkcji aktywacji w warstwie ukrytej (np. tanh lub sigmoidalna).
   Wytrenuj sieć metodą wsadową z użyciem propagacji wstecznej błędu.

3. Ocena działania sieci – underfitting/overfitting
   Oceń działanie sieci pod kątem dopasowania: niedopasowanie, dopasowanie optymalne, zbytnie dopasowanie.

4. Zmiana sposobu trenowania
   Zmień sposób trenowania z wsadowego na online (stochastyczny).
   Wytrenuj sieć i oceń jej działanie.

5. Funkcja aktywacji RELU
   Zaproponuj sieć z funkcją aktywacji RELU w warstwie ukrytej.
   Wytrenuj sieć metodą wsadową z propagacją wsteczną błędu.

Uwaga: Nie używaj gotowych bibliotek sieci neuronowych.
Do implementacji sieci użyj operacji macierzowych w bibliotece NumPy.

Pytania (4 punkty)
1. Jakie są różnice między funkcjami aktywacji sigmoidalną, tanh i ReLU, i jaki mają wpływ na proces uczenia sieci neuronowej?
2. Co to jest przeuczenie (overfitting) i niedouczenie (underfitting) w sieciach neuronowych, i jakie są metody ich wykrywania oraz przeciwdziałania?
3. Czym różni się uczenie wsadowe (batch) od uczenia online (stochastic), i jakie są zalety i wady każdego z podejść?
4. Co to jest interpolacja i aproksymacja?
5. Co to jest współczynnik korelacji? Co to jest współczynnik korelacji liniowej Pearsona?
6. Co to jest metoda najmniejszych kwadratów?