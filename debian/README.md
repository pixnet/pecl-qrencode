# php-qrencode for Debian

This extension has been debianized with dh-make-pecl plus
modifications which is more similar to `dh_make --native`.

The dependencies are based on Debian buster and php7.3.

## Build dependencies

Install development packages before building the extension:

```
apt install php-dev libqrencode-dev libpng-dev build-essential dpkg-dev dh-make-php xsltproc
```

## Build command

Run command below to build package from root of the repository:

```
dpkg-buildpackage -rfakeroot -uc -b
```

## TODO

* The upstream documentations are not yet included in the debian package.
