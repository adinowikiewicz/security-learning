# Day 1 – Git Basics

## Co zrobiłem:
- mkdir (tworzenie folderu)
- cd / pwd / ls (poruszanie się po systemie)
- touch (tworzenie pliku)
- cat (podgląd pliku)
- echo + >> (dopisywanie do pliku)
- git init (tworzenie repo lokalnego)
- git status (sprawdzanie stanu)
- git add (dodanie do staging area)
- git commit (zapis punktu w historii)
- git log (podgląd historii)
- różnica między working directory, staging area i commit

## Model mentalny:
Working directory → Staging area → Commit → Log

## Wnioski:
Git daje historię zmian, możliwość cofania i kontrolę nad wersjami.

Powiedzmy że tworzę jakis folder/katalog w którym będę trzymał rożne pliki. Poprzez komende git 
init zamieniam ten folder w repozytorium git i dodaje do tego folderu niewidoczny folder .git gdzie 
zapisywane są wszystkie zmiany, historia commitów, daty zmian, wszystkie poprzednie wersje 
poprzednich zmian itd. Bez tego nie mielibyśmy wglądu jak się zmieniał nasz katalog, jakie zmiany 
zrobiliśmy kiedyś, jak wyglądał na danym etapie pracy itd. Git nam to wszystko "archiwuje". 
