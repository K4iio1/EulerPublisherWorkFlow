ARG BASE=kaii0713/euler_repository-langchain:0.2-transformers4.20.1-python3.10.1-oe2503

ARG VERSION=2.1.0

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir --index-url https://download.pytorch.org/whl/cpu \
    torch==${VERSION}