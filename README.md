# quine
A small python program that generates itself as its output.
run check.sh to compile the program and check the diff of the output and itself.

I did this because the one liner solution I could find:
s='s=%r;print(s%%s,sep="")';print(s%s,sep="")
looked really ugly and convoluted.
