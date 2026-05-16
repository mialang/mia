# Introduction to Mia 

Example of Mia's Syntax 

```scala
//-- Hello World (4x) - Mia 0.01 - Script
// Featuring low weight and low boilerplate

//----- shortest way
print "Hello, World!" // no braces
         
//----- using a variable hw
hw = "Hello, World!"
print(hw)             // with braces

//----- echo function
def echo(s) = s        // return expression
print(echo hw)         // optional braces

//----- prints function 
def prints(s)          // no Python's collon
    print s

prints "Hello," +      // no ugly line continuation
   " " +
      "World"
```
