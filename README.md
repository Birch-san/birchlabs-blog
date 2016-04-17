# birchlabs-blog

New [Jekyll](https://jekyllrb.com/)-powered blog intended for Birchlabs.co.uk

## Development

### Setup computer

#### Get Ruby

Preferably via rvm.

#### Install [Jekyll](https://jekyllrb.com/)

```bash
gem install jekyll
```

### Serve blog

This launches the blog locally. Any changes made will be watched, and trigger a build.

Configuration [documented here](https://jekyllrb.com/docs/configuration/).

`--skip-initial-build` should be used iff you've made no changes since the last time Jekyll was off.

`--incremental` is an experimental feature that should improve build times.

```bash
jekyll serve --skip-initial-build --incremental
# Now browse to http://localhost:4000/blag/
```