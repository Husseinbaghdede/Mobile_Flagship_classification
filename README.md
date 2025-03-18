# AWS SageMaker Project

## Project Overview
This project is designed for training and evaluating machine learning models using AWS SageMaker. It includes data processing, model training, and evaluation scripts to automate the workflow.

## Folder Structure
```
awssagemaker/
│── mob_price_classification_train.csv  # Training dataset
│── test-V-1.csv  # Test dataset
│── train-V-1.csv  # Another training dataset
│── research.ipynb  # Jupyter Notebook for research and analysis
│── script.py  # Python script for model training
│── requirements.txt  # Dependencies for the project
│── README.md  # Project documentation
```

## Prerequisites
Ensure you have the following installed before running the project:
- Python 3.7+
- AWS CLI
- Boto3
- Jupyter Notebook (optional, for research.ipynb)
- Required Python libraries (install via `requirements.txt`)

## Installation
1. Clone the repository or extract the ZIP file.
2. Navigate to the project directory:
   ```sh
   cd awssagemaker_extracted
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage
### Running the Jupyter Notebook
To explore data and run experiments interactively:
```sh
jupyter notebook research.ipynb
```

### Running the Training Script
To train the model using AWS SageMaker:
```sh
python script.py
```

## Data
- `mob_price_classification_train.csv`: Training data for mobile price classification.
- `train-V-1.csv`: Another version of the training dataset.
- `test-V-1.csv`: Dataset for testing model performance.

## AWS SageMaker Integration
The script utilizes AWS SageMaker for:
- Model training
- Hyperparameter tuning
- Deployment (if needed)

Ensure you have AWS credentials configured:
```sh
aws configure
```

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.
