# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.
ARG BASE_CONTAINER=jupyter/scipy-notebook
FROM $BASE_CONTAINER


RUN pip install --quiet 
	'torch==1.5.0' \
	'kernel-run==0.0.13' \
#&& \
#fix-permissions $CONDA_DIR && \
#fix-permissions /home/$NB_USER
