# tutorial-crocolake-2026

## CrocoLake-Python

The Jupyter notebooks in this repository show how to use Argo data in parquet format and [CrocoLake](https://crocolakedocs.readthedocs.io/en/latest/).

### Usage

You can just launch any notebook and execute it. The datasets needed are already loaded in the JupyterHub `shared/` space for the workshop.

Note that there are a couple of ways to load parquet datasets in a dataframe in Python: using [pyarrow](https://arrow.apache.org/docs/python/index.html) and using [dask](https://www.dask.org/). [Example 1](Example_1_ArgoBGC_Map_Oxygen.ipynb) and [Example 2](Example_2_CrocoLakeBGC_Map_Oxygen.ipynb) show both, while the other example uses dask, which is often the most efficient.

### Examples

1. [Example 1](Example_1_ArgoBGC_Map_Oxygen.ipynb) shows how to make a map of dissolved oxygen content from Argo BGC floats in the North West Atlantic;
2. [Example 2](Example_1_CrocoLakeBGC_Map_Oxygen.ipynb) shows how to make a map of dissolved oxygen content in the Pacific, with data from multiple sources: Argo, GLODAPv3, and Spray Gliders;
3. [Example 3](Example_3_Animation_Oxygen.ipynb) shows how to make an animation of Argo's fleet growth over time on a world map;

### More

To replicate these examples outside the workshop (e.g. on your own machine), look at [this repository](https://github.com/boom-lab/crocolake-python/tree/main).

For any questions, bugs, missing information, etc, open an issue or [get in touch](enrico.milanese@whoi.edu)!
