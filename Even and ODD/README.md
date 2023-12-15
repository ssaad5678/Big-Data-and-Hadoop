# PROGRAM TITLE 🖥️
**EvenOdd MapReduce Program** 

# Program Description 📖
This MapReduce program verifies whether the provided numbers are even or odd. It encompasses two primary components:

**Mapper**: Splits the input text and emits each word with a count of 1.
Reducer: Determines the even or odd nature of extracted numbers, assigning 1 for even and 0 for odd.

# Usage Guide 🚀
To utilize this MapReduce program:

**Setup**: Ensure Hadoop is correctly configured.

**Input**: Supply an input file containing numbers separated by spaces.

**Execution**: Run the EvenOdd class specifying input and output paths.

Example command:
hadoop jar EvenOdd.jar input/input.txt output/

# Files Included 📂
**EvenOdd.java**: Contains Java code for Mapper and Reducer.
**input.txt**: Sample input file with numbers.

# Output Format 📄
The output includes each number from the input file alongside a 1 (for even) or 0 (for odd).
