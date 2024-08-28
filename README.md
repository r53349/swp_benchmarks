# Swp Benchmarks

## Overview
This project was designed to evaluate the performance of a new algorithm (Spindle) for software pipeline. The benchmarks were produced using the Gcc compiler, by converting C code loops into their Data Dependency Graphs. 

## Benchmarks Structure
Each benchmark file is a text format description of a DDG.

Such a file, contains the following sections :

- Unit description - name of units and the number of instances for each one.

- Instructions description (Ddg nodes) - name of allowed units for each instruction (the default one, marked with '*' is the unit that was chosen by Gcc).

- Stalls (Ddg edges) - the number of needed cycles between pairs of commands.  

- Information about potential register moves.

  
