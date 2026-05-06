# System Zarządzania Uczelnią (SQL + Python Generator)

Projekt relacyjnej bazy danych obsługującej strukturę uczelni, kadrę akademicką oraz studentów. Zawiera triggery dbające o limity miejsc w grupach oraz automatyczny generator danych.

## Funkcje
- **Struktura SQL**: Pełny schemat bazy (tabele, relacje, klucze obce).
- **Automatyzacja**: Skrypt Python generujący setki realistycznych rekordów (350 studentów, 30 wykładowców).
- **Logika biznesowa**: Triggery pilnujące limitów zapisów.

## Jak uruchomić?
1. Sklonuj repozytorium.
2. Uruchom skrypt generujący dane:
   ```bash
   python generator.py
