# Introduction to Mia 

Example of Mia's Syntax 

```groovy
// Hello World, repeated 4 times - Mia 0.01 script
// Similar to Python, but designed to be lighter

//----- shortest way
print "Hello, World!" // usual function with no braces
         
//----- using a variable hw
hw = "Hello, World!"  // assign can create var 
print(hw)             // with optional braces

//----- expression function example
def echo(s) = s        // return expression
print(echo hw)         // calling without 

//----- regular function example
def printHelloDear(s)          // no Python's collon
    print "Hello, " + s        // some computation

printHelloDear 'World'         // single quote string
```
