# スクリプトの実行
```
$ docker run -it --rm --name php-script -v "$PWD":/usr/src/myapp -w /usr/src/myapp php:8.1.16-cli php script.php
```