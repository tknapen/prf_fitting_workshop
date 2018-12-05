# pRF fitting workshop

This is the repo for the pRF fitting workshop, to be held on Dec 5 in Amsterdam. The notebook containing the entire workshop is located next to this README, and can be run on our notebook server at the VU (but only on the day of the workshop). 

If you just want to view the notebook on GitHub, go here: [PRF_demo.ipynb](PRF_demo.ipynb)

### How to use at home
If you want to run this workshop's materials at home, you will have to install the necessary software. This is a working python environment and, inside it, a set of python packages. Here's a brief step-by-step guide.

- First, download the conda installer from the webpage explaining how to install conda: [anaconda.com](https://conda.io/docs/user-guide/install/download.html). We recommend you use miniconda, as this is the most frugal option in terms of disk usage. If you have a Mac or Linux computer, you'll likely end up downloading some `.sh` file. I don't know how this works for Windows. I'm sure this is not the first time you hear that serious scientific software is **not** available for Windows. 
- Install conda. This can often be done by entering something like `bash miniconda_version_installer.sh` (depending on the file you downloaded) and answering the relevant questions
- Create your first environment: `conda create -n prf_workshop python=3.6` 
- From now on, this environment can be 'activated' by: `conda activate prf_workshop` (or, for older conda versions: `source activate prf_workshop`). Please activate your environment. 
- You'll have to install a bunch of packages. 
    - `conda install -c conda-forge jupyter numpy matplotlib scipy pandas seaborn cython nibabel nilearn`
    - remaining packages are installed with pip:
    - `pip install sharedmem popeye`
- You're done. You can now start a notebook server somewhat like the one you worked on in the workshop on your own computer (preferably in this folder) by: `jupyter notebook`

Note that your system will have to have some things installed for this to work; `ffmpeg` is necessary for the movies of the experimental design, and you will need a compiler to be able to install `popeye`. 

## List of students

Your login is the `student_XX` string in front of your name in the table below. Your password is `prf_workshop_YOUR_EMAIL_ADDRESS`. This list will be deleted on December 6, 2018.

|login         | First and last name       |
|--------------|---------------------------|
| `student_00` | Marlene Roesner |
| `student_01` | Jelle van Dijk |
| `student_02` | Jonathan van Leeuwen |
| `student_03` | Evert Boonstra |
| `student_04` | Luisa Prochazkova |
| `student_05` | Kiki Arkesteijn |
| `student_06` | Laura - Isabelle Klatt |
| `student_07` | Andromachi Tsouli |
| `student_08` | katya olmos |
| `student_09` | Anne Trutti |
| `student_10` | Roel van Dooren |
| `student_11` | Eduard Ort |
| `student_12` | Roderik Gerritsen |
| `student_13` | Ingmar de Vries |
| `student_14` | Isabell Meier |
| `student_15` | Daniel Lindh |
| `student_16` | Remo van der Heiden |
| `student_17` | Iris Schutte |
| `student_18` | Ya Gao |
| `student_19` | Mengsi Xu |
| `student_20` | Aisu Li |
| `student_21` | Kayla Stone |
| `student_22` | Elle van Heusden |
| `student_23` | Dana van Son |
| `student_24` | Yang Liu |
| `student_25` | Martijn van Ackooij |
| `student_26` | Franca Parianen |
| `student_27` | Gijs Holleman |
| `student_28` | Nicolas Carvajal Sanchez |
| `student_29` | Bauke van der Velde |
| `student_30` | Marcelo Malbec |
| `student_31` | Ibrahim Hakami |