FROM ruby:3.0.2-alpine

RUN apk add --no-cache build-base g++

RUN gem install seven_zip_ruby || exit 0
RUN cat /usr/local/bundle/extensions/aarch64-linux-musl/3.0.0/seven_zip_ruby-1.3.0/mkmf.log