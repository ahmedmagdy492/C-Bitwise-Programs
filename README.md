# C-Bitwise-Programs
Some Useful C Programs that does some bit manupilation
Some Useful constructs that might be helpful:
- ~(~0 << n) where n is any positive integer  ->  sets the right most n bits to 1, you can use it with & to extract the right most bits from any number
- (~(~0 << n) << p) where p is a position in any given integer  ->  we can use it to shift the bits constructed in the previous example to position p
