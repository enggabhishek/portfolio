<p align="center">
  <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
</p>
<p align="center">
    <h1 align="center">Data Engineer/ Machine Learning Engineer</h1>
</p>
<p align="center">
    <em>Passionate Data Engineer & Software Engineer with a Master's in Analytics from Northeastern. Proficient in Python, Java, ML, led impactful teams at PowerSchool, certified problem solver.</em>
</p>
<p align="center">
		<em>Developed with the software and tools below.</em>
</p>
<p align="center">
	<img src="https://img.shields.io/badge/Python-3776AB.svg?style=flat&logo=Python&logoColor=white" alt="Python">
	<img src="https://seeklogo.com/images/J/java-logo-AC1B3887F3-seeklogo.com.png" width="80" height="40"alt="JAVA">
	<img src="https://blogger.googleusercontent.com/img/a/AVvXsEi_9I286_KzezMNKQFQ4vAcHemjXth1jBqNN0IcH8i5gxFhiehXzsLzdRkUwL1MvpxUz6sqTUWstKHq1GYwwzf29l7FhrVxEO34R6bOEJFGQF4rwKwp-SDLYpAQ8i-mGFmA8cs_llp_-l7qaSzOP6ALWqsZmT2T3I2gP7x6P9JGP_YehGJdCN2T3Q=w640-h500" width="50" height="40"  alt="R-Code">
	<br>
	<img src="https://img.shields.io/badge/pandas-150458.svg?style=flat&logo=pandas&logoColor=white" alt="pandas">
	<img src="https://img.shields.io/badge/NumPy-013243.svg?style=flat&logo=NumPy&logoColor=white" alt="NumPy">
 	<img src="https://img.shields.io/badge/scikitlearn-F7931E.svg?style=flat&logo=scikit-learn&logoColor=white" alt="scikitlearn">
	<br>
	<img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-ar21.svg" width="80" height="40"alt="TensorFlow">
	<img src="https://logowik.com/content/uploads/images/t_qiskit9093.logowik.com.webp" width="80" height="40"alt="Qiskit">
	<br>
	<img src="https://www.mysql.com/common/logos/logo-mysql-170x115.png" width="120" height="40" alt="MySQL">
	<img src="https://miro.medium.com/v2/resize:fit:750/format:webp/0*epnKnkKuLx2RAajt" width="120" height="40" alt="PostgreSQL" style= "background-color: white;">
	<img src="https://seeklogo.com/images/M/microsoft-sql-server-logo-96AF49E2B3-seeklogo.com.png" width="30" height="40" alt="SQL-Server">
	<br>
	<img alt="Visual Studio Code" src="https://madskristensen.gallerycdn.vsassets.io/extensions/madskristensen/openinvisualstudiocode/1.4.58/1698165477219/Microsoft.VisualStudio.Services.Icons.Default" width="20" height="20">
	<img src="https://img.shields.io/badge/Jupyter-F37626.svg?style=flat&logo=Jupyter&logoColor=white" alt="Jupyter">
	<img src="https://download.logo.wine/logo/Eclipse_(software)/Eclipse_(software)-Logo.wine.png" width="80" height="40"alt="Eclipse">
</p>
<hr>

## 🔗 Quick Links

