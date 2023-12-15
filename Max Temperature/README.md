# MaxTemp MapReduce Program 🌡️

## Program Description 📖

The MaxTemp MapReduce program aims to determine the maximum temperature recorded for each year from an input dataset containing temperature data.

### Mapper (MaxTempMapper)

- Maps temperature data to key-value pairs where the key is the year and the value is the recorded temperature.
- Parses input data and extracts necessary information for analysis.

### Reducer (MaxTempReducer)

- Reduces mapped data to find the maximum temperature for each year.
- Iterates through temperature values and determines the highest temperature for each year.

### Driver (MaxTempDriver)

- Configures and executes the MapReduce job for maximum temperature calculation.
- Sets input and output key-value classes and file paths.
- Manages job execution and handles MapReduce job setup.

## Usage Guide 🚀

To utilize the MaxTemp MapReduce program:

1. **Setup:** Ensure Hadoop is properly configured.
2. **Input:** Provide temperature data in a compatible format.
3. **Execution:** Run the `MaxTempDriver` class with input and output paths.

Example command:
```bash
hadoop jar MaxTemp.jar input_temperatures/ output_maxtemp/
