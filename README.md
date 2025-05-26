# jupyter-docker

Docker files for building OCEAN 215 docker image

Modified from Docker image for UW-IT JupyterHub for Teaching SciPy notebook, version 2.7.1

- Built docker image can be found at https://hub.docker.com/r/winghouw/ocean215
- Detailed information about base SciPy notebook is here: https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html#jupyter-scipy-notebook
- General information about working with base images is here: https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html
- Information about the UW-IT JupyterHub for Teaching SciPy notebook is here: https://github.com/uw-it-aca/rttl-notebooks/blob/main/scipy/README.md
- Installed packages and versions can be viewed in this image's [Dockerfile](Dockerfile) using `pip list` or `conda list`.
- Full dependence of python packages can be viewed in this image's [Dockerfile](Dockerfile) using `pipdeptree`. A copy of the output is included in `dependency.txt`
