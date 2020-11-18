FROM circleci/elixir:1.9.1-node

USER root

RUN apt-get update -qq && \
    apt-get install -qq -y python-dev python-pip && \
    pip install -q awscli ansible==2.9.11 boto boto3

