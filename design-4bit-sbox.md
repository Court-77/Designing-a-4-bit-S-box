## Mathematical Calculations

The S-box mapping is defined by a cubic polynomial over the input x:

`S(x) = (a * x ** 3 + 5 * x ** 2 + 2 * x + 7) mod 16`

Where `a = 3`, `b = 5`, `c = 2` and `d = 7`.

Evaluating for all inputs 0 through 15:

For `x = 0`:
'S(0) = 7'

For `x = 1`:

`S(1) = 3 + 5 + 2 + 7`

`= 17`

`= 1 (mod 16)`

For `x = 2`:

`S(2) = 3 *(2) ** 3 + 5 *(2) ** 2`

`= 55`

`= 7` (mod 16)

We repeat this same process for values of x within the closed interval from 3 to 15, and obtain the following results, modulo 16:

For `x = 3`: S(3) = 11

For `x = 4`: S(4) = 15

For `x = 5`: S(5) = 5

For `x = 6`: S(6) = 15

For `x = 7`: S(7) = 15

For `x = 8`: S(8) = 7

For `x = 9`: S(9) = 9

For `x = 10`: S(10) = 7

For `x = 11`: S(11) = 3

For `x = 12`: S(12) = 15

For `x = 13`: S(13) = 7

For `x = 14`: S(14) = 15

For `x = 15`: S(15) = 7


We note that this S-box is NOT bijective, as the output values are not unique. Thus, our equation is not a bijection.
