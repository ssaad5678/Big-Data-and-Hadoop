# Mileage Analysis MapReduce Program 🚗

## Program Description 📊

The Mileage Analysis MapReduce program processes data related to petroleum consumption in electric and gasoline cars to calculate their average mileage and determine the difference in petroleum consumption between the two types of vehicles.

### Mapper (Mileagemapper)

- Parses input data, filtering non-numerical petroleum blend data and ensuring numerical petroleum consumption data.
- Maps petroleum blend as keys and annual petroleum consumption as values.

### Reducer (Mileagereducer)

- Reduces mapped data to calculate the average petroleum consumption for electric and gasoline cars.
- Computes the difference between the average consumption of electric and gasoline cars.

### Driver (mileageee)

- Configures and executes the MapReduce job for mileage analysis.
- Sets input and output paths, handles job execution, and specifies mapper and reducer classes.

## Usage Guide 🚀

To use the Mileage Analysis MapReduce program:

1. **Setup:** Ensure Hadoop is properly configured.
2. **Input:** Provide a dataset containing petroleum blend and annual consumption data.
3. **Execution:** Run the `mileageee` driver class with input and output paths.

Example command:
```bash
hadoop jar MileageAnalysis.jar input_mileage_data/ output_mileage_results/
