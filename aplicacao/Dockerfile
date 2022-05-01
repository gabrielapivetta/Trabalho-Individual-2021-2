FROM ruby:3.0.0

WORKDIR /aplicacao

COPY Gemfile Gemfile.lock ./
RUN bundle install

COPY . /aplicacao

CMD ["rails", "server", "-b", "0.0.0.0"]