# 20.06.23
## Symmetrische Verschlüsselung


Aufgaben:

Aufgabe 1:
![grafik](https://github.com/Marzioappli/Modul114/assets/90458224/7974e9bc-5bd8-4481-83a0-261d10d081d4)

Aufgabe 3:

Verschlüsseln sie die Dezimalzahl 4711 von Hand als XOR-Stromchiffre. Der binäre Schlüssel lautet: 1000'1101. Zur Kontrolle entschlüsseln sie die erhaltene Chiffre wieder.
Hinweis: Sie müssen die Dezimalzahl zuerst in eine 16-Bit Binärzahl umwandeln (Führende Nullen nicht weglassen). Sollte der Schlüssel für die Verschlüsselung zu kurz sein, wird dieser mehrmals wiederholt. Der Datenstrom soll in dieser Aufgabe mit der Übertragung des MSB's, also von links nach rechts beginnen.

### Lösung:
1 Schritt: 4711 = 0000 0001 0011 0111 -->  Der binäre Schlüssel lautet: 1000 1101
2 Schritt: Da der Schlüssel kürzer ist als die Daten, wird er wiederholt: --> Schlüssel: 1000 1101 1000 1101 1000 1101
3 Schritt: Daten: 0000 0001 0011 0111, Schlüssel: 1000 1101 1000 1101 (XOR Verschlüsselung)
4 Schritt: Chiffre: 1000 1100 1011 1010, Schlüssel: 1000 1101 1000 1101
#### 5 Schritt: Entschlüsselte Daten: 0000 0001 0011 0111
