# Gradient descent on Seed7

## Idea

There is no idea in this project :) It is a simple one for practicing in Seed7.
What's a Seed7? Interesting, safe and comfortable language, written in C.
For more information you can check official site of Seed7 (Manual).

### I'll be glad, if my project helps someone in learning Seed7!

## BuildSeed7/CompileProject/ExecuteBin

1) Build: Build_Seed7.sh (linux/gcc);
2) Release: src/s7c.sh;
3) Debug: src/s7c_dbg.sh;
4) Bin: bin/gradDescSeed7 (x86_64/debug).

Arguments' values - paths to config|result files.

Example: ./gradDescSeed7 config.txt result.txt.

### If calculation takes long time, reduce 'tm' in calcAdaMax.s7i.

## Implemented

1) Parsing arguments' values;
2) Reading data from file;
3) Sorting points by X;
4) Parsing points;
5) Removing duplicates;
6) Calculating AdaMax;
7) Writting coefficients to file.
