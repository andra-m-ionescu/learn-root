FROM mcr.microsoft.com/devcontainers/miniconda:latest

RUN conda config --set channel_priority strict

RUN conda install -y -c conda-forge \
    root \
    jupyterlab \
    notebook \
    numpy \
    matplotlib \
    pandas && \
    pip install mplhep

RUN echo "conda activate base" >> ~/.bashrc
