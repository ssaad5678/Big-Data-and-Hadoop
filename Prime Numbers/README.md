# Prime Number Finder with MapReduce 🌟

## Program Overview 📝

The Prime Number Finder program is designed to determine whether numbers in a dataset are prime or not, utilizing the MapReduce framework.

### Mapper (PrimeMapper)

- Parses input data into individual numbers and checks if they are prime.
- Emits each number as a key and assigns a value of 1 if prime, 0 if not.

### Reducer (PrimeReducer)

- Receives mapped key-value pairs.
- Determines if a number is prime by summing up the occurrences of the number and emitting it if the sum equals 1.

### MapReduce Function (PrimeNumberFinder)

- Configures and executes the MapReduce job for prime number identification.
- Specifies mapper and reducer classes, input and output paths, and handles job execution.

## Usage Guide 🚀

To use the Prime Number Finder program:

1. **Setup:** Ensure Hadoop is properly installed and configured.
2. **Input Data:** Provide a dataset containing numeric values.
3. **Execution:** Run the `PrimeNumberFinder` class with appropriate input and output paths.

Example command:
```bash
hadoop jar PrimeNumberFinder.jar input_numbers/ output_primes/
