# learn-php

## yii
https://www.yiiframework.com/doc/guide/2.0/zh-cn/start-workflow

```sh
php yii serve --port=8888
```

## 安装 composer
https://pkg.phpcomposer.com/

```sh
php -r "copy('https://install.phpcomposer.com/installer', 'composer-setup.php');"
php composer-setup.php
php -r "unlink('composer-setup.php');"
sudo mv composer.phar /usr/local/bin/composer
```

上述 3 条命令的作用依次是：
下载安装脚本 － composer-setup.php － 到当前目录。
执行安装过程。
删除安装脚本。
