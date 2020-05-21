# Heroku OR Tools Buildpack
This buildpack installs [Google OR Tools](https://developers.google.com/optimization) for the `heroku-18` stack.

The binary installed is hosted [here](https://github.com/google/or-tools/releases/download/v7.6/or-tools_ubuntu-18.04_v7.6.7691.tar.gz)

This buildpack was created by following this [Sendgrid tutorial](https://sendgrid.com/blog/create-first-heroku-buildpack/)

To use:

```
heroku create -b https://github.com/rodreegez/heroku-ortools-buildpack.git
# _or if your app is already created_
heroku config:add BUILDPACK_URL=https://github.com/rodreegez/heroku-ortools-buildpack.git
git push heroku master
```
