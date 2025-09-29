ARG BASE=Qwen3-Coder-30B-A3B-Instruct-transformers:4.55.4-pytorch2.5.0-python3.10.1-oe2503

ARG VERSION=0.3

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir langchain==${VERSION}