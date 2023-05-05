# hash:sha256:41ddaf8bab99e664dbd8bc2dbc490668e20a5b230ebad4bb991cacd28e96f212
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.4.4-miniconda4.12.0-python3.9-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    simpleitk==2.2.1
