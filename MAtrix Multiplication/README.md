# Matrix Multiplication MapReduce Program 🖥️

## Program Description 📖

This MapReduce program performs matrix multiplication using Hadoop's MapReduce framework. The program consists of three main components:

### 1. Mapper (MMMapper)

- Maps input matrices into key-value pairs suitable for matrix multiplication.
- Emits intermediate key-value pairs for Reducer processing.

### 2. Reducer (MMReducer)

- Reduces intermediate key-value pairs to calculate the result of matrix multiplication.
- Employs hash maps for efficient storage and retrieval of matrix elements.
- Outputs the final matrix multiplication results.

### 3. Driver (MMDriver)

- Configures and initiates the MapReduce job for matrix multiplication.
- Sets the dimensions (m, n, p) for the matrices.
- Manages input and output formats, paths, and job settings.

## Usage Guide 🚀

To use this Matrix Multiplication MapReduce program:

1. **Setup:** Ensure Hadoop is correctly configured.
2. **Input:** Provide input matrices in CSV format.
3. **Execution:** Run the `MMDriver` class with input and output paths.

Example command:
```bash
hadoop jar MatrixMultiply.jar input_matrices/ output_result/
