# http-proxy

## Cделано
- [x] Проксирование HTTP запросов 5 баллов  
- [ ] Проксирование HTTPS запросов 5 баллов (пытался, хз в чём проблема)  
- [x] Отправка сохраненного запроса 5 баллов  

## Запуск  

Должны быть свободны 8080, 8081, 8090 порты  
- 8080 для http запросов
- 8081 для https(предполагался)
- 8090 для работы с историей запросов

Из корневой директории go run main.go

http://localhost:8090/requests?limit=0&offset=0 - для получения списка ранее отправленных запросов 

http://localhost:8090/response/{id} - для повторения запроса
