# Business-Contract-Dataset-Intel-Training-Program-2024📜

## Description

The **Business-Contract-Dataset-Intel-Training-Program-2024** is a comprehensive dataset designed for training and evaluating models on contract analysis. It consists of 27 contract files organized into 5 distinct folders based on contract type. This dataset is ideal for those looking to train machine learning models for tasks such as clause classification, deviation detection, and contract parsing.

## Dataset Structure

The dataset is organized into the following folders, each containing contracts specific to its type:

- **Employment**: 5 contracts
- **Joint**: 5 contracts
- **Partnership**: 7 contracts
- **Purchase**: 4 contracts
- **Sales**: 5 contracts


## Installation

To use this dataset in your project, you can clone the repository using the following command:

```bash
git clone https://github.com/yourusername/Business-Contract-Dataset-Intel-Training-Program-2024.git
```
## Usage
This dataset can be used for various contract analysis tasks, including but not limited to:

## Clause classification
Deviation detection from standard templates
Contract parsing and segmentation
Example usage in Python:
```
import os

dataset_path = 'path/to/Business-Contract-Dataset-Intel-Training-Program-2024'

for folder in os.listdir(dataset_path):
    folder_path = os.path.join(dataset_path, folder)
    for file in os.listdir(folder_path):
        file_path = os.path.join(folder_path, file)
        # Perform your analysis on file_path
```

## Contributing
We welcome contributions to enhance the dataset and improve its usability. To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Commit your changes (git commit -m 'Add new feature').
4. Push to the branch (git push origin feature-branch).
5. Create a pull request.

## Contact
For any questions or support, please contact us at megharajeev022@gmail.com, shanesamofficial@gmail.com.
