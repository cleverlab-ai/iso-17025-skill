# ISO/IEC 17025:2017 — Przewodnik walidacji metod

## Kiedy wymagana jest walidacja (7.2.2.1)

Walidacja jest wymagana dla:
- Metod nieznormalizowanych
- Metod opracowanych przez laboratorium
- Metod znormalizowanych stosowanych poza ich zamierzonym zakresem
- Zmodyfikowanych metod znormalizowanych (rozszerzenia/modyfikacje)

Weryfikacja (nie pełna walidacja) wystarcza dla:
- Metod znormalizowanych stosowanych w ich zakresie, w celu potwierdzenia że laboratorium może prawidłowo wykonać metodę

## Parametry walidacyjne (7.2.2.3)

### Wymagane charakterystyki do oceny

| Parametr | Opis | Kiedy wymagany |
|----------|------|----------------|
| **Selektywność/Specyficzność** | Zdolność pomiaru analitu bez interferencji ze składników matrycy | Zawsze |
| **Liniowość** | Zakres, w którym odpowiedź jest proporcjonalna do stężenia | Metody ilościowe |
| **Zakres roboczy** | Przedział stężeń analitu, dla którego metoda daje akceptowalne wyniki | Metody ilościowe |
| **Dokładność (Prawdziwość)** | Bliskość średniego wyniku do wartości prawdziwej/akceptowanej (obciążenie/odzysk) | Zawsze dla ilościowych |
| **Precyzja — Powtarzalność** | Zmienność w tych samych warunkach (ten sam operator, wyposażenie, krótki czas) | Zawsze |
| **Precyzja — Odtwarzalność wewnątrzlaboratoryjna** | Zmienność w laboratorium (różni operatorzy, wyposażenie, dni) | Zalecane |
| **Precyzja — Odtwarzalność międzylaboratoryjna** | Zmienność między laboratoriami (z badań międzylaboratoryjnych) | Gdy dostępne |
| **Granica wykrywalności (LOD)** | Najniższa ilość, która może być wykryta (niekoniecznie oznaczona ilościowo) | Gdy oczekiwane wyniki bliskie LOD |
| **Granica oznaczalności (LOQ)** | Najniższa ilość, która może być oznaczona ilościowo z akceptowalną precyzją/dokładnością | Metody analizy śladowej |
| **Odporność (Robustness)** | Odporność na małe, celowe zmiany parametrów metody | Zalecane |
| **Niepewność pomiaru** | Parametr charakteryzujący rozrzut wartości przypisywanych mierzandowi | Zawsze |
| **Czułość** | Zmiana odpowiedzi na jednostkową zmianę stężenia | Przy porównywaniu metod |
| **Efekty matrycowe** | Wpływ matrycy próbki na pomiar | Gdy analizowane różne matrycami |

### Walidacja metod mikrobiologicznych — parametry specyficzne

| Parametr | Opis |
|----------|------|
| **Prawdziwość względna** | Porównanie z metodą referencyjną na próbkach naturalnie zanieczyszczonych lub sztucznie skażonych |
| **Czułość względna** | Stosunek wyników pozytywnych wykrytych metodą alternatywną vs referencyjną |
| **Specyficzność względna** | Stosunek wyników negatywnych potwierdzonych metodą alternatywną vs referencyjną |
| **Dokładność względna** | Stopień zgodności między metodą alternatywną a referencyjną |
| **Względna granica wykrywalności** | Najniższy poziom skażenia możliwy do wiarygodnego wykrycia |
| **Inkluzywność** | Zdolność wykrycia docelowych organizmów z różnych źródeł |
| **Ekskluzywność** | Brak fałszywie dodatnich wyników od organizmów niedocelowych |

## Struktura planu walidacji

```
1. Cel
   - Jaka metoda jest walidowana
   - Zamierzone zastosowanie/zakres (anality, matrycami, zakresy stężeń)
   - Odniesienie do normy lub procedury

2. Parametry walidacyjne
   - Które parametry będą oceniane (uzasadnione na podstawie zamierzonego zastosowania)
   - Kryteria akceptacji dla każdego parametru (zdefiniowane PRZED walidacją)

3. Plan eksperymentalny
   - Liczba pomiarów/powtórzeń
   - Poziomy stężeń
   - Matrycami do przebadania
   - Materiały odniesienia/wzorce do użycia
   - Metody statystyczne do oceny danych

4. Wymagane zasoby
   - Personel (z wymaganiami kompetencyjnymi)
   - Wyposażenie i odczynniki
   - Materiały odniesienia/wzorce
   - Harmonogram

5. Kryteria akceptacji
   - Zdefiniowane dla każdego parametru PRZED rozpoczęciem eksperymentów
   - Na podstawie: wymagań klienta, limitów regulacyjnych, celów wydajności metody
```

## Struktura raportu z walidacji (7.2.2.4)

Raport z walidacji powinien zawierać:

1. **Identyfikacja metody** — tytuł, wersja, odniesienie
2. **Zakres** — analit(y), matryca/matrycami, zakres
3. **Procedura walidacyjna** — plan eksperymentalny, użyte materiały
4. **Specyfikacja wymagań** — kryteria akceptacji
5. **Wyniki dla każdego parametru** — dane, analiza statystyczna
6. **Stwierdzenie przydatności do zamierzonego celu** — wniosek czy metoda spełnia wymagania
7. **Wszelkie ograniczenia lub warunki** zidentyfikowane podczas walidacji
8. **Zatwierdzenie** — data, osoba odpowiedzialna, autoryzacja

## Przykładowe kryteria akceptacji

### Badania chemiczne
| Parametr | Typowe kryterium |
|----------|-----------------|
| Odzysk | 80-120% (zależy od stężenia i matrycy) |
| Powtarzalność (RSD) | <5-10% (zależnie od poziomu stężenia) |
| Odtwarzalność wewnątrzlab. (RSD) | <10-15% |
| Liniowość (R²) | >0,995 (typowo >0,999) |
| LOD | < 1/10 limitu regulacyjnego |
| LOQ | < 1/3 limitu regulacyjnego |

### Badania mikrobiologiczne
| Parametr | Typowe kryterium |
|----------|-----------------|
| Dokładność względna | >90% zgodności z metodą referencyjną |
| Czułość względna | >90% |
| Specyficzność względna | >90% |
| Odsetek fałszywie dodatnich | <5% |
| Odsetek fałszywie ujemnych | <5% |

## Ważne uwagi

- Walidacja powinna być tak rozległa, jak to konieczne do spełnienia potrzeb zamierzonego zastosowania (7.2.2.1)
- Gdy wprowadzane są zmiany w zwalidowanej metodzie, wpływ zmian musi być określony, a jeśli istotny — przeprowadzona nowa walidacja (7.2.2.2)
- Wyniki walidacji, w tym stwierdzenie przydatności, muszą być zapisane i przechowywane (7.2.2.4)
- Kryteria akceptacji muszą być zdefiniowane PRZED walidacją, a nie po zobaczeniu wyników
