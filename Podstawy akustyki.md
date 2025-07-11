Poniżej znajdziesz szczegółowe omówienie wszystkich podpunktów z rozdziału „Podstawy akustyki”:

---

## 1. Fale dźwiękowe

### a) Właściwości fal dźwiękowych

* **Częstotliwość (f)** mierzy liczbę drgań na sekundę, wyrażana w hercach (Hz). To ona decyduje o wysokości tonu: niskie częstotliwości (np. 20 Hz) brzmią basowo, wysokie (np. 10 kHz) – sopranowo.
* **Amplituda (A)** to maksymalne wychylenie cząstek ośrodka od pozycji równowagi; odpowiada za głośność. Związek między amplitudą a poziomem ciśnienia akustycznego opisuje równanie:

$$
  \p(t) = A \sin(2\pi f t + \varphi)
$$

  gdzie $p(t)$ – ciśnienie w funkcji czasu, $\varphi$ – faza początkowa.
* **Długość fali (λ)** to odległość, jaką fala przebywa w czasie jednego okresu drgań:

  $$
    \lambda = \frac{c}{f}
  $$

  z $c$ – prędkość dźwięku w danym ośrodku (w powietrzu ok. 343 m/s przy 20 °C).

### b) Propagacja

Dźwięk rozchodzi się jako fala podłużna – cząstki ośrodka oscylują w kierunku rozchodzenia się fali. W powietrzu proces ten jest stosunkowo wolny (343 m/s), w wodzie i w ciałach stałych – znacznie szybszy.

---

## 2. Prawo superpozycji

Gdy w jednym miejscu spotkają się dwie lub więcej fal, suma wychyleń cząstek jest równa algebraicznej sumie wychyleń każdej fali z osobna. Dzięki temu zjawisku powstają:

* **Interferencje konstruktywne** – gdy fale wzmocnią się wzajemnie (próżnie i grzbiety nakładają się fazowo),
* **Interferencje destrukcyjne** – gdy fale się wygaszają (grzbiet jednej nakłada się na próżnię drugiej).

To prawo tłumaczy np. „martwe” punkty w studiu, gdzie część częstotliwości jest wygaszona przez falę odbitą.

---

## 3. Odbicie, absorpcja, transmisja i dyfrakcja

1. **Odbicie** – część energii fali zostaje wyrzucona z powrotem od powierzchni. Kąt padania = kąt odbicia.
2. **Absorpcja** – część energii przechodzi w ciepło wewnątrz materiału. Mierzy się ją współczynnikiem pochłaniania $\alpha$ (0 = całkowite odbicie, 1 = całkowite pochłonięcie).
3. **Transmisja** – fala przechodzi przez przeszkodę do innego ośrodka, zmieniając prędkość i długość fali zgodnie z prawem załamania.
4. **Dyfrakcja** – ugięcie fali na krawędziach przeszkód i otworów, pozwalające „obejść” przez nią niewielkie przeszkody.

---

## 4. Zjawisko refrakcji (załamanie fali)

Gdy fala przechodzi z jednego ośrodka do drugiego (np. z zimnego powietrza do cieplejszego), zmienia się jej prędkość i kierunek. Opisuje to prawo Snelliusa:

$$
  \frac{\sin \theta_1}{\sin \theta_2} = \frac{c_1}{c_2}
$$

gdzie $\theta_1, \theta_2$ – kąty padania i załamania, $c_1, c_2$ – prędkości w obu ośrodkach.

---

## 5. Parametry akustyczne pomieszczeń

### a) Czas pogłosu $RT_{60}$

Czas, w którym poziom dźwięku spadnie o 60 dB po wyłączeniu źródła. Oblicza się go formułą Sabine’a:

$$
  RT_{60} = 0{,}161\,\frac{V}{A}
$$

gdzie $V$ – objętość pomieszczenia \[m³], $A = \sum S_i \alpha_i$ – suma powierzchni elementów \[m²] pomnożonych przez ich współczynniki pochłaniania $\alpha_i$.

### b) Wskaźnik Clarity

* **$C_{50}$** – stosunek energii dotarłej w pierwszych 50 ms do energii późniejszej. Ważny dla zrozumiałości mowy.
* **$C_{80}$** – analogicznie dla pierwszych 80 ms, istotny przy muzyce.

### c) Współczynnik pochłaniania ($\alpha$)

Określa, jaka część energii fali zostaje wchłonięta przez materiał. Przykładowe wartości: pianka akustyczna $\alpha\approx0{,}6$–0,9, beton $\alpha\approx0{,}02$.

---

## 6. Rozchodzenie się dźwięku w otwartej przestrzeni

Prawo odwrotnego kwadratu informuje, że poziom ciśnienia akustycznego $L_p$ spada o 6 dB przy dwukrotnym wzroście odległości od źródła punktowego:

$$
  L_p(r_2) = L_p(r_1) - 20\log_{10}\frac{r_2}{r_1}
$$

gdzie $r_1, r_2$ – odległości od źródła.

---

**Podsumowując**, zrozumienie tych fundamentów pozwala:

1. Przewidywać, jak dźwięk zachowa się w pomieszczeniu i na otwartej przestrzeni.
2. Optymalnie dobierać i ustawiać materiały pochłaniające.
3. Minimalizować niepożądane interferencje i pogłosy.

Opanowanie tych zagadnień to klucz do skutecznej kontroli i kształtowania brzmienia FOH. Jeśli chcesz, możemy przejść do przykładów obliczeń (np. wyznaczenie RT₆₀ dla konkretnego pomieszczenia) lub omówić wizualizację propagacji fali w praktyce.
