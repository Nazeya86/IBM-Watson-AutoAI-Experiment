# IBM Watson AutoAI Experiment

## Project Overview
This project demonstrates the use of IBM Watson AutoAI for automated machine learning (AutoML) to build a model based on training data. The project includes steps for configuring and running AutoAI experiments, managing training data, deploying models, and scoring.

## Key Features
- Automated machine learning pipeline creation using IBM Watson AutoAI.
- Deployment of the best pipeline as a web service.
- Scoring new data via the deployed web service.

## Prerequisites
- IBM Cloud account with Watson Machine Learning access.
- Python 3.x and pip installed.

## Setup
1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/IBM-Watson-AutoAI-Experiment.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Set your IBM Cloud API key and deployment URL in the script.
2. Run the AutoAI experiment and retrieve the best model.
3. Deploy the model as a web service for scoring.

## Deployment
To deploy the model:
1. Create a deployment space in IBM Cloud.
2. Create a web service using the best pipeline model.

## License
This project is licensed under the MIT License.
