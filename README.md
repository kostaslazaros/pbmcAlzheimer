## GSE181279 integration analysis using scalex

To replicate the experiments, execute the following steps:

1. Download the dataset batches from this [page](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE181279). Make sure that the RAW data are downloaded (on the download section, choose "custom" and download).

2. Create virtual environment

```sh
python -m venv venv
```

3. Activate virtual environment

- For linux:

```sh
source venv/bin/activate
```

- For windows

```sh
venv\Scripts\activate
```

4. Install the required libraries inside the virtual environment:

```sh
pip install -m requirements.txt
```

5. Then run the following command:

```sh
jupyter notebook
```

Now you can open the notebooks and replicate the experiment.
