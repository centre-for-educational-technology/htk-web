# htk-web

## Build and develop

Using bundler with locally placed gems is recommended and allows sandboxing

1. Install [Ruby](https://www.ruby-lang.org) on your machine
2. Clone repo and cd into it
3. Install bundler
  * `gem install bundler`
4. Use bundler to pull jekyll dependencies
  * `bundle install --path vendor/bundle`
  * `bundle update`

### Serve with development env

        bundle exec jekyll serve --config=_config-dev.yml --watch


## Build (old)

        jekyll serve --config=_config-dev.yml --watch
