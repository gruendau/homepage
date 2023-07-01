<!-- Navigation top -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`intro`__][content2] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`runter`__][bottom] _`home/swift/intro/access_modifiers`_

<!-- Navigation links -->
[home]:     ./home
[seiten]:   ./home-pages
[content]:  ./home-az
[content2]: ./swift-intro-az
[left]:     ./swift-intro-variables
[up]:       ./swift-intro/#zugriffsmodifizierer
[right]:    ./swift-intro-types
[top]:      #
[bottom]:   #links

<!-- CONTENT START ############################################## -->

## Zugriffsmodifizierer

Swift kennt fünf Zugriffsmodifikatoren (access modifiers) [`open`](#open) [`public`](#public) [`internal`](#internal) [`fileprivate`](#fileprivate) und [`private`](#private).

---
### open

`open` erlaubt den Zugriff von außerhalb eines Swift Moduls.   
Mit Vererbung von Klassen und Überschreiben von Eigenschaften und Methoden.

```swift
open struct Person {
    // ...
}
```

[__`rauf`__][top] [__`runter`__][bottom]

---
### public

`public` erlaubt den Zugriff von außerhalb eines Swift Moduls.    
Ohne Vererbung von Klassen und Überschreiben von Eigenschaften und Methoden.

```swift
public struct Person {
    // ...
}
```

[__`rauf`__][top] [__`runter`__][bottom]

---
### internal

`internal` erlaubt den Zugriff innerhalb eines Swift Moduls.   
Es ist der voreingestellte <_default_> Zugriffsmodifikator in Swift.  

```swift
// Beide Strukturen haben die gleichen Zugriffsrechte.

struct Person {
    // ...
}

internal struct Person {
    // ...
}
```

[__`rauf`__][top] [__`runter`__][bottom]

---
### fileprivate

`fileprivate` erlaubt den Zugriff innerhalb der Swift Datei.

```swift
struct Person {
    // Auf die id kann nur innerhalb der Swift Datei zugegriffen werden.
    fileprivate let id: Int
    // Auf die Namen die ohne Zugriffsmodifiziererangabe, per default  
    // 'internal' sind, kann innerhalb des Swift Moduls zugegriffen werden.
    var vorname: String
    var nachname: String
}
```

[__`rauf`__][top] [__`runter`__][bottom]

---
### private

`private` erlaubt den Zugriff innerhalb einer Struktur (class, struct, enum, ...)

```swift
private struct Person {
    // ...
}
```

```swift
struct Person {
    // Auf die id kann nur innerhalb der Struktur zugegriffen werden.
    private let id: Int
    // Auf die Namen die ohne Zugriffsmodifiziererangabe, per default  
    // 'internal' sind, kann innerhalb des Swift Moduls zugegriffen werden.
    var vorname: String
    var nachname: String
}
```

[__`rauf`__][top] [__`runter`__][bottom]

<!-- CONTENT END ############################################## -->

<!-- Comment [__`rauf`__][top] [__`runter`__][bottom] -->

<!-- Links --> <br>
##### Links:
<!--   
[`doku`](, "Apple Dokumentation")
[`buch`](, "Swift.org Buch")
-->
[]() []()

##### Videos:
[]() []()

<!-- Navigation bottom --> <br>
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`rauf`__][top]