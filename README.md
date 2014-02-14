'deal out' input lines into n (concatentated) piles.

This is an awk script, so you can set n on the command line.

Example:

dealout n=2 input

  ... where input is

    a1
    a2
    b1
    b2
    c1

will produce this output:

    a1
    b1
    c1
    a2
    b2

'n' defaults to 10.
