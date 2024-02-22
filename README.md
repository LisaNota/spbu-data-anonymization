# Data Anonymization Tool

This tool provides functionality for anonymizing datasets according to specified quasi-identifiers and calculating the k-anonymity value of the anonymized dataset.

## User Interface

1. **Load File:** Load the input dataset file (final file of the 1st lab work).
2. **Select Attributes:** Choose the quasi-identifiers for anonymization and k-anonymity calculation.
3. **Anonymize and Calculate:** Anonymize the dataset based on the selected attributes and calculate the k-anonymity value.
4. **Calculate k-anonymity:** Directly calculate the k-anonymity value without anonymizing the dataset.

## Supported Anonymization Methods

- **Delete Attribute:** Delete the values of the selected attribute.
- **Local Generalization:** Generalize passport data based on the country of origin.
- **Masking SNILS:** Replace SNILS numbers with masked values.
- **Count Attributes:** Count the number of attributes in the "Symptoms" column.
- **Pseudonymization:** Map doctor names to corresponding departments.
- **Mask Dates:** Mask dates in the "Visit Date" and "Analysis Receipt Date" columns.
- **Mean Anonymization (Cost):** Anonymize the cost of analysis using mean-based anonymization.
- **Mask Credit Card Numbers:** Mask credit card numbers by replacing digits with 'X'.

## Usage

1. Load the input dataset file by clicking the "Load File" button.
2. Select the desired quasi-identifiers by checking the corresponding checkboxes.
3. Click the "Anonymize and Calculate" button to anonymize the dataset and calculate the k-anonymity value.
4. Alternatively, click the "Calculate k-anonymity" button to directly calculate the k-anonymity value without anonymizing the dataset.

## Requirements

- Python 3.x
- pandas
- tkinter

