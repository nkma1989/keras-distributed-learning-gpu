# keras-distributed-learning-gpu
This tutorial shows how to train a model on a GPU cluster in Azure Machine Learning Services

# Prerequisites

Before you get started a working python installation is required. For this tutorial i've used python 3.6.6 (https://www.python.org/downloads/release/python-366/)
OBS! Some dependencies like tensorflow requires a 64-bit python version. So make sure you have that!

- Requires access to a working Azure Subscription. You can get a free trial here:
	- https://azure.microsoft.com/en-us/offers/ms-azr-0044p/
- Install the Azure CLI version 2.x or later.
	- https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest
	
In order to host the functions locally you need a virtual environment. If you have a fresh installation of python you can install the library virtualenv to create virtual environments(make sure 
to add python as environment variable):
```
pip install virtualenv
```
Open a powershell or cmd window and navigate to the cloned repository:
```
cd <path to local repository>
```
Create a virtual environment for your project:
```
virtualenv venv --python=<path to python 3.6>
```
Activate the virtual environment:
```
venv\scripts\activate
```
Now install the dependencies in order to host the functions locally:
```
pip install -r venv_requirements.txt
```