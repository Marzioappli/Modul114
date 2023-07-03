# 20.06.23
## Symmetrische Verschlüsselung


Aufgaben:

Aufgabe 1:
![grafik](https://github.com/Marzioappli/Modul114/assets/90458224/7974e9bc-5bd8-4481-83a0-261d10d081d4)

Aufgabe 3:

Verschlüsseln sie die Dezimalzahl 4711 von Hand als XOR-Stromchiffre. Der binäre Schlüssel lautet: 1000'1101. Zur Kontrolle entschlüsseln sie die erhaltene Chiffre wieder.
Hinweis: Sie müssen die Dezimalzahl zuerst in eine 16-Bit Binärzahl umwandeln (Führende Nullen nicht weglassen). Sollte der Schlüssel für die Verschlüsselung zu kurz sein, wird dieser mehrmals wiederholt. Der Datenstrom soll in dieser Aufgabe mit der Übertragung des MSB's, also von links nach rechts beginnen.

### Lösung:
1 Schritt: 4711 = 0000 0001 0011 0111 -->  Der binäre Schlüssel lautet: 1000 1101 <br>
2 Schritt: Da der Schlüssel kürzer ist als die Daten, wird er wiederholt: --> Schlüssel: 1000 1101 1000 1101 1000 1101 <br>
3 Schritt: Daten: 0000 0001 0011 0111, Schlüssel: 1000 1101 1000 1101 (XOR Verschlüsselung) <br>
4 Schritt: Chiffre: 1000 1100 1011 1010, Schlüssel: 1000 1101 1000 1101 <br>
#### 5 Schritt: Entschlüsselte Daten: 0000 0001 0011 0111

Tag-1

Wir mit einem Kahoot begonnen damit er eine übersicht davon hat wie viel wir schon wissen. Bestandesaufnahme "Ihr Vorwissen"

Start mit dem Thema "Daten codieren" Danach hat er uns gezeigt wie man verschieden Files den Binär code anschaut.
HEX-Editor (https://hexed.it) damit kann man Files öffnen in Bits es werden immer 16 mal 4 bits zusammen gefasst
Zahlensysteme, numerische Codes

    Wandeln sie die folgende Dezimalzahl ohne Taschenrechner in die entsprechende Binärzahl um: 911

    911 ÷ 2 = 455 Rest 1

    455 ÷ 2 = 227 Rest 1

    227 ÷ 2 = 113 Rest 1

    113 ÷ 2 = 56 Rest 1

    56 ÷ 2 = 28 Rest 0

    28 ÷ 2 = 14 Rest 0

    14 ÷ 2 = 7 Rest 0

    7 ÷ 2 = 3 Rest 1

    3 ÷ 2 = 1 Rest 1

    1 ÷ 2 = 0 Rest 1

    Die Binärzahl für 911 lautet also 1110001111.

    Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Dezimalzahl um: 1011'0110

    128 | 64 | 32 | 16 | 8 | 4 | 2 | 1

    1 0 1 1 0 1 1 0

    128 + 32 + 16 + 4 + 2 = 182

    Wandeln sie die folgende Binärzahl ohne Taschenrechner in die entsprechende Hexadezimalzahl um: 1110'0010'1010'0101

    1110 -> E

    0010 -> 2

    1010 -> A

    0101 -> 5

    Die Binärzahl 1110'0010'1010'0101 entspricht der Hexadezimalzahl E2A5.

