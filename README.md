# Introduction to Mia 

A taste of of Mia's syntax 

```groovy
// Hello World, repeated 4 times - Mia 0.01 script
// Similar to Python, but designed to be lighter

//----- shortest way - single/double quoted strings ok!
print 'Hello, World!' // function call with no braces
         
//----- using variables
hw = "Hello, World!"  // creates var with double quote
print(hw)             // with braces

//----- expression function example
def echo(s) = s        // return expression
print(echo hw)         // No braces on echo call

//----- regular function example (preview)
def printHelloSomebody(s)          // no Python's collon
    print f'Hello, {s}!', s        // formated with 2 args

printHelloSomebody 'World'         // no braces call

//----- Disclaimer
// There are many more examples we could include here.
// For now, given our current resources, we are focusing first on
// polishing the grammar and building a useful compiler.
// We plan to add more instructive examples over time.
//
```
