# MinimalOmeropy

### Install packages, conda:

For omero-py only:\
conda create -n ompy -c ome python=3.6 zeroc-ice36-python omero-py\
conda activate ompy

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
