# How To Use

Build the image using `docker build -t repository/tag:version .`

The [Superset](https://github.com/apache/incubator-superset) version is defined at the top of the Dockerfile and installed using pip.

Default username and password is admin, admin. This is defined on line 6 of `superset/superset-init`.

Disable the loading of examples by deleting line 11 of `superset/superset-init`.

Access the application at port 8088.

