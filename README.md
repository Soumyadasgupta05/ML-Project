# ML-Project
For installation of the packages

#Create new conda environment

conda create -n pyg python=3.8
conda activate pyg

#Install PyTorch (Check CUDA version!)

conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch

#Install PyG

conda install pyg -c pyg -c conda-forge

#Install other dependencies

pip3 install e3nn==0.4.4
conda install matplotlib pandas networkx
pip3 install ipdb ase
conda install jupyterlab -c conda-forge
