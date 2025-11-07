# AI-instrukcja-zrobienia-konsultanta-

# Instrukcja: jak pracować z AI jak z konsultantem

*(od pierwszego poznania, przez karmienie wiedzą, po ton odpowiedzi i protipy)*

--- 

## 🧠 TL;DR — *Jak pracować z AI jak z konsultantem*

Ten projekt to **kompletny system współpracy z AI** w roli doradcy strategicznego — od pierwszego kontaktu po codzienną iterację decyzji.
Celem jest, by AI **myślało razem z Tobą**, nie za Ciebie.

---

### 🎯 Idea

Traktuj AI jak **partnera konsultacyjnego**, nie asystenta.
Ustal rolę, ton, kontekst i zasady gry.
Zawsze prowadź rozmowę w trybie **cel → analiza → warianty → decyzja → refleksja**.

---

### ⚙️ Kluczowe zasady

1. **Nadaj rolę**:
   „Bądź moim konsultantem. Mów konkretnie, krytycznie, bez kurtuazji.”

2. **Podaj kontekst i cel**:
   kim jesteś, co chcesz osiągnąć, jakie są ograniczenia i kryteria sukcesu.

3. **Zlecaj zadania imperatywnie**:
   używaj poleceń: *przeanalizuj, zaproponuj, porównaj, zarekomenduj.*

4. **Wymagaj struktury i uzasadnień**:
   zawsze: **wnioski → uzasadnienie → ryzyka → rekomendacja.**

5. **Iteruj**:
   pogłębiaj, skracaj, zmieniaj perspektywę („dodaj sceptyka”, „zrób sanity check”).

6. **Zachowaj decyzyjność**:
   AI = hipotezy i rekomendacje, Ty = decyzje i odpowiedzialność.

7. **Unikaj słabości AI**:
   przypominaj kontekst, proś o źródła, żądaj krytyki własnych wniosków.

---

### 🧩 Narzędzia i formaty

* **Profil użytkownika** (rola, styl, wartości)
* **Pakiet kontekstu** (cel, fakty, ryzyka, kryteria sukcesu)
* **Szablony promptów** (diagnoza, rekomendacja, sanity check, red-team)
* **Gotowce do codziennej pracy** (brief, kickoff, reset, kontrola jakości)
* **Checklista jakości współpracy**

---

### 🧭 Efekt

Dzięki tej metodzie:

* AI **rozumie Twój kontekst i styl decyzji**,
* rozmowy są **merytoryczne, iteracyjne i produktywne**,
* Ty zyskujesz **narzędzie refleksji i akcelerator decyzji**,
* a nie iluzję inteligentnego asystenta.

---

> 📘 Używaj tego przewodnika jak „Operating Manual” dla współpracy człowiek–AI:
> raz dobrze ustaw — potem tylko iteruj, przypominaj cel i ucz AI o sobie.

---

## Spis treści

