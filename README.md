# Introduction to Mia 

A first look at Mia's syntax through a few simple variations of "Hello, World!".

```groovy
// Hello, World!, repeated 4 times - Mia v0.01 script
// This example uses Python-like syntax, but
// Mia aims to be lighter and more flexible.

//----- shortest form - single/double quoted strings ok!
print 'Hello, World!' // function call without parentheses
         
//----- using variables
hw = "Hello, World!"  // here, this creates the variable hw
print(hw)             // call with parentheses is ok too

//----- expression function example
def echo(s) = s        // returns the expression
print(echo hw)         // no parentheses on echo call

//----- regular function example 
def printHelloTo(s)            // no Python-style colon
    print 'Hello, ' + s + '!'  // computing the final string

printHelloTo 'World'           // call without parentheses

//----- Disclaimer
// There are many more examples we could include here.
// For now, given our current resources, we are focusing first on
// polishing the grammar and building a useful compiler.
// We plan to add more instructive examples over time.
//
```
