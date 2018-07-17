FROM ubuntu:16.04

RUN apt-get update && \
    apt-get install -y \
	libssl-dev \
	libmysqlclient-dev \
	libcurl4-openssl-dev \
	gcc \
	g++ \
	build-essential \
	libz-dev \
    && rm -rf /var/lib/apt/lists/*
