# Introduction to Mia 

Preview of syntax

```scala
//-- Hello World (4x) - script mode 

//----- shortest way
print "Hello, World!" // no braces
         
//----- using a variable hw
hw = "Hello, World!"
print(hw)             // with braces

//----- echo function
def echo(s) = s
print(echo hw)         // optional braces

//----- prints function + low boilerplate
def prints(s)
    print s

prints "Hello,"       // no line continuation
   + " " +
      "World"
```
