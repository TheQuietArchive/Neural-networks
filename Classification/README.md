Program (10 punktów)

1. Generowanie danych
   Użyj biblioteki scikit-learn.
   Wygeneruj zbiór danych funkcją make_moons(n_samples=1000, noise=0.25).
   Podziel dane na zbiór uczący i testowy metodą train_test_split().

2. Regresja logistyczna (własna implementacja)
   Zaimplementuj model w pliku reglog.py i wytrenuj klasyfikator.
   Napisz metodę zwracającą prawdopodobieństwa przynależności do klas.
   Nie używaj gotowych implementacji perceptronu ani regresji logistycznej z bibliotek.

3. Drzewo decyzyjne
   Użyj DecisionTreeClassifier.
   Porównaj kryteria: entropia oraz Gini.
   Sprawdź wpływ różnych głębokości drzewa.

4. Las losowy
   Użyj RandomForestClassifier.
   Zbadaj wpływ liczby drzew na wyniki.

5. SVM
   Wytrenuj klasyfikator SVM.

6. Ensemble
   Połącz SVM, LogisticRegression oraz RandomForestClassifier w VotingClassifier.

7. Ewaluacja
   Porównaj modele z punktów 2–6.
   Użyj metryk accuracy oraz wizualizacji granic decyzyjnych (decision boundaries).

Pytania teoretyczne (4 punkty)

1. Jakie są różnice między perceptronem a regresją logistyczną w kontekście klasyfikacji binarnej i wieloklasowej?
2. Jak działają strategie OvR i OvO przy klasyfikacji wieloklasowej i jakie mają wady i zalety?
3. Czym różnią się kryteria entropii i Gini w DecisionTreeClassifier i jaki mają wpływ na podział węzłów drzewa?
4. Dlaczego lasy losowe (RandomForest) osiągają lepszą stabilność i dokładność niż pojedyncze drzewo decyzyjne?
5. Jak funkcjonuje SVM w kontekście separacji danych nieliniowych i czym jest margines maksymalny?
6. Jakie są zalety łączenia różnych klasyfikatorów w VotingClassifier i w jakich sytuacjach takie podejście może poprawić wyniki klasyfikacji?