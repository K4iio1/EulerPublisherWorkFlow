ARG BASE=kaii0713/euler_repository-transformers:4.50.0-huggingface_hubV0.35.0-python3.10.1-oe2503

ARG VERSION=2.5.0

FROM ${BASE}

ARG VERSION

RUN pip install --no-cache-dir --index-url https://download.pytorch.org/whl/cpu \
    torch==${VERSION}