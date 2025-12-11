# Custom Prediction Routine on Google AI Platform

This repository contains code and resources for implementing a custom prediction routine on Google AI Platform. With custom prediction routines, you can incorporate your own prediction logic and deploy machine learning models that go beyond the standard serving capabilities provided by Google AI Platform.

## Overview

The custom prediction routine allows you to define custom preprocessing, post-processing, or inference logic for your machine learning models. It provides flexibility in handling prediction requests and enables you to tailor the prediction process to your specific use case.

## Getting Started

To get started with custom prediction routines on Google AI Platform, follow these steps:

1. Clone this repository to your local machine.

2. Review the code and documentation provided in the repository to understand the structure and implementation of the custom prediction routine.

3. Customize the prediction logic according to your requirements. Modify the preprocessing steps, model inference, or post-processing steps as needed.

4. Package the custom prediction code as a Docker container. Update the necessary configurations and dependencies in the Dockerfile.

5. Store the trained model artifacts and any required resources on Google Storage.

6. Deploy the custom prediction routine on Google AI Platform using the packaged Docker container and the stored model artifacts.

## Directory Structure

```
├── code/
│   ├── preprocessing.py
│   ├── inference.py
│   ├── postprocessing.py
│   └── main.py
├── model/
│   ├── model.pkl
│   └── model_config.json
├── Dockerfile
├── requirements.txt
└── README.md
```

- `code/`: Contains the custom prediction routine code, including preprocessing, inference, post-processing, and the main entry point.

- `model/`: Stores the trained model artifacts and configuration files required for prediction.

- `Dockerfile`: Defines the Docker container specifications and dependencies for running the custom prediction routine.

- `requirements.txt`: Lists the Python dependencies required by the custom prediction routine.

## Usage

Please refer to the detailed documentation and instructions within the repository for information on how to use and deploy the custom prediction routine on Google AI Platform.

## Contributing

Contributions to this repository are welcome. If you encounter any issues, have suggestions, or want to add new features, please submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to acknowledge the contributions and support from the open source community and Google AI Platform.
