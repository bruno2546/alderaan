[![](https://images.microbadger.com/badges/image/brnbp/php.svg)](https://microbadger.com/images/brnbp/php "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/brnbp/php.svg)](http://microbadger.com/images/brnbp/php "Get your own version badge on microbadger.com")

###### you can simple build and run

``` $ docker build -t foo/bar:0.1 . ```

``` $ docker run -i -t foo/bar:0.1 /bin/bash ```

##### or you can just use it from docker registry

#### ``` $ docker run -it -p 8080:80 brnbp/php:latest /bin/bash ```

##### if you want to mount some dir into container, add the following comand before "startup"
        -v path/host/dir:path/container/dir

> this Dockerfile contains:
  - Ubuntu 15.10 (wily)
  - git
  - php 7.0.3
  - mysql 5.7
  - nginx
  - composer
  - nodejs 5.6 && npm
  - mongodb

###### average time to pulling: 10 minutes
