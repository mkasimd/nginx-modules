# nginx-modules
This is a github repo containing several useful nginx modules. This repo is intended to become part of the [debian-nginx](https://github.com/mkasimd/debian-nginx) repository such that the custom nginx builds may have the newest features enabled. By adding as a submodule, it is also easily achieved to configure any newer version of nginx without having to move everything around.

## Bad Bot Blocker
The nginx bad bot blocker is not a module per se, but a set of nginx configuration files. If installed correctly, the configuration files will be included into your `/etc/nginx/nginx.conf`. See the module for further details.

## Notes on Pagespeed
The latest PSOL binaries may be found under https://www.modpagespeed.com/release_archive/. Set the `PSOL_BINARY_URL` accordingly.
