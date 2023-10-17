[Spis treści](System premiowy CX!/SUMMARY.md)

# 📏 Mierniki doradców

## Podstawowe mierniki:

<details>

<summary>Wydajność</summary>

Suma rozwiązanych spraw przez sumę czasu spędzonego na statusie transakcyjnym. Od sumy czasu transakcyjnego odejmowana jest suma czasu IDLE, czyli czasu, kiedy doradca był na statusie gotowy, ale nie wpadła mu żadna sprawa.\
\- Dla obszaru Klienta do sumy rozwiązanych spraw dodawana jest suma konsultacji eksperckich z wagą 1.5 oraz suma konsultacji slack, również z wagą 1.5.\
\- Dla obszaru partnera do sumy rozwiązanych spraw dodawana jest suma konsultacji eksperckich z wagą 1.5.

Wykluczenia:\
DLa zespołów FL od wolumenu rozwiązanych spraw odejmujemy sprawy reklamacyjne, a od czasu transakcyjnego czas spędzony na reklamacjach.

</details>

<details>

<summary>NPS</summary>

Suma promotorów (ankiety z ocenami 9-10) minus suma detraktorów (ankiety z ocenami 0-6) przez sumę wszystkich ankiet. \
Dla obszaru Partnera, poza streamem VIP, bierzemy pod uwagę jedynie ankiety od segmentu B2C, a dla streamu VIP jedynie ankiety od segmentu VIP lub ze skilli VIPTOP.

</details>

<details>

<summary>FCRs</summary>

Suma odpowiedzi ‘TAK’ na pytanie ‘Was case resolved’ przez sumę wszystkich ankiet.\
Dla streamu VIP jedynie ankiety od segmentu VIP lub ze skilli VIPTOP.

</details>

<details>

<summary>CSAT</summary>

Suma pozytywnych odpowiedzi na dwa pytania: ‘answers\_comprehensibility’ oraz ’employee\_involvement’ przez sumę wszystkich ankiet.\
Dla streamu VIP jedynie ankiety od segmentu VIP lub ze skilli VIPTOP.

</details>

<details>

<summary>Jakość</summary>

Suma ocen bardzo dobrych przez sumę wszystkich ocen z monitoringów. Pod uwagę bierzemy jedynie rodzaj oceny Próbka. Nie jest brana pod uwagę Weryfikacja lidera.\
Dodatkowo:\
Zdanie Testów Wiedzy jest warunkiem koniecznym zaliczenia celu Jakość w raporcie premiowym:\
entry 50 -> 70% ocen bdb w monitoringach +  zaliczone wszystkie TW\
target 100 -> 80% ocen bdb w monitoringach +  zaliczone wszystkie TW\
boost 125 -> 90% ocen bdb w monitoringach + zaliczone wszystkie TW\
boost 150 -> 100% ocen bdb w monitoringach + zaliczone wszystkie TW

</details>

<details>

<summary>Czas transakcyjny </summary>

Suma czasu spędzonego na statusie transakcyjnym przez sumę czasu total.

</details>

<details>

<summary>Czas rozpatrywania (pudo,broker)</summary>

Średni czas od przekierowania do pobrania sprawy. \
Pudo - reklamacje One Box. Broker - reklamacje logistyczne.

</details>

<details>

<summary>CR (pudo,broker) </summary>

Średnia ilość wiadomości wysłana w jednej sprawie. \
Pudo - reklamacje One Box. Broker - reklamacje logistyczne.

</details>

<details>

<summary>Projekt </summary>

Cel rozliczany na koniec kwartału przez przełożonego, poprzez wysłanie maila z finalnym poziomem zaliczenia (entry, target, boost125%, boost150%) na alias premiowy.

</details>

## Wykluczenia ankiet dotyczące NPS, FCR oraz CSAT:

1. Dla streamu 3 w Kliencie wykluczone są ankiety dotyczące typu Mediacja lub kanałów kontaktów Callback, lub Mail.
2. Jeśli w momencie wypełnienia ankiety konto Klienta/Partnera było zablokowane.

<details>

<summary>Skille wykluczane dla zespołów FL</summary>

* KL\_OneKurier\_Reklamacje
* PA\_OneKurier\_Reklamacje
* PA\_Reklamacje\_PUDO
* KL\_Reklamacje\_PUDO
* BO\_Mediacje
* PA\_Mediacje
* PA\_Zasady
* PA\_Zasady\_CZ
* TS\_Oferta
* TS\_Prewencja
* TS\_SQM
* TS\_SQM\_CZ
* PA\_Antychurn
* PA\_Komentarze
* PA\_Komentarze\_CZ
* PA\_VIPTOP\_Komentarze
* PA\_VIPTOP\_Zasady

</details>

<details>

<summary>Skille wykluczane dla zespołów BL</summary>

* PA\_Zasady
* PA\_Zasady\_CZ
* TS\_Oferta
* TS\_Prewencja
* TS\_SQM
* TS\_SQM\_CZ
* PA\_Antychurn
* PA\_Komentarze
* PA\_Komentarze\_CZ
* PA\_VIPTOP\_Komentarze
* PA\_VIPTOP\_Zasady

\


</details>

