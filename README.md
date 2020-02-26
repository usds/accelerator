# Accelerator

Digital Accelerator @ DHS

## Setup

Build natively

1. Install ruby https://jekyllrb.com/docs/installation/
2. install dependencies `bundle install`
3. Build site: `bundle exec jekyll serve`

Build with docker:

``` bash
export JEKYLL_VERSION=3.8
docker run --rm \
  --volume="$PWD:/srv/jekyll" \
  -it jekyll/jekyll:$JEKYLL_VERSION \
  jekyll build
```
