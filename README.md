builpack-prevent-assets-compilation
------------------------

## Using

Prevent heroku/ruby buildpack to compile assets and crashes since it tries to connect to a private space database

```
heroku buildpacks:add -a MY-APP https://git.trustpair.fr/trustpair/heroku/builpack-prevent-assets-compilation
```
