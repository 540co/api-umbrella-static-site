# API Umbrella Static Site for FedAPI

### Setup
Ruby 1.9+ is required to build the site.

```
$ git submodule update --init --recursive # Make sure to pull in git submodules
$ gem install bundler
$ bundle install --binstubs
```

### Development
The content files to edit are in ./source. You can view your changes as you make them by running the Middleman preview server:

```
$ ./bin/middleman server
```

This will start a local web server running at http://localhost:4567/

### Deploy
To publish to production with GitHub Pages:

```
$ ./bin/rake publish
```
