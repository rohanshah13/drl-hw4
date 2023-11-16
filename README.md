Installation Instructions (from Piazza post - https://piazza.com/class/llmlh1ivh0156m/post/257)

conda create -n DRLhw4 -c conda-forge python=3.6 pybox2d
conda activate DRLhw4
conda install pytorch opencv matplotlib
conda install -c conda-forge gym
// go to utils/config.py and comment out line 60 ('import tensorflow as tf')
