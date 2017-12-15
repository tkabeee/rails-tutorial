FROM ruby:2.3.5
RUN apt-get update -qq && apt-get install -y build-essential libpq-dev nodejs
RUN mkdir /toy-app
WORKDIR /toy-app
COPY Gemfile /toy-app/Gemfile
COPY Gemfile.lock /toy-app/Gemfile.lock
RUN bundle install
COPY . /toy-app