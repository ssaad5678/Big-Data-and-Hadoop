# Program Title 🖥️

Average Salary Calculator using Hadoop MapReduce

# Description 📖

The "Average Salary Calculator" project aims to compute the average salary from a dataset utilizing Hadoop's MapReduce framework. The primary objective is to process employee salary information and determine the average salary within specified departments.

The MapReduce paradigm segments the computation into two main stages: mapping and reducing. The mapper extracts the salary data by department from the input dataset, while the reducer calculates the average salary for each department.



## Tech Stack </>

**Hadoop MapReduce Framework**: Utilized for distributed processing, enabling efficient handling of large datasets by dividing computation tasks across a cluster.

**Java Programming Language**: Implemented the MapReduce tasks using Java for its compatibility with Hadoop.
**Input/Output Format**: The project processed data in CSV format, allowing structured input and output data handling.

**Libraries/Frameworks**: Utilized Hadoop libraries and MapReduce APIs to facilitate data processing and task execution.


## Appendix 🌐

**Sample Input Data**:The input data comprised employee records with fields for department and salary.

**Mapper Functionality**:The Mapper class parses the input data, extracting departmental salary information while handling any potential data format issues.

**Reducer Functionality**:The Reducer class calculates the average salary for each department by aggregating the salary data and determining the mean value.
