# Introduction to Mia 

Preview of syntax

```scala
//-- Hello World (4x) - Mia 0.01 - Script
// Featuring low weight and low boilerplate

//----- shortest way
print "Hello, World!" // no braces
         
//----- using a variable hw
hw = "Hello, World!"
print(hw)             // with braces

//----- echo function
def echo(s) = s
print(echo hw)         // optional braces

//----- prints function 
def prints(s)
    print s

prints "Hello," +      // no explict line continuation
   " " +
      "World"
```