* [0) Szybki start](#0-szybki-start-5-kroków--kopiujwklej)
* [1) Ustawienie współpracy i tonu](#1-ustawienie-współpracy-i-tonu)
* [2) Co AI ma o Tobie wiedzieć](#2-co-ai-ma-o-tobie-wiedzieć-i-jak-to-podawać)
* [3) Jak „nakarmić” AI wiedzą](#3-jak-nakarmić-ai-wiedzą-materiały-wejściowe)
* [4) Jak pytać (tryb konsultanta)](#4-jak-pytać-tryb-konsultanta)
* [5) Iteracja (praca krokowa)](#5-iteracja-praca-krokowa)
* [6) Decyzje i odpowiedzialność](#6-decyzje-jak-używać-ai-i-pozostać-decydentem)
* [7) Antywzorce i kontrakcje](#7-jak-unikać-słabości-ai-antywzorce--kontrakcje)
* [8) Multi-źródła i weryfikacja](#8-multi-źródła-i-weryfikacja)
* [9) Szablony do codziennej pracy](#9-szablony-do-codziennej-pracy-gotowce)
* [10) Protipy i przypomnienia](#10-protipy-i-przypomnienia)
* [11) Gotowe formatki](#11-gotowe-formatki-kopiujwklej)
* [12) Checklista](#12-checklista-czy-dobrze-korzystam-z-ai)

---

## 0) Szybki start (5 kroków – kopiuj/wklej)

**Ustal rolę AI:**

> „Bądź moim konsultantem strategicznym. Mów wprost, krytycznie, bez kurtuazji.”

**Przedstaw się i cel:**

> „Jestem [rola]. Dziś chcę [cel], ograniczenia: [czas/budżet/zakres].”

**Dostarcz kontekst:**

> „Oto 5 faktów, 3 ryzyka, 3 kryteria sukcesu: [lista].”

**Zlecaj zadania w trybie imperatywnym:**

> „Przeanalizuj → zaproponuj 3 warianty → oceń ryzyko + wpływ → wskaż rekomendację.”

**Wymagaj uzasadnienia i weryfikacji:**

> „Pokaż tok rozumowania, założenia, sygnały ostrzegawcze i co zweryfikować.”

---

## 1) Ustawienie współpracy i tonu

### 1.1 Deklaracja roli i standardów

**Prompt powitalny (kopiuj/wklej):**

> „Od teraz jesteś moim konsultantem strategicznym. Priorytet: klarowność, wpływ na decyzje, pragmatyzm. Pisz zwięźle, konkretnie, bez ogólników. Zawsze: (1) wnioski → (2) uzasadnienie → (3) ryzyka → (4) rekomendacja. Kwestionuj moje założenia. Jeśli brakuje danych – powiedz czego potrzebujesz.”

### 1.2 Ton odpowiedzi, jaki preferuję

* Bezpośredni, krytyczny, rzeczowy.
* Zero „pocieszaczy” i nadmiarowej uprzejmości.
* Priorytet decyzji nad opisem świata.

**Krótkie przypomnienie tonu (wklej co kilka interakcji):**

> „Przypominam: doradzasz liderowi. Priorytet: decyzja, ryzyko, wpływ. Bez upiększania.”

---

## 2) Co AI ma o Tobie wiedzieć (i jak to podawać)

### 2.1 Profil użytkownika – mini-bio (stałe)

* Rola / odpowiedzialność: …
* Poziom techniczny / biznesowy: …
* Sposób pracy i preferencje: … (np. zwięzłe listy, matryce decyzyjne, warianty)
* Horyzont decyzyjny: … (dzień/tydzień/kwartał)
* Wartości / zasady (np. „mniej, ale lepiej”, „bezpieczeństwo > wygoda”)

**Szablon – „Mój profil” (wklej na start nowego wątku):**

> „Kim jestem: [rola]. Co robię: [3 punkty]. Decyduję o: [obszary]. Styl: [zwięzły/krytyczny/analityczny]. Cel współpracy: [np. lepsze decyzje szybciej].”

### 2.2 Kontekst zadania (zmienne)

* Cel na dziś (1 zdanie)
* Kluczowe fakty (≤7)
* Ryzyka/Ograniczenia (czas, budżet, zależności)
* Kryteria sukcesu (jak poznasz, że się udało?)

**Szablon – „Pakiet kontekstu”:**

```
Cel: …
Fakty: 1) … 2) … 3) …
Ograniczenia/ryzyka: …
Kryteria sukcesu: …
```

---

## 3) Jak „nakarmić” AI wiedzą (materiały wejściowe)

### 3.1 Co podawać

* Fragmenty dokumentów (zaznaczone kluczowe sekcje)
* Listy faktów i liczb, wyniki ankiet, założenia
* Dotychczasowe decyzje i ich skutki
* Wersje alternatywne / hipotezy do porównania

### 3.2 Jak podawać (format)

* Krótkie bloki (≤300–500 słów) + nagłówki
* Checklisty i **tabele** zamiast esejów
* Jasne **pytanie/akcja na końcu**

**Szablon – „Pakiet do analizy”:**

```
Kontekst (3–5 zdań)
Dane (punktowo)
Pytanie/zadanie (imperatyw)
Oczekiwany format odpowiedzi (np. tabela + rekomendacja)
```

---

## 4) Jak pytać (tryb konsultanta)

### 4.1 Formuły poleceń (kopiuj/wklej)

> „Zdiagnozuj problem: objawy → możliwe przyczyny → testy weryfikacyjne.”
> „Zaproponuj 3 warianty: opis, koszt/czas, ryzyko, wpływ, kiedy stosować.”
> „Zrób sanity check: wskaż założenia o wysokim ryzyku błędu i jak je sprawdzić.”
> „Zarekomenduj: wybierz 1 wariant, powiedz dlaczego teraz i co jeśli nie.”
> „Zared-teamuj: podważ własną rekomendację – wskaż 3 kontrargumenty.”

### 4.2 Wymagany format odpowiedzi

* TL;DR (3–5 zdań) na początku
* Tabela wariantów / matryca decyzyjna
* Lista ryzyk i mitigacji
* Jasna rekomendacja + następny krok (D1, D7)

**Szablon – „Format odpowiedzi, którego oczekuję”:**

```
1) TL;DR
2) Warianty (tabela)
3) Ryzyka + mitigacje
4) Rekomendacja (jedna)
5) Pierwszy mikro-krok (≤30 min)
```

---

## 5) Iteracja (praca krokowa)

### 5.1 Komendy do prowadzenia iteracji

> „Rozwiń tylko punkt 2 (max 10 zdań).”
> „Skróć do planu w 7 krokach.”
> „Dodaj perspektywę sceptyka.”
> „Zamień to na checklistę wdrożeniową.”
> „Przygotuj brief do zarządu (1 slajd: problem → opcje → koszt → ryzyko → decyzja).”

### 5.2 Reset i pamięć

* Co 6–10 wiadomości przypomnij cel:

  > „Przypomnienie celu: [1 zdanie]. Kontynuuj zgodnie z nim.”
* Nowy temat = **nowy wątek** + skrócony profil/kontekst.

---

## 6) Decyzje: jak używać AI i pozostać decydentem

### 6.1 Matryca decyzji (MVP)

* Kryteria: **wpływ, koszt, czas, ryzyko, odwracalność**
* Skala: **1–5**
* Wniosek: wybierasz **najwyższy wpływ / ryzyko do przyjęcia**

**Prompt – „Policz i wybierz”:**

> „Wypełnij matrycę (wpływ/koszt/czas/ryzyko/odwracalność 1–5), podaj wynik i rekomendację. Pokaż obliczenia.”

### 6.2 „Zrób to sam” z pomocą AI

* Traktuj odpowiedzi jako **hipotezy**
* Proś o **dowody/uzasadnienie** i **plan minimalnej weryfikacji (MVP test)**
* Decyzję zatwierdza **Twój rozsądek + minimalny eksperyment**

---

## 7) Jak unikać słabości AI (antywzorce → kontrakcje)

| Słabość (DNA AI)                 | Co mówisz / robisz                                                               |
| -------------------------------- | -------------------------------------------------------------------------------- |
| Halucynacje (wymyślanie)         | „Podaj założenia i niepewności. Jeśli brak danych – powiedz czego potrzebujesz.” |
| Zbyt miły, ogólny ton            | „Bez kurtuazji. Merytorycznie, krytycznie, wprost.”                              |
| Zapominanie kontekstu            | „Przypomnę cel: … Kontynuuj w tym kierunku.” Nowy wątek dla nowego tematu.       |
| Brak krytycyzmu                  | „Dodaj sekcję **Słabe punkty** i **Kiedy nie stosować**.”                        |
| Rozwlekłość                      | „Max 10 zdań + tabela. Usuń dygresje.”                                           |
| Stronniczość/pewność bez podstaw | „Oceń pewność (niska/średnia/wysoka) i wskaż brakujące dane.”                    |
| Zbyt skomplikowany język         | „Napisz dla zarządu – prosto, bez żargonu.”                                      |

---

## 8) Multi-źródła i weryfikacja

**Zawsze proś o:**

* Listę **źródeł do sprawdzenia** (raporty, standardy, benchmarki)
* **Minimalny eksperyment** (co sprawdzić w 24–48 h)
* **Sygnały ostrzegawcze** (co skłoniłoby do zmiany decyzji)

**Prompt – „Zdolność do falsyfikacji”:**

> „Wymień 3 najszybsze testy, które mogą obalić tę tezę. Jakie wyniki uznasz za rozstrzygające?”

---

## 9) Szablony do codziennej pracy (gotowce)

### 9.1 Kickoff nowego tematu

> „Bądź moim konsultantem. Cel: [1 zdanie]. Kontekst: [5 faktów]. Ograniczenia: [czas/budżet]. Kryteria sukcesu: [3]. Zrób: diagnoza → 3 opcje → ryzyka → rekomendacja → 1. krok.”

### 9.2 Brief decyzyjny (dla zarządu)

> „Przygotuj 1-slajdowy brief: Problem, Opcje (3), Koszt/Czas/Ryzyko, Rekomendacja (1), Co jeśli nic nie zrobimy, Pierwszy krok.”

### 9.3 Tryb „Czerwony zespół” (red-team)

> „Podważ rekomendację: wskaż 5 kontrargumentów, 3 luki w danych, 2 alternatywne metryki sukcesu.”

### 9.4 Tryb „Sanity check”

> „Wypisz jawne i ukryte założenia. Oceń ich ryzyko błędu. Zaproponuj testy niskokosztowe.”

### 9.5 Tryb „Brevity”

> „Odpowiadaj w 7 punktach max, bez wstępów, najpierw wnioski.”

---

## 10) Protipy i przypomnienia

### 10.1 Pętle przypominające (gdy tempo spada)

> „Przypomnij mi cel i wskaż 1 najważniejszy następny krok.”
> „Zrób przegląd ryzyk: co ignorujemy?”
> „Jakie założenie ma największą niepewność? Zaproponuj test do 30 min.”

### 10.2 Higiena rozmowy

* Jeden temat = jeden wątek
* Duże materiały → **streszczenie + fragmenty**
* Po 6–10 wiadomościach – **mini-reset** (cel + kryteria)

### 10.3 Decyzyjność

* Jeśli odpowiedź **nie prowadzi do decyzji** – poproś o **warianty + kryteria + rekomendację**
* Jeśli nadal mgliście – poproś o **mapę pytań, które odblokują decyzję**

---

## 11) Gotowe formatki (kopiuj/wklej)

### 11.1 „Mój profil”

> „Jestem [rola]. Decyduję w [obszary]. Styl: [zwięzły/krytyczny/analityczny]. Cenię: [wartości]. Oczekuję: wnioski → uzasadnienie → ryzyka → rekomendacja.”

### 11.2 „Mój kontekst na dziś”

```
Cel: …
Fakty: 1) … 2) … 3) …
Ograniczenia: …
Kryteria sukcesu: …
```

### 11.3 „Zadanie dla konsultanta”

> „Zdiagnozuj → zaproponuj 3 opcje (tabela: opis/koszt/czas/ryzyko/wpływ) → wskaż rekomendację → daj pierwszy krok (≤30 min).”

### 11.4 „Kontrola jakości odpowiedzi”

> „Dodaj sekcję: Założenia, Niepewności, Słabe punkty, Kiedy nie stosować, Minimalny test weryfikacyjny.”

### 11.5 „Reset”

> „Reset: cel to [1 zdanie]. Dostosuj dalsze wnioski pod ten cel.”

---

## 12) Checklista „Czy dobrze korzystam z AI?”

* [ ] Nadałem AI rolę konsultanta i ton odpowiedzi.
* [ ] Dałem profil i kontekst (cel, fakty, ograniczenia, kryteria).
* [ ] Zleciłem zadanie imperatywnie i określiłem format odpowiedzi.
* [ ] Wymagam uzasadnień, wariantów, ryzyk, rekomendacji.
* [ ] Robię iteracje: sanity check, red-team, skróty, briefy.
* [ ] Decyzję podejmuję sam, po minimalnej weryfikacji.
* [ ] Co kilka wiadomości przypominam cel albo robię reset.

---

> **Wskazówka:** dodaj ten plik jako `README.md` w repo wiedzy zespołu i linkuj z niego wzorce promptów oraz przykłady dobrych rozmów z AI.
