# Исходники сайта [robotech.info](https://robotech.info)

<br/>

### Запустить robotech.info для разработки

    $ docker-compose up

<br/>

### Запустить robotech.info локально как сервис

<a href="https://sysadm.ru/linux/servers/containers/docker/install/">Docker</a> должен быть установлен.

    # cp robotech.info.service /etc/systemd/system/robotech.info.service

<br/>

    # systemctl enable robotech.info.service
    # systemctl start  robotech.info.service
    # systemctl status robotech.info.service

http://localhost:4018
