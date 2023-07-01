<!-- Navigation top -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`intro`__][content2] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`runter`__][bottom] _`home/swift/intro/dictionaries`_

<!-- Navigation links -->
[home]:     ./home
[seiten]:   ./home-pages
[content]:  ./home-az
[content2]: ./swift-intro-az
[left]:     ./swift-intro-sets
[up]:       ./swift-intro/#dictionaries
[right]:    ./swift-intro-optional_types
[top]:      #
[bottom]:   #links

<!-- CONTENT START ############################################## -->

## Dictionaries

Ein [Wörterbuch](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/collectiontypes#Dictionaries) <_dictionary_> ist eine Liste von ungeordneten Schlüssel/Wert <_key_/_value_> Paaren. Für die Deklarierung wird das Schlüsselwort `dictionary` genutzt.
    
```swift
let wörterbuch = [1: "volker", 2: "nils"]   // struct Dictionary<Key : Hashable, Value>
```

```swift
// Definition
@frozen
struct Dictionary<Key, Value> where Key : Hashable
```

```swift
var PersonenDictionary = [1: "volker", 2: "nils", 7: "martin", 5: "Michael"]

for (key, value) in PersonenDictionary {
    print(String(key) + value)
}
```

<!-- CONTENT END ############################################## -->

<!-- Comment [__`rauf`__][top] [__`runter`__][bottom] -->

<!-- Links --> <br>
##### Links:
<!--   
[`doku`](, "Apple Dokumentation")
-->
[`buch`](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/collectiontypes#Dictionaries, "Swift.org Buch")
[Hashable](https://developer.apple.com/documentation/swift/hashable)
[]() []()

##### Videos:
[]() []()

<!-- Navigation bottom --> <br>
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`rauf`__][top]