> - [📍 Overview](#-overview)
> - [🧩 Project_Modules](#-Project_Modules)
> - [👏 Acknowledgments](#-acknowledgments)

---

## 📍 Overview

In this 

---



## 🧩 Project_Modules

<details closed><summary>.</summary>

| File                                                                                          | Summary                                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                           | ---                                                                                                                                                                                                                                                                                                                                                                                          |
| [requirements.txt](https://github.com/GokuMohandas/mlops-course/blob/master/requirements.txt) | The code snippet in the `requirements.txt` file specifies the necessary dependencies for the parent repository. It lists various packages for different purposes such as data preprocessing, model training, evaluation, and deployment.                                                                                                                                                     |
| [Makefile](https://github.com/GokuMohandas/mlops-course/blob/master/Makefile)                 | The Makefile in the repository is responsible for executing styling and cleaning tasks. It provides commands for code formatting, linting, and removing unnecessary files.                                                                                                                                                                                                                   |
| [pyproject.toml](https://github.com/GokuMohandas/mlops-course/blob/master/pyproject.toml)     | This code snippet is located in the `pyproject.toml` file of the repository. It sets up linting, formatting, and testing configurations for the project, including tools like Black, iSort, Flake8, and Pytest. It defines the file formatting rules and excludes certain directories from linting. The code ensures that the codebase follows consistent formatting and is properly tested. |

</details>

<details closed><summary>deploy</summary>

| File                                                                                                         | Summary                                                                                                                                                                                                                                                                                            |
| ---                                                                                                          | ---                                                                                                                                                                                                                                                                                                |
| [cluster_env.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/deploy/cluster_env.yaml)         | The code snippet in `deploy/cluster_env.yaml` defines the environment configuration for the parent repository. It specifies the base image, environment variables, Debian packages, Python packages, and post-build commands.                                                                      |
| [cluster_compute.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/deploy/cluster_compute.yaml) | The code snippet `deploy/cluster_compute.yaml` contains the configuration settings for the cluster computation in the parent repository's architecture. It specifies the cloud provider, region, instance types, minimum and maximum workers, storage volume size, and tags for the cluster nodes. |

</details>

<details closed><summary>deploy.jobs</summary>

| File                                                                                                  | Summary                                                                                                                                                                                                                                                                                                  |
| ---                                                                                                   | ---                                                                                                                                                                                                                                                                                                      |
| [workloads.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/deploy/jobs/workloads.yaml) | This code snippet, located in `deploy/jobs/workloads.yaml`, defines the configuration for a workload in the parent repository's architecture. It specifies the project ID, cluster environment, compute configuration, runtime environment, and other parameters necessary for the workload's execution. |
| [workloads.sh](https://github.com/GokuMohandas/mlops-course/blob/master/deploy/jobs/workloads.sh)     | This code snippet is responsible for executing different tasks, such as testing data/code, training a model, evaluating performance, and saving results to S3. It sets up necessary environment variables, runs pytest, executes training and evaluation scripts, and performs S3 uploads.               |

</details>

<details closed><summary>deploy.services</summary>

| File                                                                                                          | Summary                                                                                                                                                                                                                                                                                                                             |
| ---                                                                                                           | ---                                                                                                                                                                                                                                                                                                                                 |
| [serve_model.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/deploy/services/serve_model.yaml) | The code snippet in `deploy/services/serve_model.yaml` is responsible for serving the madewithml project using Ray Serve, specifying the project ID, cluster environment, compute configuration, and other runtime environment variables. It enables the deployment of the madewithml project with the specified rollout strategy.  |
| [serve_model.py](https://github.com/GokuMohandas/mlops-course/blob/master/deploy/services/serve_model.py)     | This code snippet serves to copy files from an S3 bucket, sets the model registry path, and binds the entrypoint for model deployment. It is located in the `deploy/services/serve_model.py` file of the repository. The key activities include copying files from S3, setting the model registry path, and binding the entrypoint. |

</details>

<details closed><summary>madewithml</summary>

| File                                                                                           | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ---                                                                                            | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| [config.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/config.py)     | The code snippet in `madewithml/config.py` sets up logging and configuration for the parent repository. It creates directories, configures MLflow, and defines a logger. Additional constraints for stopwords are also included.                                                                                                                                                                                                                                                                                             |
| [models.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/models.py)     | The `models.py` file in the `madewithml` directory contains the `FinetunedLLM` class, which defines the architecture for a Large Language Model (LLM) that can be fine-tuned. It takes in various parameters, including the LLM itself, and implements the forward pass method for processing batches of data.                                                                                                                                                                                                               |
| [predict.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/predict.py)   | The `predict.py` code snippet in the `madewithml` module is responsible for predicting project tags based on project title and description. It uses MLflow to retrieve the best checkpoint from a specific run, loads the checkpoint, and performs the prediction. The results are then logged and returned.                                                                                                                                                                                                                 |
| [serve.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/serve.py)       | This `serve.py` code snippet in the `madewithml` module is responsible for deploying and serving a trained machine learning model. It uses FastAPI and Ray Serve to expose endpoints for health check, model evaluation, and prediction. The code initializes the model and provides methods for handling requests and returning results.                                                                                                                                                                                    |
| [utils.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/utils.py)       | The `utils.py` code snippet in the `madewithml` module of the parent repository provides utility functions for reproducibility, data processing, and data conversion. It includes functions to set seeds for reproducibility, load and save dictionaries to JSON files, pad arrays, collate batches of data, retrieve the MLflow run ID for a Ray trial ID, and convert dictionaries to lists of dictionaries. These functions are critical for various data processing tasks in the repository's machine learning pipeline. |
| [tune.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/tune.py)         | This code snippet is part of the madewithml repository and is responsible for performing hyperparameter tuning experiments. It uses Ray Tune to search for the best hyperparameters by training and evaluating multiple models. The results of the tuning experiment are returned as a grid of results. The code also provides options for specifying the dataset, initial parameters, number of workers, and other tuning configurations.                                                                                   |
| [train.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/train.py)       | The `madewithml/train.py` file in the repository is responsible for training a model using distributed workload. It uses the Ray library and PyTorch to train the model on multiple workers with customizable hyperparameters. The code has functions for training and evaluation steps, a training loop for each worker, and a main function for training the model.                                                                                                                                                        |
| [evaluate.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/evaluate.py) | The `evaluate.py` file in the `madewithml` module of the codebase is responsible for evaluating the performance of a model on a holdout dataset. It contains functions for calculating overall performance metrics, per class metrics, and metrics for different slices of the data. The code also includes a CLI command for running the evaluation and saving the results.                                                                                                                                                 |
| [data.py](https://github.com/GokuMohandas/mlops-course/blob/master/madewithml/data.py)         | The `madewithml/data.py` code snippet in the `mlops-course` repository is responsible for loading data from a source into a Ray Dataset, splitting the dataset into train and test sets with equal amounts of data points from each class, cleaning raw text, tokenizing text inputs, and preprocessing a raw dataframe. This snippet facilitates the data handling and preprocessing aspects of the parent repository's architecture.                                                                                       |

</details>

<details closed><summary>.github.workflows</summary>

| File                                                                                                                | Summary                                                                                                                                                                                                                                                                                                             |
| ---                                                                                                                 | ---                                                                                                                                                                                                                                                                                                                 |
| [serve.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/.github/workflows/serve.yaml)                 | This code snippet defines a GitHub Actions workflow called serve.yaml in the.github/workflows directory of the repository. It is responsible for deploying and serving the trained machine learning model.                                                                                                          |
| [json_to_md.py](https://github.com/GokuMohandas/mlops-course/blob/master/.github/workflows/json_to_md.py)           | This code snippet, located at `.github/workflows/json_to_md.py`, is responsible for converting JSON files to Markdown format. It is an essential part of the repository's architecture, providing a critical feature for transforming data into a human-readable format.                                            |
| [workloads.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/.github/workflows/workloads.yaml)         | This code snippet is located in the.github/workflows/workloads.yaml file. It likely defines the workflows and tasks that need to be executed in the repository's CI/CD pipeline. Its critical features include automation of the build and deployment processes, ensuring efficient and reliable software delivery. |
| [documentation.yaml](https://github.com/GokuMohandas/mlops-course/blob/master/.github/workflows/documentation.yaml) | The code snippet in `documentation.yaml` is responsible for automating the documentation workflow in the `mlops-course` repository. It defines the steps and triggers for generating and deploying documentation using `mkdocs` and GitHub Actions.                                                                 |

</details>

<details closed><summary>notebooks</summary>

| File                                                                                                    | Summary                                                                                                                                                                                                                                                                                                                       |
| ---                                                                                                     | ---                                                                                                                                                                                                                                                                                                                           |
| [benchmarks.ipynb](https://github.com/GokuMohandas/mlops-course/blob/master/notebooks/benchmarks.ipynb) | The code snippet plays a critical role in the parent repository's architecture by achieving specific functionalities. It is not possible to generate a summary without looking at the actual code snippet and understanding its implementation details. Please provide the relevant code snippet for a more accurate summary. |
| [madewithml.ipynb](https://github.com/GokuMohandas/mlops-course/blob/master/notebooks/madewithml.ipynb) | The code snippet is part of the parent repository's architecture and performs critical features. Its main role includes data preprocessing and feature engineering for machine learning models. It contributes to the overall MLOps course and is linked to datasets and deployment configurations.                           |

</details>

---

## 👏 Acknowledgments

- List any resources, contributors, inspiration, etc. here.

[**Return**](#-quick-links)

---
