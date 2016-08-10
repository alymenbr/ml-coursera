# ml-coursera

Repository for storing the Machine Learning exercises I will be doing for my Coursera ML Certification. 
Please don't copy/fork it. Thanks.



Step 1: Ensure Python 2.7.x
# Create a new conda environment with Python 2.7.x
conda create -n gl-env python=2.7 anaconda

# Activate the conda environment
source activate gl-env


Step 2: Ensure pip version >= 7
# Ensure pip is updated to the latest version
# miniconda users may need to install pip first, using 'conda install pip'
conda update pip


Step 3: Install GraphLab Create
# Install your licensed copy of GraphLab Create
pip install --upgrade --no-cache-dir https://get.graphlab.com/GraphLab-Create/2.1/my-key-here/GraphLab-Create-License.tar.gz


Step 4: Ensure installation of IPython and IPython Notebook
# Install or update IPython and IPython Notebook
conda install ipython-notebook


## RUN IPYTHON
ipython notebook