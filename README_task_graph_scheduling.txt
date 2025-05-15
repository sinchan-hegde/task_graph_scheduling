# Task Graph Scheduling: Formal Verification of Optimality

## Overview

This project focuses on the formal verification of task graph scheduling, ensuring optimal execution sequences in real-time systems.
By leveraging formal methods, the project aims to validate scheduling strategies against defined optimality criteria, providing guarantees
about system performance and reliability.

## Key Features

- **Formal Verification**: Utilizes formal methods to rigorously prove properties of task scheduling algorithms.
- **Optimality Checks**: Includes queries to assess whether a given schedule meets optimality conditions.
- **Modeling and Analysis**: Provides models representing task graphs and associated scheduling scenarios for analysis.

## Project Structure

- `problem_instance.xml`: Defines the task graph structure and parameters for the scheduling problem.
- `simple_model.xml`: A simplified model for initial testing and validation.
- `extended_model.xml`: An extended model incorporating additional complexities for comprehensive analysis.
- `minimum_time.q`: Query to determine the minimum execution time for the task graph.
- `optimality_check1.q` and `optimality_check2.q`: Queries to verify the optimality of specific scheduling strategies.
- `problem_instance_query1.q`, `problem_instance_query2.q`, `problem_instance_query3.q`: Additional queries for various analysis scenarios.

## Getting Started

1. **Prerequisites**: Ensure you have a compatible formal verification tool installed (e.g., PRISM, UPPAAL).
2. **Load the Model**: Open one of the `.xml` model files in your chosen tool to visualize and understand the task graph structure.
3. **Run Queries**: Use the `.q` query files to perform analyses on the loaded models, assessing properties like execution time and schedule optimality.

## Potential Applications

- **Real-Time Systems**: Validating scheduling strategies in systems where timing is critical.
- **Embedded Systems**: Ensuring reliable task execution sequences in resource-constrained environments.
- **Academic Research**: Serving as a foundation for studies in formal methods and scheduling theory.

## About the Author

Sinchan Hegde is a dedicated researcher with interests in formal verification, real-time systems, and scheduling algorithms.
This project reflects a commitment to enhancing the reliability and efficiency of task scheduling through rigorous analysis.

---

For more details and to access the project files, visit the GitHub repository:
https://github.com/sinchan-hegde/task_graph_scheduling
