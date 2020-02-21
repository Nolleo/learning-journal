# Operators and Loops

1. Other Notes
	1. [Markdown](markdown.md)
	1. [Text Editor](TEXTEDITOR.md)
	1. [Terminal](TERMINAL.md)
	1. [Git Guide - (_made in VS Code_)](VScode.md)
	1. [HTML](HTML.md)
	1. [CSS](CDD.md)
	1. [Git Guide - (1st VS made notes)](GitGuide-VS.md)
	1. [How Computers Work](how_computers_work.md)
	1. [JaveScript Notes](JavaScript.md)
	1. [JavaScript Programming](JavaScript-Programming.md)

## COMPARISON OPERATORS: Evaluating Conditions

Evaluate by comparing ONE VALUE in the script to WHAT YOU EXPECT. Result: BOOLEAN: __True__ or __False__

### OPERATORS

OPERATOR | NAME | MEANING | EXAMPLES
--- | --- | --- | ---
== | IS EQUAL TO | Compares values, determines if SAME | 'Hello' == 'Goodbye' returns __false__
!= | IS NOT EQUAL TO | Compares values, determines if SAME | 'Hello' == 'Hello' returns __true__
=== | STRICT EQUAL TO | Compares values, determines if BOTH DATA type AND VALUE __SAME__ | '3' === 3 returns __fales__
!== | STRICT NOT EQUAL TO | Compares values, determines if BOTH DATA type AND VALUE __NOT THE SAME__ | '3' !== 3 returns __true__
> | GREATER THAN | Checks values, if number left is greater than number right  __NOT THE SAME__ | 4 > 3 returns __true__
< | LESS THAN | Checks values, if number left is greater than number right  __NOT THE SAME__ | 4 > 3 returns __fale__
>= | GREATER THAN OR EQUAL TO | Checks values, if number left is greater than number right  __NOT THE SAME__ | 4 > 3 returns __true__
<= | LESS THAN OR EQUAL TO | Checks values, if number left is greater than number right  __NOT THE SAME__ | 4 > 3 returns __fale__
&& | LOGICAL AND | Tests condition, if BOTH expression returns TRUE - then TRUE  __NOT THE SAME__ | 4 > 3 returns __fale__
`||` | LOGICAL OR | Tests condition, if either expression returns TRUE - then TRUE  __NOT THE SAME__ | ((2 > 5) || (2 < 1)) returns __fale__
! | LOGICAL NOT | REVERS states of expression  __NOT THE SAME__ | ((2 > 5) || (2 < 1)) returns __fale__

__Evaluating__ = testing a condition for TRUE or FALSE

## LOGICAL OPERATORS

__Comparison operators__ return single values __true__ or __fales__.  __LOGICAL OPERATORS__ compare the results.

((5 < 2) && (2 >= 3))
- Do expression 1 and expression 2 BOTH evaluate to TRUE? __FALSE__

## LOOPS

### FOR

#### Run a code specific NUMBER of times in a loop.  This is like a COUNTER for a LOOP.

### WHILE

#### If the number of loops is unknown, use WHILE.  Loop will continue until the TRUE condition becomes FALSE.

### DO WHILE

#### Like WHILE but will always evaluate the statement within curly brackets at least once, even if condition evaluates as false.

### Loop Counters

#### Initialization

Create variable and set to __0__.  Commonly _i_ and acts as counter.
> var i = 0;

#### Condition

Loop runs until counter reaches a specific number.
> i , 10;

#### Update

After running the statements in curly braces, ADD ONE to the counter.
> i++

- KEYWORDS
    - break - causes termination
    - continue - continue and check again
- Loop & Arrays
- Performance Issues
    - all other actions are paused until script done
    - infinite loop warning - always FALSE