Heroku buildpack: Lineman
=========================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [Lineman](https://github.com/testdouble/lineman) apps.

Usage
-----

Example usage:

    $ ls
    Procfile  package.json  web.js

    $ heroku create --stack cedar --buildpack http://github.com/testdouble/heroku-buildpack-lineman.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> Lineman app detected
    -----> Vendoring node 0.4.7
    -----> Installing dependencies with npm 1.0.8
           express@2.1.0 ./node_modules/express
           ├── mime@1.2.2
           ├── qs@0.3.1
           └── connect@1.6.2
           Dependencies installed

