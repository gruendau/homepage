<!-- Navigation top -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`intro`__][content2] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`runter`__][bottom] _`home/swift/intro/arrays`_

<!-- Navigation links -->
[home]:     ./home
[seiten]:   ./home-pages
[content]:  ./home-az
[content2]: ./swift-intro-az
[left]:     ./swift-intro-collections
[up]:       ./swift-intro/#Arrays
[right]:    ./swift-intro-sets
[top]:      #
[bottom]:   #links

<!-- CONTENT START ############################################## -->
## Arrays

Ein [Array](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/collectiontypes#Arrays) <_array_> ist eine geordnete Liste von Elementen. Für die Deklarierung wird das Schlüsselwort `array` genutzt.
    
```swift
let array = ["volker", "nils"]   // struct Array<Element>
```

### Definition
```swift
// Definition
@frozen
struct Array<Element>
```

### Deklaration
```swift
// Ein leeres Array für Strings deklarieren
var a1: Array<String> = Array()
var a2: Array<String> = []
var a3 = Array<String>()

var a4: [String] = Array()
var a5: [String] = []
var a6 = [String]()

print(type(of: a1))  // --> Array<String>
print(a1)            // --> []
```

### Initialisierung
```swift
// Ein leeres Array für Strings deklarieren und initialisieren (Werte zuweisen).
var a1: Array<String> = Array(["volker", "nils"])
var a2: Array<String> = ["volker", "nils"]
var a3 = Array<String>(["volker", "nils"])

var a4: [String] = Array(["volker", "nils"])
var a5: [String] = ["volker", "nils"]
var a6 = ["volker", "nils"]

print(type(of: a1))  // --> Array<String>
print(a1)            // --> ["volker", "nils"]
```

### Ausgewählte Eigenschaften und Funktionen
```swift
// Wichtige Eigenschaften und Methoden von Arrays
var names = ["volker", "nils", "monika", "jana", "hanna"]

// .count 
// Die Anzahl der Elemente im Array.
print( names.count )  // --> 5


// .append() 
// Fügt am Ende des Arrays ein neues Element hinzu.
names.append("rainer")
print( names )  // --> ["volker", "nils", "monika", "jana", "hanna", "rainer"]

// Fügt die Elemente einer Sequenz am Ende des Arrays hinzu.
names.append(contentsOf: ["ludwig", "anne"])
print( names )  // --> ["volker", "nils", "monika", "jana", "hanna", "rainer", "ludwig", "anne"]

// .remove() 
// Entfernt das Element an der angegebenen Position und gibt es zurück.
print( names.remove(at: 1) )  // --> nils
print(names)  // --> ["volker", "monika", "jana", "hanna", "rainer", "ludwig", "anne"]


// .sort() 
// Sortiert die Elemente von oben nach unten.
names.sort()
print( names )  // --> ["anne", "hanna", "jana", "ludwig", "monika", "rainer", "volker"]

// .reverse() 
// Sortiert die Elemente von unten nach oben.
names.reverse()
print( names )  // --> ["volker", "rainer", "monika", "ludwig", "jana", "hanna", "anne"]


// .map() 
// Gibt ein Array zurück, das die Elemente entsprechend den Anforderungen des Closures verändert.
print( names.map( { "vorname: " + $0 } ) )  // --> ["vorname: volker", "vorname: rainer", ...]

// .filter() 
// Gibt ein Array zurück, das Elemente entsprechend den Anforderungen des Closures enthält.
print( names.filter( { $0.contains("an") } ) )  // --> ["anne", "hanna", "jana"]

// .reduce()
// Gibt das Ergebnis entsprechend den Anforderungen des Closures zurück.
print( names.reduce("") { $0 + $1 + " " } )  // --> volker rainer monika ludwig jana hanna anne
```

<!-- CONTENT END ############################################## -->

<!-- Comment [__`rauf`__][top] [__`runter`__][bottom]-->

<!-- Links --><br>
##### Links:
[`doku`](https://developer.apple.com/documentation/swift/array, "Apple Dokumentation")
[`buch`](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/collectiontypes#Arrays, "Swift.org Buch")
[]()
[]()

##### Videos:
[]() []()

<!-- Navigation bottom --><br>
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`rauf`__][top]