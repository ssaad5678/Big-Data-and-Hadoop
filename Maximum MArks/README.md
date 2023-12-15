# Maximum Average MapReduce Program 📊

## Program Description 📖

The Maximum Average MapReduce program aims to determine the maximum average of a set of numbers from an input dataset.

### Mapper (MaximumAverageMapper)

- Maps input data to key-value pairs, calculating the average of integers in each record.
- Parses input data and computes the average for each record.

### Reducer (MaximumAverageReducer)

- Reduces mapped data to find the maximum average among the calculated averages.
- Iterates through the average values to determine the highest average.

### Driver (MaximumAverageDriver)

- Configures and executes the MapReduce job for maximum average calculation.
- Sets input and output key-value classes and file paths.
- Manages job execution and handles MapReduce job setup.

## Usage Guide 🚀

To utilize the Maximum Average MapReduce program:

1. **Setup:** Ensure Hadoop is properly configured.
2. **Input:** Provide a dataset with a list of integers in each record.
3. **Execution:** Run the `MaximumAverageDriver` class with input and output paths.

Example command:
```bash
hadoop jar MaxAvg.jar input_numbers/ output_maxavg/
