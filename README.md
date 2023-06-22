<h1>Opis gry</h1>

Ta gra to klasyczna wersja Pac-Mana napisana w języku JavaScript. Gra odzwierciedla znane elementy oryginalnej gry, które sprawią, że będziesz mieć ochotę na nią zagrać.

W grze znajdziesz charakterystycznego żółtego gracza, którym będziesz sterować. Twoim celem jest zbieranie białych kulek rozsianych po planszy. 
Za każdą zebraną kulkę zdobywasz 10 punktów. Musisz jednak uważać na duchy, które poruszają się po planszy i będą próbowały cię złapać. Jeśli którykolwiek z duchów cię dotknie, 
przegrasz grę.
![lost](https://github.com/IS-UMK/project-ABurkas/assets/118464323/546ee8d9-73ed-4d1e-8c0f-bcbd245449df)



Aby ułatwić sobie zadanie, na planszy znajdują się również punkty mocy. Gdy zbierzesz taki punkt, duchy stają się przerażone i możesz je zjeść. 
Każde zjedzone ducha przynosi ci dodatkowe punkty. Przerażone duchy będą się jednak po pewnym czasie odzyskiwać, więc musisz zagrać sprytnie, aby wykorzystać tę szansę.

![scared](https://github.com/IS-UMK/project-ABurkas/assets/118464323/476deb4d-945e-4628-806b-9edce612878f)


Plansza składa się z różnych elementów, takich jak ściany, przeszkody czy rożki. Musisz dobrze zaplanować swoje ruchy, aby uniknąć kolizji ze ścianami i przeszkodami, 
a także unikać spotkania z duchami. Sterowanie postacią odbywa się za pomocą klawiszy W, A, S i D, które odpowiadają za ruch w górę, w lewo, w dół i w prawo.



Gra posiada również system punktacji, który jest wyświetlany na ekranie. Możesz śledzić swoje postępy i starać się zdobyć jak najwięcej punktów. 
Wygrana jest osiągalna, gdy zebrasz wszystkie białe kuleczki na planszy.

![winner](https://github.com/IS-UMK/project-ABurkas/assets/118464323/f4951d02-ce8c-4e17-adf4-b0d7961cbf55)



<h3>Najlepsze strony tej gry to:</h3>

* Autentyczne odtworzenie: Gra Pac-Man została wiernie odtworzona, z zachowaniem charakterystycznych elementów takich jak kształt postaci Pac-Mana i duchów, 
wygląd kropek oraz kształt granic planszy. To sprawia, że gra jest rozpoznawalna i dostarcza nostalgii dla fanów oryginalnej gry.

* Wyzwanie i strategia: Gra oferuje wyzwanie, ponieważ gracze muszą sprawnie manewrować postacią Pac-Mana po planszy, unikając duchów i zbierając kropki. 
Dodatkowo, obecność punktów mocy daje graczowi okazję do odwrócenia sytuacji i ścigania duchów. Optymalne planowanie tras i szybkie podejmowanie decyzji są kluczowe dla osiągnięcia sukcesu.

* Interakcja z elementami planszy: Gracze mogą interakcjonować z różnymi elementami planszy, takimi jak granice, kropki i punkty mocy. Granice wymagają zręczności, 
aby uniknąć kolizji, a zbieranie kropek i punktów mocy pozwala zdobywać punkty i kontrolować zachowanie duchów.

* Wyjątkowe cechy graficzne: Gra została wizualnie dostosowana do stylu Pac-Mana, używając kolorów i wzorów charakterystycznych dla oryginalnej gry. Wzory duchów, 
ich zmieniający się kolor oraz wygląd kropek i punktów mocy są dobrze rozpoznawalne i dodają atrakcyjności wizualnej do rozgrywki.

* Prosta kontrola: Sterowanie postacią Pac-Mana odbywa się za pomocą klawiszy strzałek, co czyni grę łatwą do opanowania dla nowych graczy. 
Intuicyjne poruszanie się po planszy pozwala skupić się na zabawie i strategicznym podejmowaniu decyzji.

* Ta wersja Pac-Mana napisana w JavaScript oferuje wszystkie znane elementy oryginalnej gry, takie jak sterowanie postacią, zdobywanie punktów, 
unikanie duchów i wygrana po zebraniu wszystkich kul. 
Jeśli jesteś fanem Pac-Mana lub po prostu chcesz spróbować tej klasycznej gry, ta implementacja z pewnością dostarczy ci wiele frajdy i wyzwań. 

**Czy jesteś gotowy, aby zostać mistrzem Pac-Mana?**

<h1>Instrukcja obsługi gry:</h1>

W celu rozpoczęcia gry, otwórz stronę internetową lub edytor kodu, w którym można uruchomić skrypt JavaScript.

Skopiuj podany kod gry do swojego edytora kodu.

Uruchom grę, a następnie zobaczysz planszę gry oraz postać gracza, oznaczoną kolorem żółtym.

Gracz może poruszać się po planszy przy pomocy klawiszy **WASD**. Naciśnij klawisz **W**, aby poruszać się **do góry**, klawisz **A** - **w lewo**, klawisz **S** - **w dół**, klawisz **D** - **w prawo**.

Celem gry jest zebranie wszystkich punktów oznaczonych kolorem białym na planszy. Punkty można zbierać poprzez dotknięcie ich postacią gracza. Każdy zebrany punkt dodaje 10 punktów do ogólnego wyniku, który jest wyświetlany w lewym górnym rogu planszy.

Unikaj kolizji z duchami, które poruszają się po planszy. Kolizja z duchem spowoduje przegraną. Jeśli dotkniesz przestraszonego ducha, zostanie on usunięty z planszy.

Na planszy znajdują się również punkty mocy oznaczone kolorem żółtym. Jeśli dotkniesz punktu mocy, duchy zostaną przestraszone na 5 sekund. W tym czasie możesz bezpiecznie zbierać punkty lub unikać duchów.

Gra kończy się, gdy wszystkie punkty na planszy zostaną zebrane lub gdy gracz dotknie ducha. Po zakończeniu gry wyświetli się odpowiedni komunikat w środku planszy.

Aby dostosować planszę gry, można zmieniać układ mapy, dodając lub usuwając elementy z tablicy "map". Możesz również zmieniać prędkość poruszania się duchów, zmieniając wartość zmiennej "speed" w klasie Ghost.

Możesz również dostosować wygląd planszy gry, zmieniając obrazy używane do renderowania granic, punktów i punktów mocy. Możesz zastąpić istniejące obrazy, 
dostarczając nowe ścieżki do nich w funkcji "createImage".

To wszystko! Teraz możesz cieszyć się grą i próbować zdobywać jak najwięcej punktów, unikając jednocześnie duchów. Powodzenia!
