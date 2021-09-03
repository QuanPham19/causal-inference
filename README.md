# Suggested setup instructions

1. Use conda
2. Start a new conda environment, suggested to use python 3.6 or 3.7:

`conda create -n causalnex python=3.7`

(replace 'causalnex' with your preferred name). Do NOT try and do the install in the `base` environment, or use python 3.8.

3. Activate environment:

`conda activate causalnex`

4. Use conda to install pygraphviz, rather than pip

`conda install pygraphviz`

If you get an error that the package can't be found, try with conda-forge:

`conda install --channel "conda-forge" pygraphviz`

5. Use conda to install jupyter notebooks too

`conda install notebook`

(or if that doesn't work, `conda install --channel "conda-forge" notebook`)

6. The remainder of the packages should install smoothly using pip:

`pip install causalnex`

7. Start Jupyter using `jupyter notebook` and navigate to the Workbook.