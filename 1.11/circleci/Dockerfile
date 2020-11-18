FROM circleci/elixir:1.11.2-node

USER root

RUN apt-get update -qq && \
    apt-get install -qq -y python-dev && \
    rm -rf /var/lib/apt/lists/* && \
    curl -sL https://bootstrap.pypa.io/get-pip.py | python && \
    pip install -q ansible==2.10.3 awscli  boto boto3

