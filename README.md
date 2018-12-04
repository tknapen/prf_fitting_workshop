# pRF fitting workshop

This is the repo for the pRF fitting workshop, to be held on Dec 5 in Amsterdam. The notebook containing the entire workshop is located next to this README, and can be run on our notebook server at the VU (but only on the day of the workshop). 

If you just want to view the notebook on GitHub, go here: [PRF_demo.ipynb](PRF_demo.ipynb)

### How to use at home
If you want to run this workshop's materials at home, you will have to install the necessary software. This is a working python environment and, inside it, a set of python packages. Here's a brief step-by-step guide.

- First, download the conda installer from the webpage explaining how to install conda: [anaconda.com](https://conda.io/docs/user-guide/install/download.html). We recommend you use miniconda, as this is the most frugal option in terms of disk usage. If you have a Mac or Linux computer, you'll likely end up downloading some `.sh` file. I don't know how this works for Windows. I'm sure this is not the first time you hear that serious scientific software is **not** available for Windows. 
- Install conda. This can often be done by entering `bash miniconda_version_installer.sh` and answering the relevant questions
- Create your first environment: `conda create -n prf_workshop python=3.6` 
- From now on, this environment can be 'activated' by: `conda activate prf_workshop` (or, for older conda versions: `source activate prf_workshop`). Please activate your environment. 
- You'll have to install a bunch of packages. 
    - `conda install jupyter numpy matplotlib scipy pandas seaborn ctypes`
    - remaining packages are installed with pip:
    - `pip install sharedmem popeye`
- You're done. You can now start a notebook server somewhat like the one you worked on in the workshop on your own computer (preferably in this folder) by: `jupyter notebook`
