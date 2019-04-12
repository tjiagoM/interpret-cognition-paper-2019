# A machine learning tool for interpreting differences in cognition using brain features

This repository stores the code used in the following preprint: [https://www.biorxiv.org/content/10.1101/558403v1](https://www.biorxiv.org/content/10.1101/558403v1) (accepted in AIAI 2019).

We cannot share the original data used in the paper so we provide example files in `example_data/` folder so the code in this repository can be executed.

Dependencies to execute the code are listed in [environment_paper.yml](environment_paper.yml). One can easily install all the dependencias by using an Anaconda environment, and running the following commands:

```sh
# Creating the environment with the file we provided
$ conda env create --force --file environment_paper.yml

# Activating the environment
$ conda activate env-paper

```

The main packages and respective versions that were used in this work (and defined in `environment_paper.yml`) are:

* __jupyterlab__ 0.35.4 
* __matplotlib__ 3.0.2
* __numpy__ 1.15.4
* __pandas__ 0.24.1
* __python__ 3.6.8
* __scikit-learn__ 0.20.2
* __scipy__ 1.2.0
* __shap__ 0.27.0
* __xgboost__ 0.81


All the descriptions are in the folder `notebooks/`, which you can see by executing, for example, Jupyter Lab:
```sh
(env-paper) $ jupyter lab
```

If you have any questions please just [open an issue](https://github.com/tjiagoM/interpret-cognition-paper-2019/issues).
