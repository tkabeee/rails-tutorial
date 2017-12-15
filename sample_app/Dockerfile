FROM ruby:2.3.5
RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs
RUN mkdir /sample-app
WORKDIR /sample-app
COPY Gemfile /sample-app/Gemfile
COPY Gemfile.lock /sample-app/Gemfile.lock
RUN bundle install
COPY . /sample-app