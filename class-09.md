# Read:09 Summary
## Concepts of Functional Programming in Javascript & Refactoring Javascript for Readability
> Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

### pure functions:
  * It returns the same result if given the same arguments (it is also referred as deterministic).
  * It does not cause any observable side effects.

### impure function :
  * It uses a global object that was not passed as a parameter to the function
  * It reads external files.
  * Relies on a random number generator.
-----------------------------------------------------------------------------
* When data is ***immutable***, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.
---------------------------------------------------------------------------------
* `Referential transparency` : if a function consistently yields the same result for the same input, it is referentially transparent. 'pure functions + immutable data = referential transparency'.
---------------------------------------------------------------------------------
### Functions as first-class entities can:

  * refer to it from constants and variables
  * pass it as a parameter to other functions

  * return it as result from other functions
  
### Higher-order functions :

  * takes one or more functions as arguments, or
  * returns a function as its result


