# online-store-api
В этом репозитории хранится API для интернет-магазина с заглушками. API возвращает тестовые данные. 

Пожалуйста, используйте это API на курсах по frontend-разработке на языке Javascript, а также при разработке мобильного приложения для интернет-магазина. С его помощью вы получите работающий интернет-магазин с тестовыми данными.

Описание соглашений по работе API содержится в файле [API Description.xlsx](https://github.com/ArtoVoloshenko/online-store-api/blob/master/online-store-api-master/API%20Description.xlsx) в корне репозитория. 

# Правила использования статических JSON-файлов
Для получения статического JSON-ответа можно обращаться по URL-адресу 

https://raw.githubusercontent.com/ArtoVoloshenko/online-store-api/master/online-store-api-master/responses/..нужныйФайл.JSON

[![N|Solid](https://img.icons8.com/ios-filled/100/000000/json.png)](https://developer.mozilla.org/ru/docs/Web/JavaScript)

Это вернет чистый JSON-ответ согласно прилагающейся документации.

Обратите внимание, что кросс-доменные запросы не поддерживаются браузерами, ниже IE9. В случае использования такового
рекомендуется разместить репозиторий локально на компьютере, где производится тестирование.

Для кросс-доменных запросов установка свойства content в что-то отличное от application/x-www-form-urlencoded, multipart/form-data или text/plain приведет к тому, что
браузер отправит дополнительный предварительный OPTIONS-запрос на сервер.
# Данный репозиторий был создан для публикаций 
## домашних заданий курса "Продвинутый курс Java Script" онлайн Университета GeekBrains
[![N|Solid](https://img.icons8.com/material-rounded/250/000000/js.png)](https://geekbrains.ru/)
