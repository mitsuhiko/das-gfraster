# Das Gfraster

This is the repository for the German language website [das-gfraster.at](http://das-gfraster.at/).

It uses [Lektor](https://getlektor.com/) to build it.  If you want to edit it locally
you can do this:

```
$ curl -sf https://www.getlektor.com/install.sh | sh
$ lektor server -f webpack
```

Note that you need `node` installed to use webpack locally.

The live version is built automatically by travis.
