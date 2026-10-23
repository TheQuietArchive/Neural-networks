Papier–Kamień–Nożyce  z uczeniem bayesowskim i ukrytym modelem Markowa

Zaimplementuj symulację gry Papier–Kamień–Nożyce w dowolnym języku, w której jeden gracz stosuje strategię probabilistyczną, a drugi gracz z czasem uczy się tej strategii i ją przewiduje.



(10 punktów) Kod powinien zawierać:

Jednego gracza, którego strategia jest zdefiniowana przez macierz przejść opisującą prawdopodobieństwo wyboru następnego ruchu w zależności od poprzedniego ruchu.

Drugi gracz przewiduje następny ruch przeciwnika na podstawie zaobserwowanych przejść i aktualizuje prawdopodobieństwa po każdej obserwacji, stosując aktualizację bayesowską. W praktyce może to być zaimplementowane poprzez zliczanie częstości przejść i ich normalizację w celu oszacowania prawdopodobieństw warunkowych (co odpowiada aktualizacji bayesowskiej z jednostajnym rozkładem prior). Następnie gracz stosuje strategię kontr ruchu, która ma na celu pokonanie przewidywanego ruchu przeciwnika.

Symulację co najmniej 1000 rund gry.
Śledzenie i wykres skumulowanego wyniku w kolejnych rundach.
Wypisanie wyuczonej macierzy przejść po zakończeniu symulacji.

Uwaga: Powinieneś być przygotowany na odpowiedzi na pytania dotyczące Twojego kodu, zarówno z zakresu podstaw teoretycznych, jak i aspektów programistycznych. Pytania będą bezpośrednio odnosić się do kodu, dlatego postaraj się, aby implementacja była prosta i czytelna.



(4 punkty) Jedno ustne pytanie z teorii zostanie wylosowane (rzut kostką):

Jaka jest główna idea łańcucha Markowa?

Czym są stany ukryte oraz czym jest macierz przejść w ukrytym modelu Markowa?

Czym są obserwacje oraz czym jest macierz emisji?

Czym jest prawdopodobieństwo warunkowe?

Na czym polega podstawowa idea twierdzenia Bayesa?

Jaka jest różnica między prawdopodobieństwem apriorycznym (prior) a prawdopodobieństwem aposteriorycznym (posterior)?
