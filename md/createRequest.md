Описание кода:

Эта функция отправляет POST-запрос на указанный URL-адрес (https://jscp-diplom.netoserver.ru/) с заданным телом запроса (body) в формате "application/x-www-form-urlencoded". Затем функция ожидает ответ от сервера и вызывает функцию обратного вызова (callback), передавая в нее полученный ответ в формате JSON (xhr.response). Обратный вызов будет выполнен только после того, как ответ будет получен от сервера и распарсен.