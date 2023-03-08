## Wprowadzenie
### Wymagania
* [JetBrains IntelliJ IDEA](https://www.jetbrains.com/idea/).
* (można zainstalować przez środowisko IntelliJ) Min. Java Development Kit 11 (JDK11) z Oracle, OpenJDK lub AdoptOpenJDK.
* Rozdział 1 i 2 z Java Podstawy, Cay S Horstmann'a.

### Historia
[![YouTube](https://img.youtube.com/vi/w1EDAKWzE_A/0.jpg)]([https://www.youtube.com/watch?v=UmX4kyB2wfg](https://youtu.be/w1EDAKWzE_A?t=58))

https://www.youtube.com/watch?v=w1EDAKWzE_A

#### Główne zasady
1.  **Prosty**
2.  **Obiektowy**
3.  **Sieciowy** 
4.  **Niezawodny** 
5.  **Bezpieczny** 
6.  **Niezależny od architektury** 
7.  **Przenośny** 
8.  **Interpretowany**
9.  **Wysokowydajny**
10. **Wielowątkowy**
11. **Dynamiczny**

### Zasada działania JVM
Java Virtual Machine (Wirtualna Maszyna Javy) jest abstrakcyjną maszyną zapewniającą specyfikację uruchomienia środowiska wykonawczego interpretującego kod bajtowy Java. 

Do jej podstawowych zadań należy:
* Wczytywanie kodu
* Weryfikacja kodu
* Wykonanie kodu

Diagramy przedstawiające proces kompilacji i wykonania (interpretacji)

![Kompilacja](https://user-images.githubusercontent.com/77734214/223571589-03a0cb1d-50e4-4b7a-92ea-7ce84eccebbf.png)

![Interpretacja](https://user-images.githubusercontent.com/77734214/223628705-22cd220a-5120-424f-ac2e-d75bf2326352.png)

W celu poprawy wydajności i optymalizacji, kod bajtowy w Java jest wykonywany z wykorzystaniem metody [**JIT (Just-In-Time)**](https://pl.wikipedia.org/wiki/JIT_(informatyka)). Jest to metoda wykonywania programów polegająca na ich kompilacji do kodu maszynowego w momencie przed wykonaniem danego fragmentu kodu. 


### Narzędzia wiersza poleceń 

* jshell - interpreter java, pozwalający na prototypowanie (działa podobnie jak konsola python'a)
* java - środowisko wykonawcze 
* javac - kompilator java

![jshell](https://user-images.githubusercontent.com/77734214/223543361-d1213670-9753-4927-9b75-970ac16df464.png)

### Typy danych
#### Prymitywne typy danych
|     Typ         |     Bity     |     Minimalna   wartość    |     Maksymalna   wartość     |     Zakres                                                            |
|-----------------|--------------|----------------------------|------------------------------|-----------------------------------------------------------------------|
|     byte        |     8        |     -128                   |     127                      |     od +127 do -128                                                   |
|     char        |     16       |     0                      |     216-1                    |     wszystkie znaki Unicode                                           |
|     short       |     16       |     -215                   |     215-1                    |     od +32 767 do -32 768                                             |
|     int         |     32       |     -231                   |     231-1                    |     od +2 147 483 647 do  -2,147,483,648                              |
|     long        |     64       |     -263                   |     263-1                    |     od +9 223 372 036 854 775   807 do -9 223 372 036 854 775 808     |
|     float       |     32       |     2-149                  |     (2-2-23)·2127            |     od  3.4028235 E+38 do 1.4 E-45                                    |
|     double      |     64       |     2-1074                 |     (2-2-52)·21023           |     od 1.7976931348623157 E+308 to   4.9 E-324                        |
|     boolean     |              |                            |                              |     false, true                                                       |
|     void        |              |                            |                              |                                                                       |
#### Obiektowe typy danych
Przykład obiektowej reprezentacji typów prostych.

| Typ       | Przykład                |
|-----------|-------------------------|
| Byte      | Byte b = 1;             |
| Character | Character ch = '你';    |
| Short     | Short s = 125;          |
| Integer   | Integer i = 10000;      |
| Long      | Long l = 98432563L;     |
| Float     | Float f = 1.14f;        |
| Double    | Double d = 4.3446d;     |
| Boolean   | Boolean isDone = true;  |
| Void      |                         |

### Środowisko Programistyczne
Na zajęciach będziemy korzystać z [IntelliJ IDEA](https://pl.wikipedia.org/wiki/IntelliJ_IDEA) w wersji Community.

Widok projektu:
![obraz](https://user-images.githubusercontent.com/77734214/223543572-38378f8e-81c9-4dab-baf1-608e56307611.png)

Instalacja brakującego SDK:
![obraz](https://user-images.githubusercontent.com/77734214/223548922-d9d78ae3-d2ca-4013-af1a-26f500a162d7.png)

Uruchomienie aplikacji z poziomu IDE:
![obraz](https://user-images.githubusercontent.com/77734214/223625427-a7ed37b6-08b0-45de-b985-5843f31e826c.png)



### Zadania
1. Korzystając z konsoli jshell sprawdź czym różnią się typy prymitywne od typów obiektowych.
2. Pobierz z strony https://horstmann.com/corejava/index.html Kod Źródłowy dla wydania 11. i go rozpakuj.
3. Otwórz w IntelliJ folder *v1ch02/Welcome*. Następnie przejdź do zakładki *terminal* (na dole) i sprawdź czy komendy `java` oraz `javac` są poprawne. 
4. Skompiluj plik `Welcome.java` i go uruchom.
5. Napisz program w którym wyświetlisz jakąś informację o sobie na ekranie.
6. Napisz program w którym podstawowe informacje o sobie (np. wiek, wzrost, waga) będą znajdować się w zmiennych i następnie wyświetl je na ekranie.
 
### Zadanie domowę
📖 Przeczytać rozdział 3. z Java Podstawy, Cay S Horstmann'a.
