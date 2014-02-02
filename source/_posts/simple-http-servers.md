title: Share Your Website and Files Locally: Simple Http Servers
date: 2014-01-31 11:38:12
tags: 
---

Sometimes you need to serve a directory to a group in a small room. 

Using Node 
``` javascript

npm install http-server -g
http-server 
//another port
//http-server -p 9080 
```

Using Python 

``` python

python -m SimpleHTTPServer
#specify port number via python -m SimpleHTTPServer 8080
```
Using Php
``` php
//stick something on your /var/www bin and profit. 

```


Want to share some files? use wget or curl
Localhost is your website. 

a specific file

Using Curl
``` shell
curl -O http://localhost:port/FILE.TXT
curl -O http://localhost:port/PIC.PNG

```

Using Wget
Always works for me, included no parent and recursive to only get the desired directory.
``` shell
 wget --no-parent -r  http://localhost:port/DIRECTORY
```