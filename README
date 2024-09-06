Overview

This project implements basic relational algebra operations in C++. The code provides functionality to perform operations such as selection, projection, renaming, union, intersection, set difference, and Cartesian product on CSV files representing relations.

## Features

| **Operation**       | **Syntax**                                      | **Explanation**                                                        |
|---------------------|-------------------------------------------------|------------------------------------------------------------------------|
| **Select**          | `S[predicate](relation)`                        | Filters rows based on a predicate.                                     |
| **Project**         | `P[column list](relation)`                      | Selects specific columns from a relation. Use `*` to select all columns. Columns in the list are separated by commas. |
| **Rename**          | `R[new relation name(new column names)](old relation name)` | Renames a relation and/or its columns. You can either rename all columns or keep the existing names. |
| **Union**           | `U[relation_1](relation_2)`                     | Computes the union of two relations.                                   |
| **Intersection**    | `I[relation_1](relation_2)`                     | Computes the intersection of two relations.                            |
| **Set Difference**  | `D[relation_1](relation_2)`                     | Computes the difference between two relations (relation_1 - relation_2). |
| **Cartesian Product** | `C[relation_1](relation_2)`                  | Computes the Cartesian product of two relations.                       |
| **Exit**            | `exit`                                          | Terminates the query session.                                          |
Notes

	•	Queries are case-insensitive for both table names and column names.
	•	Constants (either string or integer) in predicates must be enclosed in single quotes.
	•	Columns in the project query are separated by commas. Use * to project all columns.
	•	When renaming a relation, you can rename the relation and all columns. To rename columns, provide a name for each column, or specify 0 to keep the existing names.
