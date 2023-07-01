<!-- Navigation top -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`key`__][content2] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`runter`__][bottom] _`home/swift/keyword/associatedtype`_

<!-- Navigation links -->
[home]:     ./home
[seiten]:   ./home-pages
[content]:  ./home-az
[content2]: ./swift-keyword-az
[left]:     ./swift-keyword-as
[up]:       ./swift-keywords
[right]:    ./swift-keyword-associativity
[top]:      #
[bottom]:   #links

<!-- CONTENT START ############################################## -->

## associatedtype

Ein zugeordneter Typ <_associated type_> kann verwendet werden, um ein Protokoll generisch zu machen. Er wird als generischer Typ für Eigenschaften <_properties_> genutzt. Der zugehörige Typ wird mit dem Schlüsselwort `associatedtype` angegeben.

```swift
// TYPE ist der Platzhalter für den generischen Typ
protocol Store {
    associatedtype TYPE

    var items: [TYPE] { get set }
    mutating func add(item: TYPE)
}

extension Store {
    mutating func add(item: TYPE) {
        items.append(item)
    }
}

struct Shop: Store {
    var items = [String]()
}

var shop = Shop()

shop.add(item: "Book")
shop.add(item: "Car")
```

<!-- Content navigation -->
[](#) [](#) [](#)

<!-- ToDos -->
<!-- 
-->

<!--
### CHAPTER

#### SUBCHAPTER
-->

<!-- Program code -->
<!--
```swift
// Programmcode
```
-->

<!-- CONTENT END ############################################## -->

<!-- Comment [__`rauf`__][top] [__`runter`__][bottom] -->

<!-- Links --> <br>
##### Links:
<!--   
[`doku`](, "Apple Dokumentation")
-->
[`Generics`](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/generics/#Associated-Types, "Swift.org Buch") _<sub>`by Swift.org`</sub>_   
[`Getting started with associated types in Swift Protocols`](https://www.avanderlee.com/swift/associated-types-protocols) _<sub>`by Antoine von der Lee, 2020`</sub>_  
[`AssociatedType in Swift – A Generic Adventure`](https://holyswift.app/associatedtypes-in-swift-a-generic-adventure) _<sub>`by Leonardo, 2020`</sub>_   
[`What is a protocol associated type?`](https://www.hackingwithswift.com/example-code/language/what-is-a-protocol-associated-type) _<sub>`by Paul Hudson, 2019`</sub>_  
[`Understanding protocol associated types and their constraints`](https://www.hackingwithswift.com/articles/74/understanding-protocol-associated-types-and-their-constraints) _<sub>`by Paul Hudson, 2018`</sub>_  

[]() []()

<!-- AttributedString -->

##### Videos:
[`AssociatedType Introduction`](https://www.youtube.com/watch?v=4XpHOJr9Z7I) _<sub>`by iOS Academy, 2022, 7min`</sub>_
[]()


<!-- Navigation bottom --> <br>
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`rauf`__][top]