# MinimalOmeropy

Created for Image Analysis and Computing Drop In 27/01/2021.
To demonstrate how to connect to OMERO from python and some basic tools.

### Install packages, conda:

For omero-py only:\
conda create -n myenv -c ome python=3.6 zeroc-ice36-python omero-py\
conda activate myenv

Additional:\
conda install -c conda-forge notebook\
conda install scipy\
conda install matplotlib\

### Install packages, venv:

For omero-py only:\
python3 -m venv myenv\
. myenv/bin/activate\
pip install omero-py==5.8.1\

Additional:\
pip install notebook\
pip install scipy\
pip install matplotlib\

### Start jupyter notebook
jupyter notebook
