FROM ruby:alpine
RUN apk add build-base && gem install puma rackup sinatra && apk del build-base
COPY hasher.rb .
CMD ruby hasher.rb
