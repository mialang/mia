# Introduction to Mia 

A taste of of Mia's syntax 

```groovy
// Hello, World!, repeated 4 times - Mia 0.01 script
// This example uses Python-like syntax, but
// Mia is lighter and more flexible.

//----- shortest form - single/double quoted strings ok!
print 'Hello, World!' // function call without parentheses
         
//----- using variables
hw = "Hello, World!"  // here, this creates the variable hw
print(hw)             // call with parentheses is ok too

//----- expression function example
def echo(s) = s        // returns the expression
print(echo hw)         // no parentheses on echo call

//----- regular function example (preview)
def printHelloTo(s)            // no Python-style colon
    print f'Hello, {s}!', s    // formatted string + second arg

printHelloTo 'World'           // call without parentheses

//----- Disclaimer
// There are many more examples we could include here.
// For now, given our current resources, we are focusing first on
// polishing the grammar and building a useful compiler.
// We plan to add more instructive examples over time.
//
```
