ARG BASE=Qwen3-Coder-30B-A3B-Instruct-python:3.10.1-None

ARG VERSION=2.5.0

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir --index-url https://download.pytorch.org/whl/cpu \
    torch==${VERSION}