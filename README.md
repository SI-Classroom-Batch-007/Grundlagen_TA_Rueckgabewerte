
<h1 align="center">Grundlagen der Programmierung</h1>
<h3 align="center">Funktionen</h3>
<br>

<p align="center">
  <img src="img/meme.jpeg" />
</p>

#### Beschreibung:

- Willkommen zurück zu den Übungsaufgaben von Tag 12! Heute habt ihr alles rund um das Thema Rückgabewert gelernt. Wenden wir gleich einmal das Gelernte an!

#### Hinweise zur Bearbeitung:

- Achte auf einen sauberen Quellcode, insbesondere Einrückungen sind wichtig!

---

<details>
<summary><b>Aufgabe 1 - Was passiert hier? </b></summary>

In dieser Aufgabe sind Codeausschnitte gegeben und du sollst beschreiben, was diese tun.
Schreibe die Lösung in den Kommentar in der Datei.
a)
- Schau dir den nachfolgenden Code an und beschreibe kurz in eigenen Worten, was hier passiert.

```
fun sub(): Int {
    var number1 = 28
    var number2 = 13
    return number1 - number2
}

fun main() {ㅤㅤ
    println(sub())
}

```

b)

- Schau dir den nachfolgenden Code an und beschreibe kurz in eigenen Worten, was hier passiert.

```

fun favoriteColor(): String {
    val colors: List<String> = listOf("Rot", "Blau", "Gelb", "Grün", "Lila", "Pink")
    var myColor: String = colors[colors.size-4]
    return myColor
}

fun main() {
    println(favoriteColor())
}

```

c)

Schau dir den nachfolgenden Code an und schreibe auf in welcher Reihenfolge die Zeilen abgearbeitet werden.

```
1 fun firstNumber(): Int {
2     return (20 - 18) * 6
3 }

4 fun secondNumber(): Int {
5     return 25 / 5 
6 }

7 fun main() {
8     val result = firstNumber() * secondNumber()
9     println(result)
10 }
```

**Modul für die Aufgabe:** *Aufgabe1*  
**Datei für die Aufgabe:** *Textabgabe.kt* 

</details>

---

<details>
<summary><b>Aufgabe 2 - Funktion + Rückgabewert implementieren und aufrufen </b></summary>

- Schreibe eine Funktion ``tenTimes``, die das zehnfache einer vom Nutzer eingelesenen Zahl zurückgeben soll.
- Gebe den Rückgabewert in einem print-Statement in der main Funktion aus

**Modul für die Aufgabe:** *Aufgabe2*  
**Datei für die Aufgabe:** *ReturnImplementieren.kt*

</details>

---

<details>
<summary><b>Aufgabe 3 - Funktionen entwerfen I </b></summary>

In dieser Aufgabe sollst du ein paar Funktionen entwerfen, um etwas Übung zu bekommen.
Achte dabei auf den richtigen Rückgabewert. 
Prüfe dann jede Funktion programmatisch, indem du sie in der main() Funktion, 
wie in Aufgabe 1, aufrufst und den Rückgabewert in der Konsole ausgibst.

Ein Beispiel:

```

fun main() {
    println(aFunction())
}

fun aFunction(): String {
    return "Das ist eine Funktion!"
}

```

a)

- Schreibe eine Funktion, die das Ergebnis einer Addition zweier beliebiger Zahlen zurückgibt.

b)

- Schreibe eine Funktion, die eine Umrechnung von Euro in Dollar ermöglicht.
- Lese dafür eine Nutzereingabe ein und wandle diese in die gewünschte Währung um
- Die Funktion soll das Ergebnis zurückgeben
- Hinweis: 1€ entspricht 1.08$

c)

- Schreibe eine Funktion, in der du den Nutzer auf der Konsole begrüßt 
- Gebe die Funktion in einem print-Statement in der main-Funktion aus

d)

