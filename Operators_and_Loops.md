# Operators and Loops

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
|| | LOGICAL OR | Tests condition, if either expression returns TRUE - then TRUE  __NOT THE SAME__ | ((2 > 5) || (2 < 1)) returns __fale__
! | LOGICAL NOT | REVERS states of expression  __NOT THE SAME__ | ((2 > 5) || (2 < 1)) returns __fale__

__Evaluating__ = testing a condition for TRUE or FALSE

## LOGICAL OPERATORS

__Comparison operators__ return single values __true__ or __fales__.  __LOGICAL OPERATORS__ compare the results.

((5 < 2) && (2 >= 3))
- Do expression 1 and expression 2 BOTH evaluate to TRUE? __FALSE__

