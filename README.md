# Домашнее задание к занятию 2 «Кластеризация и балансировка нагрузки». Осипенков АЮ

## Mission 1

*Запустите два simple python сервера на своей виртуальной машине на разных портах
*Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
*Настройте балансировку Round-robin на 4 уровне.
*На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

[конфигурационный файл haproxy](https://github.com/Kovrei/Clustering-and-load-balancing/blob/main/haproxy.cfg/haproxy_mission1)

![alt text](https://raw.githubusercontent.com/Kovrei/Clustering-and-load-balancing/main/img/s1s2.PNG)

## Mission 2

*Запустите три simple python сервера на своей виртуальной машине на разных портах
*Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
*HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
*На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

[конфигурационный файл haproxy](https://github.com/Kovrei/Clustering-and-load-balancing/blob/main/haproxy.cfg/haproxy_mission2)

![alt text](https://raw.githubusercontent.com/Kovrei/Clustering-and-load-balancing/main/img/s1s2s3example.PNG)

![alt text](https://raw.githubusercontent.com/Kovrei/Clustering-and-load-balancing/main/img/s1s2s3.PNG)
