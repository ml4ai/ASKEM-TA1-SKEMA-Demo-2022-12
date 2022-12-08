# ASKEM TA-1 SKEMA Demo for December 2022

## Install

1. Recommend creating a python virtual environment

	`python -m venv <venv_name>`

	Activate the venv.

2. Clone the automates repository: [https://github.com/ml4ai/automates](https://github.com/ml4ai/automates)
	
	`git clone https://github.com/ml4ai/automates.git`

3. While in the activated venv, pip install automates: cd into the root of the automates respository and run:

	`pip install -e .`

4. Clone the skema repository: [https://github.com/ml4ai/skema](https://github.com/ml4ai/skema)

	`git clone https://github.com/ml4ai/skema.git`

5. While in the activated venv, pip install skema: cd into the root of the skema repository and run:

	`pip install -e .`

6. Ensure you have a copy of the following directories under the `ASKEM-SKEMA/data google drive`:

	- `resources/tr/`
	- `epidemiology/CHIME/CHIME_penn_full_model/`
	
	You will update your local paths to these directories in the `demo/skema-demo-2022-Dec.ipynb` jupyter notebook.