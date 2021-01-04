# ezQuake Documentation
> https://www.ezquake.com

## Development

### Setup
```shell
bundle install
```

### Build and host
* Builds to `_site/` (using development config)
* Rebuild on changes
* Hosted at http://localhost:4000

```shell
bundle exec jekyll serve --config=_config.yml,_config.localhost.yml
```

## Production

### Build
Builds using production config to `_site/`.
```shell
bundle exec jekyll build
```
