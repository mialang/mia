# Introduction to Mia 

Example of Mia's Syntax 

```scala
//-- Hello World (4x) - Mia 0.01 - Script
// Similar to Python but intend should be lighter
// Featuring reduced boilerplate and  differences

//----- shortest way
print "Hello, World!" // usual function with no braces
         
//----- using a variable hw
hw = "Hello, World!"  // assign can create var 
print(hw)             // with optional braces

//----- expression echo function
def echo(s) = s        // return expression
print(echo hw)         // calling without 

//----- usual printHelloDear function 
def printHelloDear(s)          // no Python's collon
    print "Hello, " + s        // some computation

printHelloDear 'World'         // single quote string
```
