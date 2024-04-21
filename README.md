# Bakery Association Analysis

## Introduction

Consider a dataset of transactions from a bakery, provided in the attached file "Bakery.csv". Each transaction represents a set of items defined with their names at a specific time. Each item is listed in a separate row within the transaction.

The objective is to determine the association between items within these transactions. This involves identifying frequent item sets and generating association rules based on minimum support and minimum confidence thresholds.

## Requirements

1. Write a program in any programming language that implements one of the association algorithms (Apriori, FP-Growth, or vertical data format) on the set of transactions.
2. Allow user input of minimum support and minimum confidence during runtime.
3. Generate all association rules that can be mined from the transactions.
4. Display the frequent item sets and association rules with their confidence in the final output.

## Implementation

### Data Processing

1. Load the transaction data from "Bakery.csv".
2. Preprocess the data to ensure each transaction is properly formatted for association analysis.

### Association Algorithm

1. Choose one of the association algorithms: Apriori, FP-Growth, or vertical data format.
2. Implement the selected algorithm to identify frequent item sets.

### User Input

1. Prompt the user to input the minimum support and minimum confidence thresholds.

### Association Rule Generation

1. Generate association rules based on the frequent item sets and user-defined thresholds.
2. Calculate the confidence for each association rule.

### Output

1. Display the frequent item sets along with their support.
2. Display the association rules along with their confidence.

## Conclusion

By implementing the chosen association algorithm and allowing user input for minimum support and minimum confidence, we can effectively analyze the transactions from the bakery dataset and uncover valuable associations between items.

