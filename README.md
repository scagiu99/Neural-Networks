# Neural-Networks
Project for the University Master Degree Course of Statistical Methods for Machine Learning.

The purpose of this project is to accurately classify images of muffins and chihuahuas, utilizing different neural network architectures to solve the task.

## Dataset
The projects described in this document refer to the [Muffin vs chihuahua](https://www.kaggle.com/datasets/samuelcortinhas/muffin-vs-chihuahua-image-classification) dataset, which is published on Kaggle and released under the [CC0 license: Public Domain](https://creativecommons.org/publicdomain/zero/1.0/).

## Requirements

- `kaggle`
- `tensorflow`
- `keras-tuner`
- `pandas`
- `numpy`
- `matplotlib`

### Installation

To install the required libraries, run:

```bash
pip install kaggle tensorflow keras-tuner pandas numpy matplotlib
```

## Usage

1. **Download the Dataset**:
   - Ensure that your `kaggle.json` file is properly configured for the Kaggle API.
   - Download the dataset using the following command:
     ```bash
     kaggle datasets download -d samuelcortinhas/muffin-vs-chihuahua-image-classification
     ```
   - Unzip the dataset and place it in the appropriate directory.

2. **Running the Model**:
   - Run the provided Jupyter Notebook to train and evaluate the models.
   - The training results, including accuracy and loss curves, will be displayed.

3. **Hyperparameter Tuning**:
   - Use Keras Tuner to optimize the model's hyperparameters. Adjust the search space in the script as needed.
  
## Project Structure

- `Neural_Network_Project.ipynb`: Contains the Jupyter notebooks for data exploration and model training.
- `StatisticalMethods_Report.pdf`: Contains the Report with the description of the results

