These are some example programs built using the CMOC C compiler.
See https://perso.b2b2c.ca/~sarrazip/dev/cmoc.html

ex1: First example without any i/o. Runs fine from ASSIST09 ("C
$2800"). Return value is in D.

ex2: Second example showing string output output. Needs to write
custom output routine. Does not return from main() - workaround is
just to jump to ASSIST09 RESET at end of main().