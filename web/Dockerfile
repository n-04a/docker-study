FROM ruby:2.5.0
ENV LANG C.UTF-8

RUN apt-get update && apt-get install -y \
    build-essential \
    libpq-dev \
    postgresql-client \
    nodejs \
    vim \
    emacs25-nox
RUN gem install rails
RUN mkdir /app
WORKDIR /app
