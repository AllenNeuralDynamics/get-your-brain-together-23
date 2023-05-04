# hash:sha256:039bee675da2ecf93891184c02c8f45858cf686c1330a7c7e538e2f016f3b119
FROM registry.codeocean.allenneuraldynamics.org/codeocean/miniconda3:4.9.2-cuda11.7.0-cudnn8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip install -U --no-cache-dir \
    simpleitk==2.2.1
