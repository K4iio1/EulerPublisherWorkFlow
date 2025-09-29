ARG BASE=Qwen3-Coder-30B-A3B-Instruct-pytorch:2.5.0-python3.10.1-oe2503

ARG VERSION=4.55.4

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir transformers==${VERSION}