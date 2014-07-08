**1. Formalizm lagranżowski mechaniki klasycznej.**
Mamy lagranżjan $ L$, który jest możemy utożsamiać z energią kinetyczną - energia potencjalna. I jest to funkcja: $L(q, \dot q)$ tj. położeń uogólnionych i prędkości. Z tego buduje się działanie:
$$S = \int_{t_0}^{t_1} L \; dt$$
i działanie musi być zminimalizowane, co prowadzi do równań E-L:
$$\frac{dL}{dq} - \frac{d}{dt} \left( \frac{dL}{d \dot q} \right) = 0$$
Pędy uogólnione: $p = dL/d \dot q$, siły uogólnione: $F = dL/dq$.

**2. Symetrie i prawa zachowania.**
W fizyce ciągłe symetrie lagranżjanu, a ogólniej działania, prowadzą do wielkości zachowanych - prądów noetherowskich. Np. niezmienniczość lagranżjanu względem translacji w czasie prowadzi do zachowania energii, niezmienniczosć na przesunięcia - zachowanie pędu, etc.

**3. Formalizm kanoniczny mechaniki klasycznej.**
Wpierw zdefiniujmy hamiltonian jako transformację Legendre'a lagranżjanu:
$$ H(q, p) = \sum p \dot q - L(q, \dot q)$$
Transformacja kanoniczna współrzędnych to taka zamiana $(p, q) \to (P, Q)$, która zachowuje równania kanoniczne Hamiltona:
$$\dot P = - \frac{dH}{dQ}, \quad \dot Q = \frac{dH}{dP}$$

**4. Równania mechaniki kwantowej i prawo zachowania prawdopodobieństwa**
Podstawa - równanie Schrodingera (w reprezentacji położeniowej):
$$i \hbar \partial_t \psi (x, t) = -\frac{\hbar^2}{2m} \partial_x^2 \psi (x, t) + V(x, t) \psi(x, t)$$
Bardziej formalnie:
$$\hat H | \psi (t) \rangle = i \hbar \partial_t | \psi (t) \rangle$$
Prawd.: $\rho = \langle \psi | \psi \rangle$, z r. Sc. wynika $- \partial_t \rho = \nabla \cdot \vec j$

**5. Operatory hermitowskie i wielkości obserwowalne w mechanice kwantowej.**
Obserwabla to wielkość fizyczna, która jest reprezentowana przez operator hermitowski. 
Operator hermitowski: $\langle A \psi | \phi \rangle = \langle \psi | A \phi \rangle$, ma rzeczywiste wartości własne - gdyż tylko takie możemy obserwować w eksperymencie (np. energia, pęd, położenie, rzyt spinu, etc.).
Część z tych wielkości nie komutuje tj. nie można mierzyć ich jednocześnie.

**6. Klasyczny i kwantowy opis oscylatora harmonicznego.**
Klasycznie:
$$\ddot x(t) + \omega^2  x(t)  =  0 \Rightarrow x(t) = C_1 \cos (t + \phi)$$
Kwantowo:
$$-\frac{\hbar^2}{2m} \psi''(x) + \frac{1}{2} m \omega^2 x^2 \psi (x) = E_n \psi (x)$$
Dyskretne widmo energii $E_n = \hbar \omega (n + \tfrac{1}{2})$

**7. Związki komutacyjne dla operatorów, zasada nieoznaczoności Heisenberga.**
Najpopularniejszy: $\Delta x \Delta P_x \ge \hbar / 2$
Niepewność pomiaru jednej wielkości powoduje zmienę niepewności pomiaru drugiej, o ile nie komutują odpowiednie operatory ($[x, p_x] = i \hbar$)

