# AiSD

## Zasady dodawania treści
* Należy dodawać linki do rozwiązań z egzaminu w formacie "CZa Zb c", 
gdzie:
'a' - odpowiednia część egzaminu, 
'b' - numer zadania, 
'c' - rok egzaminu
np. [CZ1 Z10 1920]()
* Format podlinkowanych rozwiązań nie ma znaczenia


## [Wizualizacje algorytmów](https://www.cs.usfca.edu/~galles/visualization/Algorithms.html)

## [Dysk](https://drive.google.com/drive/folders/1eiO0eVoxAKAhwgPH-zwNZOH7yFXUc1MH)


## Repozytoria innych studentów
[Mbronek7](https://github.com/mbronek7/hycaisd)

## Algorytmy MST
#### 1. Algortym Boruvki
#### 2. Algorytm Kruskala
#### 3. Algorytm Prima
#### Zadania z egzaminów
* [CZ1 Z1 2010](https://github.com/ithrasil/AiSD/blob/master/Egzaminy/Cz%C4%99%C5%9B%C4%87%201/2010/1.md)

## Algorytmy wyszukujące najkrótsze ścieżki w grafie
#### 1. Algorytm Dijkstry
#### Zadania z egzaminów
* [CZ1 Z2 2010](https://github.com/ithrasil/AiSD/blob/master/Egzaminy/Cz%C4%99%C5%9B%C4%87%201/2010/2.md)

## Algorytmy zachłanne
#### Zadania z egzaminów

## Algorytmy "dziel i zwyciężaj"
#### Zadania z egzaminów

## Programowanie dynamiczne
#### 1. Przejście po tablicy (najbardziej optymalna trasa po kosztach)
#### 2. LCS (najdłuższy wspólny podciąg)
#### 3. Optymalna kolejność mnożenia macierzy
#### 4. Przynależność do języka bezkontekstowego
#### 5. drabina (graf): 
#### Zadania z egzaminów

## Sortowanie
#### 1. Przez zliczanie (counting sort)
#### 2. Kubełkowe (bucket sort)
#### 3. Leksykograficzne ciągów jednakowej długości
#### 4. Leksykograficzne ciągów niejednakowej długości. 
przykład zastosowania: sprawdzanie czy ukorzenione drzewa są izomorficzne (jak sprawdzić dla nieukorzenionych do zastanowienia)
#### Zadania z egzaminów

## Dolne granice
#### 1. min i max (gra z adwersarzem)
#### 2. Drzewa decyzyjne
#### 3. Liniowe drzewa decyzyjne
#### Zadania z egzaminów

## Quicksort
#### 1. Procedura partition
#### 2. Wybór pivota (deterministyczny i zrandomizowany)
#### 3. Średni koszt algorytmu
#### Zadania z egzaminów

## Problem selekcji (wybór k-tego elementu)
#### 1. Wybór drugiego elementu
#### 2. Algorytm hore'a
#### 3. Magicznych piątek
#### 4. LazySelect (zrandomizowany algorytm wyznaczania mediany)
#### Zadania z egzaminów

## Drzewa AVL
[Wizualizacja operacji w drzewie AVL](https://www.cs.usfca.edu/~galles/visualization/AVLtree.html)
#### 1. Ograniczenie wysokości (dowód, że jest O(logn))
#### 2. [insert (rotacje)](https://www.geeksforgeeks.org/avl-tree-set-1-insertion/)
#### 3. [delete (rotacje)](https://www.geeksforgeeks.org/avl-tree-set-2-deletion/)
#### 4. Drzewo AVL jako lista (logarytmiczny dostęp do każdego elementy)
#### Zadania z egzaminów
* [2019 CZ1 Z1](https://github.com/ithrasil/AiSD/blob/master/Egzaminy/Cz%C4%99%C5%9B%C4%87%201/2019/1.md)

## B-drzewa
#### 1. Definicja/struktura
#### 2. operacja insert
#### 3. Koszt operacji
#### Zadania z egzaminów

## Drzewa czerwono-czarne
#### 1. Definicja
#### 2. Ograniczenie wysokości (dowód, że jest O(logn))
#### 3. Rotacje
#### 4. Wstawianie elementu (przywracanie własności drzewa czerwono-czarnego)
#### 5. Związek między B-drzewami a drzewami czerwono-czarnymi (z 2-3-4 B-drzewa stworzyć drzewo czerwono-czarne)
#### Zadania z egzaminów

## Kopce dwumianowe 
#### 1. Drzewa dwumianowe 
#### 2. Uwagi implementacyjne 
#### 3. Rząd
#### 4. Drzewo B_i ma 2^i wierzchołków (indukcja)
#### 5. Wersja eager i lazy (jak działają, meld, deletemin)
#### 6. Operacje typu insert, join
#### 7. Zamortyzowany koszt procedury insert (wersja eager)
#### 8. Zamortyzowany koszt procedury deletemin (wersja lazy)
#### Zadania z egzaminów

## Kopce Fibbonaciego 
#### 1. Przykład zastosowania (Dijkstra)
#### 2. Struktura
#### 3. Operacja decrement, cut (kaskadowy) 
#### 4. Zamortyzowany koszt (decrement)
#### 5. Operacja deletemin(h) (dowód, że dla każdego wierzchołka x kopca Fibb o rzędzie k, drzewko zakorzenione w x ma rozmiar wykładniczy względem k, wniosek o maksymalnym rzędzie w kopcu fibb)
#### Zadania z egzaminów
* [2010 CZ1 Z3](https://github.com/ithrasil/AiSD/blob/master/Egzaminy/Cz%C4%99%C5%9B%C4%87%201/2010/3.png)

## Drzewa Splay
#### 1. Operacje na drzewach samoorganizujących się (join, split, splay)
#### 2. Implementacja splay (odpowiednie rotacje)
#### 3. Analiza zamortyzowana operacji splay
#### Zadania z egzaminów

##  Drzewce 
#### 1. Dowód, że dla każdego zbioru elementów typu <klucz, priorytet> można utworzyć drzewiec (zakładamy, że priorytety są różne, warto też wiedzieć co jeśli wystąpią takie same)
#### 2. Losowy drzewiec
#### 3. operacje insert, delete
#### 4. Oczekiwany koszt delete
#### Zadania z egzaminów

##  Union Find 
#### 1. Przykład zastosowania
#### 2. definicja jak działa union i find
#### 3. Proste rozwiązania (naiwne)
#### 4. Struktura drzewiasta
##### 4.1. Sposób zbalansowany Union
##### 4.2. Kompresja ścieżek Find
#### 5. Szacowanie czasu wykonywania ciągu operacji union i find (definicje rzędu wierzchołka i rzędu grupy i parę faktów, wszystko dotyczy tego dowodu)
#### 6. Szacowanie czasu wykonywania ciągu operacji union i find gdy wierzchołki przy kompresji ścieżek nie byłyby podpinane pod korzeń, tylko pod swojego dziadka
#### Zadania z egzaminów


