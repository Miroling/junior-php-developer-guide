# Environment

#### Доступы к Web-серверу

```
ssh <user>@europe.vpn.apibest.com```


WebRoot ```
/home/<user>/www/<project>```


Пароль тот же что и имя

#### Доступы к MySQL


```
mysql://d_<user>:<password>@neptune.vpn.apibest.com/p_<project>_<user>```

Пароль тот же что и имя

Вы может самостоятельно создавать БД с маской ```p_*_<user>```!

Для проверки правильности настроек нужно:
1. Cоздать сайт вида ```test.<user>.europe.vpn.apibest.com```
 который будет выводить ```phpinfo()```
2. Настроить подключение к БД из Менеджера БД (например Navicat)
3. Настроить Automatic Upload в PHPStorm для тестового проекта