# docker-nginx_omniauth_adapter
Docker image for [nginx_omniauth_adapter](https://github.com/sorah/nginx_omniauth_adapter)

Docker image is available from https://hub.docker.com/r/groovenauts/nginx_omniauth_adapter/

## Environment variables

Only `RACK_ENV=production` is defined in Dockerfile.

For other environment variables, see https://github.com/sorah/nginx_omniauth_adapter#configuration

## config.ru

`config.ru` is not included in this repository, but copy from `nginx_omniauth_adapter` gem installed path on build.

## Docker image tags and git tags

### Docker image tags

- `latest`
  - git master branch
- `x.y.z-r`
  - same as git tags

### Git tags

- `x.y.z-r`
  - `x.y.z` : nginx\_omniauth\_adapter gem version
  - `r` : revison number

