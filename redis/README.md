Redis
=====

Redis Environment Building

INSTALLATION
------------

Select your Linux distribution to download and execute the installer as below:

> You can make installer executable by `$ chmod +x ./installer` then `$ ./installer`.

### Ubuntu 16.04 LTS

> Redis: 3.0.6   
> Nginx: 1.10.3 (Optional by PhpRedisAdmin)  
> PHP: 7.0 (Optional by PhpRedisAdmin)   
>
> *PhpRedisAdmin (Optional) is installed at `/var/www/html/phpredisadmin` and can be accessed via `http://yourhost/phpredisadmin`.*

```
$ wget https://raw.githubusercontent.com/yidas/server-installers/master/redis/ubuntu16.04.sh -O installer
$ bash installer
```

### Ubuntu 18.04 LTS

> Redis: 4.0.9   
> Nginx: 1.14.0 (Optional by PhpRedisAdmin)  
> PHP: 7.2 (Optional by PhpRedisAdmin)   
>
> *PhpRedisAdmin (Optional) is installed at `/var/www/html/phpredisadmin` and can be accessed via `http://yourhost/phpredisadmin`.*

```
$ wget https://raw.githubusercontent.com/yidas/server-installers/master/redis/ubuntu18.04.sh -O installer
$ bash installer
```
