# CyclicJoinBench


## Load the Data
To download the data, you can either navigate to the [Webpage](https://event.cwi.nl/da/CyclicJoinBench/) and download the data manually, or you can use the `load_data.py` script to download the data for you. 

We use `poetry` for dependency management. To install poetry, run the following command:

```bash
pip install poetry
```

To then install the dependencies, run the following command:

```bash
poetry install
```

After installing the dependencies, you can run the `load_data.py` script to download the data. The script will download the data to the `data` directory. 

```bash
poetry run python load_data.py 
```