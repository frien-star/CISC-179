# Operations within Python:
## Order of priority
### 1. Parenthesis - ()
### 2. Exponentation - **   
   Exponents are calculated from right to left   
   Example: 2**2 = 4   
   * Datatype caveat: Strings
      * Ints ** string = error
      * float ** string = error
      * string ** string = error
### 3. Unary operators   
   An operation that takes only one operand (or input) to perform its function, in contrast to binary operations that require two operands.
   Basically- think of a negative or positive integer.
   +5 instead of 5 + 0
### 4. Multiplicative/Divisinary operators (Done left to right)
   * Multiplication - (*)
      * Datatype caveats: Strings
         * int * string = true
         * float * string = Error
         * string * string = Error
   * Division or Integer Division - (/) or (//)
     * Integer division is regular division that ignores the fractional value
     * 5 // 2 = 2
     * Division with any strings results in an error.
   * Remainder Division - (%)
     * Only factor in the remainder value
     * 5 % 2 = 1
### 5. Addition or Subtraction Binary Operators (left to right)   
#### Datatype caveat:   
 * Strings +/- integers = Error
 * Strings +/- floats = Error
 * Strings + Strings = True
 * Strings - Strings = Error
