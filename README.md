# Analiza sprzedaży

Projekt wykonany w ramach laboratorium z eksploracji danych.

## Opis danych

Zbiór zawiera 12 fikcyjnych zamówień z dwóch kanałów sprzedaży: internetowego i sklepu stacjonarnego.

## Technologie

Python, pandas, matplotlib, Jupyter, Streamlit, GitHub, Render.

## Przeprowadzone analizy

- Sprawdzenie struktury danych, braków i duplikatów.
- Ujednolicenie nazw kanałów sprzedaży.
- Obliczenie liczby zamówień, sumy sprzedaży, średniej i mediany.
- Przedstawienie wyników na wykresie słupkowym.

## Uruchomienie lokalne

Zainstaluj wymagane biblioteki:

`pip install -r requirements.txt`

Uruchom aplikację:

`streamlit run app.py`

## Aplikacja

https://laboratorium-eda-290e.onrender.com/

## Wnioski

1. Sprzedaż internetowa wyniosła 1490 zł, a sprzedaż w sklepie stacjonarnym 760 zł. Kanał internetowy wygenerował większy przychód.
2. W obu kanałach zrealizowano po 6 zamówień, ale średnia wartość zamówienia internetowego była wyższa niż w sklepie stacjonarnym.