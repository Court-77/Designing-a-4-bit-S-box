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

'= 55'

'= 7' (mod 16)

For `x = 3`:

For `x = 4`:

For `x = 5`:

For `x = 6`:

For `x = 7`:

For `x = 8`:

For `x = 9`:

For `x = 10`:

For `x = 11`:

For `x = 12`:

For `x = 13`:

For `x = 14`:

For `x = 15`:
