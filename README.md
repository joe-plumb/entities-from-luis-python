# Entities from LUIS using Python
Sample Python notebook showing how to extract entities from a LUIS model into a new column on your dataframe.

## Setup
1. Navigate to https://portal.azure.com/ and provison an instance of the [Language Understanding Service](https://ms.portal.azure.com/#create/Microsoft.CognitiveServicesLUISAllInOne)
1. Install the required libraries in `requirements.txt` into your python environment i.e. `$ pip install -r requirements.txt`.
1. Populate `credentials.json.template` with connection details for your LUIS service and save as `credentials.json` in the project directory
1. Open the `example-luis-entities.ipynb` and run the example notebook

## TODO
1. Provide instructions and code to import existing `.json` or `.lu` model details