# PHP-SQLSRV

## About

I need to create this image because I use ArchLinux and a project need use SQLServe and Laravel. Laravel don't work as well with `dblib`, so I need `MS SQLSrv` and `MS ODBC` drivers.

[Here](https://gjuniioor.github.io/blog/driver-sqlsrv-laravel/) are a blog post (in portuguese (Brazil)) explain the case.

## Softs

In this image there is installed some softwares to help your development, like Git, cURL, Apache and Composer.

### Tags and softs versions

The name of the version is the PHP Version.

## Run

~~~
$ docker run -d -p 80:80 -v projeto/laravel:/var/www/html gjuniioor/php-sqlsrv:7.0
~~~

And go to [localhost](http://localhost).

## Bugs, Questions and Contribution

Has a bug found? Please, open a [Issue](https://github.com/gjuniioor/docker-php-sqlsrv/issues), a [Pull Request](https://github.com/gjuniioor/docker-php-sqlsrv/pulls) or contact me: [@gjuniioor](https://github.com/gjuniioor).
