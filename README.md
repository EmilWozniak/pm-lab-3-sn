# Parametry projektu

Nazwa: pm-lab-3  
Autor: Paweł Dąbal (pawel.dabal@wat.edu.pl)  
Opis: Projekt bazowy repozytorium na trzecie spotkanie laboratoryjne z przedmiotu _Technika mikroprocesorowa_.  
Wersja: v1.0  
Data: 14.12.2020r.

# Informacje o studencie

Imię i nazwisko studenta: Emil Woźniak  
Numer albumu: 72558
Grupa studencka: WEL18DE1S1

# Odpowiedzi do pytań z instrukcji
1. W jaki sposób można rozbudować funkcjonalność programu w przypadku gdzy liczba naciśnięć przycisku przekroczy określoną ilość?
Aby rozbudować funkcjonalność programu w przypadku gdzy liczba naciśnięć przycisku przekroczy określoną ilość, należy w kodzie programu po instrukcji w linijce 26, dodać pętle wewnętrzną (np. if), która będzie wprowadzała określoną przez użytkownika maksymalną wartość naciśnięć przycisku, po której program np. wyłączy się.
2. W jaki sposób można zwiększyć liczbę obsługiwanych poleceń oraz liczbę obsługiwanych parametrów?
Aby zwiększyć liczbę obsługiwanych poleceń i parametrów, należy zwiększyć maksymalny czas przez który polecenie będzie odbierane (linia 11 w kodzie programu - Serial.setTimeout(...)).