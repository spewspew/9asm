Local Labels for the Plan 9 Assembler
=====================================

I added local labels to the Plan 9 assembler.  A good example is
1.3.2progp.s which generates the first 500 prime numbers.

You can choose numbers 0-9 for your labels and the syntax is:

* 1(H) to create a local label.
* 1(B) to jump backwards to the closest 1(H)
* 1(F) to jump forwards to the closest 1(H)

The only changes made were to 6a/a.y, the other files are needed
to copile.
