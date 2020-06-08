This repository hosts the code for http://xtermjs.org.

## Running the website locally

You need [ruby](https://www.ruby-lang.org) and [bundler](https://bundler.io) installed first.

```bash
# Install dependencies
bundle install

# Serve the website
bundle exec jekyll serve
```

## Update API documentation

```bash
yarn
./bin/update-docs
```