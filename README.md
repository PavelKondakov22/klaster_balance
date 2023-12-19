Kondakov Pavel
### Задание 1
- Запустите два simple python сервера на своей виртуальной машине на разных портах
![alt text](https://github.com/PavelKondakov22/klaster_balance/blob/main/http1.png)  
![alt text](https://github.com/PavelKondakov22/klaster_balance/blob/main/http2.png)  
- Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](2/)
- Настройте балансировку Round-robin на 4 уровне.
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.  
Решение 1
![alt text](https://github.com/PavelKondakov22/klaster_balance/blob/main/z1%203%20p.png)  

### Задание 2
- Запустите три simple python сервера на своей виртуальной машине на разных портах
- Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
- HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
- На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.
