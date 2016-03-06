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
