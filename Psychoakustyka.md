## 2. Psychoakustyka

Psychoakustyka to nauka o tym, jak ludzie odbierają dźwięk – nie tylko jego fizyczne parametry, ale też to, jak mózg je interpretuje. W kontekście FOH jej znajomość pozwala miksować muzykę tak, by brzmiała pełniej, czyściej i bardziej naturalnie.

---

### 2.1 Percepcja głośności

* **Skale liniowe vs. logarytmiczne**
  Fizyczna amplituda ciśnienia akustycznego mierzy się w Pa, ale nasza percepcja głośności jest logarytmiczna. Dlatego używamy skali decybelowej:

$$
  L_p = 20 \log_{10}\frac{p}{p_0}\quad[\mathrm{dB}]
$$

  gdzie $p_0 = 20\,\mathrm{\mu Pa}$ to próg słyszalności.

* **Krzywe izofoniczne (Fletcher–Munson)**
  Nasze ucho nie jest jednakowo czułe na wszystkie częstotliwości. Krzywe izofoniczne pokazują poziomy ciśnienia (w dB SPL) potrzebne do tego samego wrażenia głośności przy różnych częstotliwościach.

  * Na przykład, aby słyszeć dźwięk 100 Hz tak samo głośno jak 1 kHz, potrzeba \~10 dB więcej SPL przy 100 Hz.

* **Jednostki son i phon**

  * **Phon** to liczba dB SPL na 1 kHz odpowiadająca percepcji głośności.
  * **Son** – subiektywna skala: 1 sone to głośność 40 phon; każde podwojenie sonów odbieramy jako dwukrotnie głośniejsze.

* **Prawo Webera–Fechnera**
  Zmiana intensywności dźwięku musi przekroczyć pewien względny próg ($\Delta I / I\approx 0{,}1$), by wywołać różnicę w odczuciu głośności.

---

### 2.2 Maskowanie częstotliwościowe

Gdy dwa tony bliskie częstotliwościowo występują jednocześnie, silniejszy może „zagłuszyć” słabszy:

* **Maskowanie równoczesne (simultaneous masking)**
  Ton o wyższej amplitudzie maskuje sąsiednie częstotliwości wewnątrz tzw. pasma krytycznego (\~1/3 oktawy).

* **Maskowanie czasowe (temporal masking)**
  – **Predmasking**: słabszy dźwięk poprzedzający głośny jest mniej słyszalny przez \~20 ms.
  – **Postmasking**: słabszy dźwięk występujący do \~200 ms po głośnym jest maskowany.

**Praktyczne znaczenie w miksie**:

* Wycinanie (EQ) w pasmach krytycznych innych instrumentów, gdy chcemy je wyeksponować.
* Uważne użycie kompresji i transient shaping, by unikać niezamierzonego maskowania.

---

### 2.3 Efekt Haasa (precedence effect)

Gdy ten sam dźwięk dociera do ucha bezpośrednio i po odbiciu z bardzo małym opóźnieniem (10–35 ms):

* **Pierwszeństwo słyszenia**: nasz mózg lokalizuje źródło według pierwszego impulsu, a późne odbicia łączy z tym samym źródłem, nie postrzegając ich jako echo.
* **Próg percepcji echa**: przy opóźnieniu >35 ms słyszymy wyraźne echo.

**Zastosowanie FOH**:

* Ustawianie głośników opóźnionych (delay towers), by dźwięk dotarł do dalszych rzędów w tej samej fazie, bez zakłócania percepcji lokalizacji głównego źródła scenicznego.

---

### 2.4 Lokalizacja źródła dźwięku

#### a) Różnice międzyuszne w czasie (ITD)

Dźwięk z boku dociera do bliższego ucha wcześniej nawet o \~600 µs. ITD są kluczowe w lokalizacji tonów poniżej \~1.5 kHz.

#### b) Różnice międzyuszne w poziomie (ILD)

Wyższe częstotliwości są blokowane przez głowę (tzw. cień akustyczny), co daje różnice poziomu do kilku dB – najefektywniejsze powyżej \~1.5 kHz.

#### c) Monauralne wskazówki kierunkowe

Pochodzą z kształtu małżowiny usznej (filtracja wysokościowa), pomagają określić „kąt elewacji” źródła.

#### d) Konusy niepewności (cones of confusion)

Zestaw punktów w przestrzeni dających te same ITD i ILD – rozróżniane dzięki ruchom głowy i odbiciom w pomieszczeniu.

**Praktyka FOH**:

* Miks stereo (panoramowanie) powinno uwzględniać, że ekstremalne pozycjonowanie >75% L/R traci sens dla niskich tonów (ITD przeważa).
* Umiarkowane panoramowanie i manipulacja głębią (reverb, EQ) wspiera naturalną scenę dźwiękową.

---

Opanowanie psychoakustycznych mechanizmów pozwala nie tylko na świadome kształtowanie miksu, ale i unikanie technicznych pułapek (maskowanie, niepożądane echa), dzięki czemu dźwięk FOH brzmi klarownie i przestrzennie. Jeśli masz pytania do któregoś z podpunktów lub chcesz dowiedzieć się, jak wykorzystać te zasady w praktyce miksowania, daj znać!
