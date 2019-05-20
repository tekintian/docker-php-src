# alpine docker php 配置文件对应容器中的目录



目录 php53 -- 73 分别表示 php-5.3至 php-7.3系列版本



## 目录中文件夹对应关系

### etc 对应容器目录为:
/usr/local/etc/

### extensions 对应容器目录:
/usr/local/lib/php/extensions/





如 PHP53的 redis 扩展的配置文件在容器中的完整为:

**/usr/local/etc/**php/conf.d/docker-php-ext-redis.ini



对应的扩展.so文件在容器中的路径为:

**/usr/local/lib/php/extensions**/no-debug-non-zts-20090626/redis.so











