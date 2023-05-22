# hash:sha256:53ee7f33f802786309be27dc28ebdc2a48ee71a3d6dc7740c29626d33f1a29bb
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.0.9-miniconda4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    itk==5.3.0 \
    itk-elastix==0.17.1 \
    numpy==1.24.3 \
    ome-zarr==0.7.1 \
    itkwidgets[all]==1.0a33
