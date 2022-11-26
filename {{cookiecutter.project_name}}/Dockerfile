FROM python:3.11-slim as base
FROM base as builder

WORKDIR /app
ENV PIP_DISABLE_PIP_VERSION_CHECK=1
ENV PYTHONUNBUFFERED=1

COPY . .
RUN pip install .
