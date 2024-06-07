# Dataset Splitter

This repository provides a script to split a dataset into training and testing sets in an 80:20 ratio using Python.

## Overview

Splitting a dataset is a crucial step in machine learning to ensure that the model is trained and evaluated on different data. This repository contains a simple Python script that uses pandas and scikit-learn to split a dataset into training and testing sets.

## Script Details

The `SplittingDataset.ipymb` script performs the following tasks:

1. Loads a dataset from a CSV file.
2. Splits the dataset into training and testing sets in an 80:20 ratio.
3. Saves the resulting datasets into separate CSV files.

## Requirements

- Python 3.x
- pandas
- scikit-learn

## How It Works

- **Loading Data:** The script reads the dataset from a CSV file using pandas.
- **Splitting Data:** The dataset is split using scikit-learn's `train_test_split` function, which ensures that 80% of the data is used for training and 20% for testing.

## Example Usage

After placing your dataset in the root directory of the repository, you can run the `split_dataset.py` script to generate the split datasets. Make sure to adjust the script to point to your dataset file if necessary.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
