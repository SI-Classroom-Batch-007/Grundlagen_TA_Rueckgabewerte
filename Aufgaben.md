
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
<summary><b>Aufgabe 1 - Rückgabewert vorhersagen </b></summary>

In dieser Aufgabe sind Codeausschnitte gegeben und du sollst vorhersagen, 
was für ein Wert in der Konsole ausgegeben wird.
Schreibe die Lösung in den Kommentar in der Datei, 
füge dann den Codeausschnitt hinzu und überprüfe dein Ergebnis.

a)
- Schau dir den nachfolgenden Code an und überlege wie die Ausgabe des Codes aussieht.

```
fun subtrahieren(): Int {
    var zahl1 = 28
    var zahl2 = 13
    return zahl1 - zahl2
}

fun main() {ㅤㅤ
    println(subtrahieren())
}

```

b)

- Schau dir den nachfolgenden Code an und überlege wie die Ausgabe des Codes aussieht.

```

fun lieblingsFarbe(): String {
    val farben: List<String> = listOf("Rot", "Blau", "Gelb", "Grün", "Lila", "Pink")
    var meineFarbe: String = farben[farben.size-4]
    return meineFarbe
}

fun main() {
    println(lieblingsFarbe())
}

```

c)

Schau dir den nachfolgenden Code an und überlege wie die Ausgabe des Codes aussieht.

```
fun ersteZahl(): Int {
    return (20 - 18) * 6
}

fun zweiteZahl(): Int {
    return 25 / 5 
}

fun main() {
    val ergebnis = ersteZahl() * zweiteZahl()
    println(ergebnis)
}
```

**Modul für die Aufgabe:** *Aufgabe1*  
**Datei für die Aufgabe:** *Textabgabe.kt* 

</details>

---

<details>
<summary><b>Aufgabe 2 - Funktion + Rückgabewert implementieren und aufrufen </b></summary>

- Schreibe eine Funktion ``zehnfach``, die das zehnfache einer vom Nutzer eingelesenen Zahl zurückgeben soll.
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
    println(eineFunktion())
}

fun eineFunktion(): String {
    return "Das ist eine Funktion!"
}

```

a)

Schreibe eine Funktion mit passendem Rückgabewert, die 5 zurückgibt. 

b)

Schreibe eine Funktion mit passendem Rückgabewert, die 6.234 zurückgibt.

c)

Schreibe eine Funktion mit passendem Rückgabewert, die "Hallo" zurückgibt.

d)

Schreibe eine Funktion, die eine Liste vom Typ String zurückgibt.
Die Liste ist dabei initial (also zu Begin) mit folgenden Werten gefüllt:

```

"Hallo", "Welt", "!"

```

e)

Schreibe eine Funktion, die eine MutableMap zurückgibt.
Der Key der MutableMap ist vom Typ String, der Wert der MutableMap ist vom Typ Boolean.
Die MutableMap ist dabei initial (also zu Begin) mit folgenden Paaren gefüllt:

```

"Lernen wir die Sprache Französisch?" -> false
"Lernen wir die Sprache Kotlin?" -> true

```

f)

Schreibe eine Funktion, die nichts zurückgibt.

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

- Schreibe eine Funktion mit einem beliebigen Namen.
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
D.h. die Funktion gibt mit gleicher Wahrscheinlichkeit einen Integer zwischen 1 und 6 aus.

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
<summary><b>Aufgabe 6 - verschachtelte Funktionen </b></summary>


</details>

---