## Installation

To install Bakta, follow these simple steps:

1. Ensure you have [conda](https://docs.conda.io/en/latest/) installed on your system.
2. Run the following command in your terminal to install Bakta from the conda and bioconda channels:

```bash
cona create -n bakta -y
conda activate bakta 
conda install -c conda-forge -c bioconda bakta# bakta
```

## Download the Database
Run the following command in your terminal, specifying the output path where you want to store the database:

```bash
bakta_db download --output <output-path> --type full
```

## Preparing the assembly files from skesa
Bakta requires assembly files in zipped fasta format. You can use the provided Python script called gzip_it to gzip the .fa assembly files.

## Running bakta
```bash
.\bakta_pipeline.sh
```

## Additional information
For more information and advanced usage, refer to the [Bakta documentation](https://github.com/oschwengers/bakta).
