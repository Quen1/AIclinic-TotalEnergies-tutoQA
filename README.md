# Great Expectations tutorial
[![PythonVersion](https://img.shields.io/badge/python-3.8-blue)](https://img.shields.io/badge/python-3.8-blue)

A brief tutorial for using [Great Expectations](https://greatexpectations.io/), a python tool providing batteries-included data validation. It includes tooling for testing, profiling and documenting your data and integrates with many backends such as pandas dataframes, Apache Spark, SQL databases, data warehousing solutions such as Snowflake, and cloud storage offerings (S3, Azure Blob Storage, GCS).
This tutorial covers the main concepts you'll need to know to use Great Expectations, gently walking you through writing and running your first expectation suite.

If anything is incomplete or unclear, don't hesitate to open an issue! 

## Reading online
If you'd just like to read along, just open [`tutorial_great_expectations.ipynb`] or [`tutorial_pandera.ipynb`] in the repository and you're good to go! We made sure all important output is available online.

If you'd like to run the tutorial without running anything on your own machine, you can open it in mybinder. (https://mybinder.org/)


## Run locally
For running the tutorial on your own machine, we recomend using a [virtual environment](https://docs.python.org/3/library/venv.html) with python 3.8.
1. Clone the repository
2. Install the dependencies: `pip install -r requirements.txt`. 
3. Run `jupyter notebook` in the root directory; then navigate to the `tutorial_great_expectations` notebook.


If you see `AttributeError: module 'great_expectations' has no attribute data_context`, you probably do not have Great Expectations installed. Make sure that it is installed and restart your kernel to fix this.

## Acknowledgements
Avocado dataset provided by the Hass Avocado Board, https://hassavocadoboard.com/volume-data-projections/ .