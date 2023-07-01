<!-- Navigation top -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`runter`__][bottom] _`home/xxx`_

<!-- Navigation links -->
[home]:     ./home
[seiten]:   ./home-pages
[content]:  ./home-az
[left]:     ./xxx
[up]:       ./home
[right]:    ./xxx
[top]:      #
[bottom]:   #links

<!-- CONTENT START ############################################## -->

## Operatoren

### Arithmetische Operatoren
Addition `+`  
Subtraktion `-`  
Multiplikation `*`  
Division `/`  
Modulo `%`  

```swift
1 + 2       // --> 3
5 - 3       // --> 2
2 * 3       // --> 6
10.0 / 2.5  // --> 4.0
9 % 4       // --> 1
```

### Zusammengesetzte Zuweisungsoperatoren
zusammengesetzte Zuweisungsoperatoren <_compound assignment operators_> ... 
`+=`   
`-=`   
`*=`   
`/=`  

```swift
```

### Inkrement und Dekrement Operatoren
`++`  
`--`   

```swift
var x = 1
++x   // --> 2
++x   // --> 3

--x   // --> 2
--x   // --> 1
--x   // --> 0
``` 

### Vergleichsoperatoren
Gleich `a == b`  
Ungleich `a != b`  
Größer `a > b`   
Kleiner `a < b`   
Größer.gleich `a >= b`   
Kleiner-gleich `a <= b`   

```swift
1 == 1   // --> true
2 != 1   // --> true 
2 > 1    // --> true 
1 < 2    // --> true 
1 >= 1   // --> true 
2 <= 1   // --> false

(1, "zebra") < (2, "apple")   // --> true 
(3, "apple") < (3, "bird")    // --> true
(4, "dog") == (4, "dog")      // --> true 
```

### Ternärer bedingter Operator

Ein ternärer bedingter Operator <_ternary conditional operator_> ist eine Kurzform für eine if-else Entscheidung. 

```swift
question ? answer1 : answer2
```

```swift
if question {
    answer1
} else {
    answer2
}
```

### Null-Koaleszenzoperator 

Ein Null-Koaleszenzoperator <_nil-coalescing operator_> gibt den Wert der Variablen oder einen Ersatzwert für den Wert `nil` zurück.

```swift
a ?? b
```

```swift
a != nil ? a! : b
```

### Range Operators

#### closed range operator

```swift
a...b
```

#### half-open range operator


```swift
a..<b
```

#### one-sided range


```swift
2...
```
```swift
```
```swift
```
```swift
```
```swift
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
[`"TEXT"`](LINK) _<sub>`von swift.org`</sub>_ 
[`"TEXT"`](LINK) _<sub>`by AUTHOR, YEAR`</sub>_
-->
[`Basic Operators`](https://docs.swift.org/swift-book/documentation/the-swift-programming-language/basicoperators/) _<sub>`von apple documentation`</sub>_

<!--
##### Videos:
[`"TEXT"`](LINK) _<sub>`by AUTHOR, YEAR, Xmin`</sub>_
-->

<!-- Navigation bottom --> <br>
<!-- ###### <sub>_</sub> Ersatz Sprungmarke, wenn keine '##### Links:' vorhanden ist. -->
[__`home`__][home] [__`seiten`__][seiten] [__`a-z`__][content] [__`<--`__][left] [__`hoch`__][up] [__`-->`__][right] [__`rauf`__][top]