### README

* At first...
    * I named "the site" as "service"

```
$ git config git-ftp.service.url ftp://domain.com/html/application/
$ git config git-ftp.service.user admin
$ git config git-ftp.service.password xxxxxxx
```

* Next
    * Upload files named "service" with a "init"
	* Then, you only have to do from next time is executing "push"

```
$ git ftp init -s service
$ git ftp push -s service
```

* FYI
    * [Honoka](https://github.com/windyakin/Honoka)
	* [Galleria](http://galleria.io/)

```
$ wget https://github.com/windyakin/Honoka/releases/download/v3.3.6-a/bootstrap-honoka-3.3.6-a-dist.zip
$ unzip bootstrap-honoka-3.3.6-a-dist.zip
$ cp -r bootstrap-honoka-3.3.6-a-dist/* .
$ wget http://galleria.io/static/galleria-1.4.2.zip
$ cp galleria/galleria-1.4.2.min.js js/
```
