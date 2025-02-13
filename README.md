# dataset_variable_sublots
This dataset is designed for the **Flexible Job Shop Scheduling Problem with variable sublots** in a semiconductor manufacturing environment. It captures the unique characteristics of the problem, including machine categorization, operation-specific constraints, and large-scale job processing. The dataset is intended to facilitate research and reproducibility in the field of production scheduling and optimization.
---

## Dataset Overview

The dataset contains the following key components:

1. **Machines**:
   - Machines are categorized based on the operations they can perform.
   - Machines for different operations are independent and do not interfere with each other.
   - Machines of the same type have identical processing times for the same operation.
2. **Jobs**:
   - Each job consists of a sequence of operations.
   - Each operation must be processed on a specific type of machine.
   - Processing times for operations are provided.
3. **Problem Instances**:
   - The dataset includes **18 problem instances** of varying scales:
     - **Small-scale**: 4 jobs, 19 machines, 8-47 units.
     - **Medium-scale**: 7 jobs, 19 machines, 15-98 units.
     - **Large-scale**: 10 jobs, 19 machines, 14-117 units.
   - Each instance is provided in a structured format for easy parsing.
4. **Additional Information**:
   - Setup times between operations
