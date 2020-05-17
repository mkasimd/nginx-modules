# nginx-modules.Dependencies
Some nginx modules have their dependencies included in their repos, others don't.
Here, the dependencies of modules that don't have their dependencies included, will be added.
This list may not be complete. So still read the README in the single modules' directory.

## libmodsecurity

Requires
```
apt-get install g++ flex bison curl doxygen libyajl-dev libgeoip-dev libtool dh-autoreconf libcurl4-gnutls-dev libxml2 libpcre++-dev libxml2-dev
```

Then
```
sh build.sh
$ git submodule init
$ git submodule update #[for bindings/python, others/libinjection, test/test-cases/secrules-language-tests]
$ ./configure
$ make
$ make install
```