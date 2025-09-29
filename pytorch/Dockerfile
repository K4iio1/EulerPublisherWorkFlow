ARG BASE=kaii0713/euler_repository-python:3.13.3-oe2203lts

ARG VERSION=1.11.0

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir --index-url https://download.pytorch.org/whl/cpu \
    torch==${VERSION}