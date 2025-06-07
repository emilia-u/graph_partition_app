#  Graph Partition & Visualization Tool

Projekt służy do **ładowania, analizy, podziału i wizualizacji dużych grafów** zapisanych w formacie CSR lub CSRRG. Umożliwia użytkownikowi **przeglądanie grafu przed i po podziale** na spójne komponenty — z zachowaniem czytelności i interaktywności interfejsu.


##  Główne funkcje

- **Wczytywanie grafów** z plików binarnych (`.bin`) i tekstowych (`.csrrg`) w formacie CSR
-  **Podział grafu** na spójne komponenty z uwzględnieniem równowagi
-  **Wizualizacja grafu przed i po podziale**:
  - Zoomowanie, przesuwanie, wyśrodkowanie
  - Kolorowanie komponentów
  - Dynamiczne rysowanie krawędzi i wierzchołków
-  **Algorytm siłowy** (force-directed) do rozmieszczania wierzchołków


##  Wymagania

- Java 17+
- Maven (do budowania projektu)

##  Jak uruchomić

1. Wgraj graf w pliku `.csrrg` lub `.bin`
2. Interaktywna wizualizacja grafy pojawi się na ekranie
3. Skorzystaj z dostepnych opcji i dowiedz się więcej o grafie. 

---

Projekt stworzony w ramach projektu na studiach.