- Schreibe eine Funktion, die eine Liste vom Typ String zurückgibt.
- Die Liste ist dabei initial (also zu Begin) mit folgenden Werten gefüllt:

```

"Hallo", "Welt", "!"

```

e)

- Schreibe eine Funktion, die eine MutableMap zurückgibt.
- Der Key der MutableMap ist vom Typ String, der Wert der MutableMap ist vom Typ Boolean.
- Die MutableMap ist dabei initial (also zu Beginn) mit folgenden Paaren gefüllt:

```

"Lernen wir die Sprache Französisch?" -> false
"Lernen wir die Sprache Kotlin?" -> true

```

f)

- Schreibe eine Funktion, die ein print-Statement ausgibt, jedoch keinen Rückgabewert hat

**Modul für die Aufgabe:** *Aufgabe3*  
**Datei für die Aufgabe:** *FunktionenEntwerfen.kt*

</details>

---

<details>
<summary><b>Aufgabe 4 - Funktionen entwerfen II </b></summary>

Hier üben wir das Erstellen von Funktionen weiter.

a)

- Schreibe eine Funktion mit dem Namen <i>dreifacherWert</i>.
- Lege in der Funktion eine Variable vom Typ Int mit dem Wert 12 an.
- Verdreifache den Wert der Variable und gib sie zurück.

Rufe dann die Funktion in der main() Funktion, wie in den vorherigen Teilaufgaben, auf
und gib das Ergebnis in der Konsole aus.  
Ist das Ergebnis 36?

b)

Wir bauen uns eine kleine Videothek.

- Schreibe eine Funktion mit einem beliebigen aber passenden Namen.
- Lege in der Funktion eine Liste vom Typ String an, die Liste soll initial folgende Werte besitzen:  
"Star Wars", "Shrek", "Toy Story"  
Das sind unsere Filme.
- Gebe dann in der Funktion eine Begrüßung und die Filme in der Konsole aus.  
- Frage dann den Nutzer, welchen Film er ausleihen möchte.
- Nimm dann eine Eingabe über die Konsole entgegen. Die Eingabe ist ein Index für die Liste an Filmen. 
(Also ein Integer zwischen 0 und 2).
- Gib dann den Film für den eingegebenen Index zurück.

Rufe dann die Funktion in der main() Funktion, wie in den vorherigen Teilaufgaben, auf
und gib das Ergebnis in der Konsole aus.


c)

Die letzte Aufgabe ist etwas kreativer, wir bauen eine Funktion, die einen Würfelwurf simuliert.

- Erstelle eine Funktion, die einen Würfelwurf simuliert.
D.h. die Funktion gibt zufällig einen Integer zwischen 1 und 6 zurück.

**Modul für die Aufgabe:** *Aufgabe4*  
**Datei für die Aufgabe:** *WeitereFunktionenEntwerfen.kt*

</details>

---

<details>
<summary><b>Aufgabe 5 - Fehler beheben </b></summary>

Die Katze ist über die Tastatur gelaufen und hat den Code kaput gemacht.

- Korrigiere die Fehler in der Datei.

**Modul für die Aufgabe:** *Aufgabe5*  
**Datei für die Aufgabe:** *FehlerBeheben.kt*

</details>

---

<details>
<summary><b>Aufgabe 6 - Variablen Funktionen zuweisen </b></summary>

In dieser Aufgabe soll in einer Variablen das Ergebnis einer Funktion gespeichert werden

- Erstelle eine Funktion, die als Rückgabewert die Fläche eines Kreises zurückgibt. (3.14*r^2)
- Die Variable ``r`` soll dabei innerhalb der Funktion vom Nutzer eingelesen werden
- Erstelle nun in der main-Funktion eine neue Variable in der du das Ergebnis aus der Funktion speicherst
- Gebe diese im Anschluss in einem print-Statement aus

**Modul für die Aufgabe:** *Aufgabe6*  
**Datei für die Aufgabe:** *Aufgabe6.kt*

</details>

---