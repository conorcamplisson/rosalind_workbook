# Rosalind Workbook

Jupyter notebook templates by topic for the bioinformatics problems on [rosalind.info](http://rosalind.info/problems/topics/) and a corresponding conda environment.

### Getting Started

1. Ensure you have either [Anaconda](https://docs.anaconda.com/anaconda/install/) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed.

2. Clone this repository:

```
$ git clone git@github.com:conorcamplisson/rosalind_workbook.git
```

2. Create the conda environment:

```
$ cd rosalind_workbook/
$ conda env create -f environment.yml
```

3. Activate the conda environment:

```
$ source activate rosalind
```

4. Run the jupyter notebook server:

```
$ jupyter notebook
```

6. In your web browser, navigate to the jupyter notebook server web interface and open the [rosalind_workbook/](./rosalind_workbook/) directory.

7. Open the notebook for your chosen topic, and run the import cell before working on the problems.