**8. Stany i wartości własne operatora energii i ewolucja czasowa stanów czystych.**
Stany własne operatora energii mają ustaloną energię - jedną z wartości własnych hamiltonianu. Ewolucja czasowa takiego stanu przebiega następująco:
$$|\psi(t) \rangle = U(t, 0) | \psi (0) \rangle = e^{-iHt /\hbar}  \psi (0) \rangle$$
$$|\psi(t) \rangle = e^{-iEt/\hbar} |\psi (0) \rangle$$
O ile ten stan jest stanem czystym, o ustalonej energii $E$.

**9. Stany mieszane i macierz gęstości w mechanice kwantowej**
Jeżeli rozpiszemy bazę przestrzeni Hilberta w stanach $| \psi_i \rangle$ ortonormalnych, to macierz gęstości:
$$\rho = \sum \lambda_i | \psi_i \rangle \langle \psi_i |, \quad \sum_i \lambda_i = 1$$
gdzie $\lambda_i$ to prawd. z jakimi stan $|\psi_i\rangle$ pojawia się w stanie mieszanym.
Własności: samosprzężony, dodatniookreślony, $Tr \rho = 1$, $Tr \rho^2 \le 1$.

## Elektromagnetyzm ##
**10. Równania Maxwella i ich interpretacja fizyczna.**
$\nabla \times \vec E = - \partial_t \vec B \quad \nabla \times \vec B = \mu \vec j + \mu \epsilon \partial_t \vec E$
$\nabla \cdot \vec E = \rho / \epsilon, \quad \nabla \cdot \vec B = 0$
Zmienne pole B jest źródłem E; prąd i  zmienne pole E są źródłami B, ładunki są źródłem E, B nie ma ładunków

**11.Fale elektromagnetyczne; prawa odbicia i załamania.**
Prawa odbicia i załamania wynikają z ciągłości składowych stycznych pól E i B na krawędzi

## Termodynamika ##
**12. Zasada ekwipartycji energii w układzie pozostającym w równowadzetermodynamicznej.**
Zasada ekwipartycji energii - na każdy stopień swobody przypada kT/2.

**13. Pojęcie stanu równowagi układu termodynamicznego. Równowagowe zespoły statystyczne**
Równowaga termodynamiczna - stan, w którym makroskopowe parametry (objętość, ciśnienie, funkcje stanu są stałe w czasie)
Funkcja stanu - f. zależna wyłącznie od stanu układu, np. U energia wew., S - entropia, entalpia H = U + pV, energia swobodna F = U - TS, etc. G = U - TS + pV

**14. Rozkład Plancka (np. promieniowanie Słońca, człowieka i tła).**
$$I(\nu) = \frac{2 h\nu^{3}}{c^2}\frac{1}{e^{\frac{h\nu}{kT}}-1},$$
$I(\nu)$  - radiancja spektralna częstotliwościowa (tzn. radiancja na jednostkę częstotliwości) w kierunku prostopadłym do emitującej powierzchni
Dotyczy ciała doskonale czarnego (pochłania całe promieniowanie nań padające i jest w równowadze term. z ciałami o temp $T$)
(Całka z I jest skończona - brak katastrofy w nadfiolecie)

**15. Ciepło właściwe. Teorie Einsteina i Debye'a ciepła właściwego ciał stałych.**
Ciepło właściwe – ciepło potrzebne do zwiększenia temperatury ciała o jednostkowej masie o jedną jednostkę
Cała sieć drga z tą samą częstotliwością
Model Debye'a - rozkład gęstości stanów jest jak $\omega^2$ i się urywa w pewnym momencie

**16. Rozkłady Fermiego-Diraca i Bose'go-Einsteina; spin i statystyka.**
Rozkład Fermiego (najprostszy). Albo w danym stanie kwantowym jest jedna cząstka, albo żadna, hence:
$$Z = e^0 + e^{- \beta (\epsilon - \mu)}$$
I dalej $N \sim \partial_\mu \ln Z = \frac{1}{1 + e^{\beta (\epsilon - \mu)}}$
Rozkład bozonowy - tu inaczej, bo w danym stanie kwantowym może być ile wlezie:
$$Z = \sum_n e^{-n \beta (\epsilon - \mu)}$$

