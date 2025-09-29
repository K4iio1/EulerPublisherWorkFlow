ARG BASE=kaii0713/euler_repository-python:3.9.1-oe2503

ARG VERSION=2.6.0

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir --index-url https://download.pytorch.org/whl/cpu \
    torch==${VERSION}