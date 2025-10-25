Program: Klasyfikacja siły wiatru
Program napisany w języku C, który klasyfikuje siłę wiatru według podanej prędkości w m/s. Program przypisuje klasę B i nazwę odpowiadającą standardowej skali Beauforta.

Informacje techniczne
Język: C
Edytor: Microsoft Visual Studio Code
Kompilator: Clang (clang -Wall)
System: Windows
💡 Program skompilowany przy użyciu kompilatora Clang. Korzystałem z edytora MS Visual Studio Code.

Kompilacja
Aby skompilować program, w terminalu uruchom:

clang -Wall zad1.c
Podczas kompilacji może pojawić się ostrzeżenie:

warning: 'scanf' is deprecated: This function or variable may be unsafe. Consider using scanf_s instead.
Jest to normalne w środowisku Visual Studio. Możesz je zignorować lub użyć scanf_s. Aby wyłączyć ostrzeżenie, dodaj na początku pliku:

#define _CRT_SECURE_NO_WARNINGS
Uruchomienie programu
Po kompilacji uruchom plik wykonywalny:

zad1.exe
Program poprosi o podanie prędkości wiatru w m/s i zwróci klasę wiatru:

Przykłady działania
C:\Users\X\Desktop\homework>zad1.exe
Podaj predkosc wiatru w m/s: 2
B=1 (Light Air)
C:\Users\X\Desktop\homework>zad1.exe
Podaj predkosc wiatru w m/s: 3
B=2 (Light Breeze)
Działanie programu
Program prosi użytkownika o podanie prędkości wiatru w m/s.
Na podstawie wartości prędkości wiatru przypisuje klasę wiatru i nazwę według skali Beauforta.
Wyświetla wynik w formacie:
B=<klasa> (<nazwa>)
👤 Autor
Imię / Pseudonim: Piotr
Rok: 2025
Środowisko: Visual Studio Code + Clang


