Sehr gut, du hast deine Projekte beschrieben und direkt verlinkt – das ist genau die richtige Richtung!
Jetzt verbessern wir es gemeinsam, **Schritt für Schritt**, damit es **klarer, selbstbewusster und professioneller** klingt – aber weiterhin **authentisch** bleibt.

---

### ✨ **Überarbeitete Version deines GitHub-Portfolios:**

---

# 🌟 GitHub – Meine besten Projekte

Hier zeige ich einige meiner praktischen Arbeiten mit **Python**, **SCSS** und mehr.
Jedes Projekt habe ich genutzt, um bestimmte Konzepte in der Tiefe zu verstehen und umzusetzen.

---

### 🔹 1. Berge-Website mit SCSS (responsive Design)

Ich habe eine responsive Website mit **SCSS** entworfen und umgesetzt. Dabei habe ich mit Variablen, Mixins, Grid-System und Medienabfragen gearbeitet.
Aktuell entwickle ich ein echtes Webprojekt mit SCSS, um meine Fähigkeiten weiter zu verbessern.

Zur Code : https://github.com/MaherGhazzawi/professionelle-Berge-Website-.git

---

### 🔹 2. Taschenrechner in Python

Ein einfacher Konsolen-Taschenrechner mit **Funktionen für Addition, Subtraktion, Multiplikation und Division**.
Ich habe mit einer **`while`-Schleife** gearbeitet, um eine benutzerfreundliche Wiederholung der Berechnungen zu ermöglichen.

Zur Code : https://github.com/MaherGhazzawi/Taschenrechner-Python.git

---

### 🔹 3. Caesar-Verschlüsselung in Python

Dieses Projekt zeigt eine klassische **Verschlüsselungsmethode** – die Caesar-Chiffre.
Ich habe die Buchstaben mit `ord()` und `chr()` um einen festen Wert verschoben und dabei **Groß- und Kleinbuchstaben separat behandelt**, um die Logik korrekt umzusetzen.

#### Ausschnitt aus der Funktion `encrypt_caesar`:

```python
def encrypt_caesar(text, shift):
    result = ""
    for char in text:
        if char.isalpha():
            start = ord("A") if char.isupper() else ord("a")
            result += chr((ord(char) - start + shift) % 26 + start)
        else:
            result += char
    return result
```

 `char.isalpha()` prüft, ob es sich um einen Buchstaben handelt.
 `ord()` gibt den ASCII-Wert, `chr()` wandelt zurück.
 `% 26` sorgt dafür, dass die Rotation im Alphabet bleibt.
 4.Ich habe eine andere Website entwickelt und meine Kenntnise im SCSS vertieft : 
 Zur code : https://github.com/MaherGhazzawi/Resto-Website-SCSS/blob/main/index.html
 

Zur Code : https://github.com/MaherGhazzawi/Caeser-Code/blob/main/cipher_scroll_caesar.py



    
