# AWS
ssh udacity@XX.XX.XX.XXX.XX

screen -S note -d -m jupyter notebook

jupyter notebook: ec2-XXXX.compute.amazonaws.com:8888


# Anaconda & environments
https://www.continuum.io/downloads

conda list
conda upgrade conda
conda upgrade --all

conda create -n py3 python=3
conda create -n py2 python=2

source activate py3
conda install numpy scipy pandas tensorflow tqdm scikit-image tensorflow-gpu


# Jupiter Notebooks
conda install jupyter notebook

jupyter notebook


# floydhub
floyd init jupyternote
floyd run --mode jupyter --gpu --env tensorflow-1.1


# libraries

http://pandas.pydata.org/pandas-docs/stable/10min.html#min
