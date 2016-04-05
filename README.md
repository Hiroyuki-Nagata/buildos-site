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
    * I'm using [Honoka](https://github.com/windyakin/Honoka)

```
$ wget https://github.com/windyakin/Honoka/releases/download/v3.3.6-a/bootstrap-honoka-3.3.6-a-dist.zip
$ unzip bootstrap-honoka-3.3.6-a-dist.zip
$ cp -r bootstrap-honoka-3.3.6-a-dist/* .
$ wget https://github.com/blueimp/Bootstrap-Image-Gallery/archive/v3.4.2.tar.gz
$ tar xvf v3.4.2.tar.gz
$ cp -r Bootstrap-Image-Gallery-3.4.2/* .
$ mv img/* images/
$ vim css/bootstrap-image-gallery.css
- 	background: url(../img/loading.gif) center no-repeat;
+ 	background: url(../images/loading.gif) center no-repeat;
```
