# SMSActivateWebClientListener 

Слушатель, который вызывается при каждом запросе на сервер.

Метод | Описание
---- | ----
[**handle**](SMSActivateExceptionListener.md#handle) | Вызывает при каждом запросе на сервер.

<hr/>

<a name="handle"></a>
## **handle**

Вызывает при каждой ошибке.

Принимаемые параметры:

Имя | Тип | Описание
---- | ---- | ----
cid | int | Идентификатор запроса.
request | String | Запрос, отправленный на сервер.
statusCode | int | Статус ответа.
response | String | Ответ, который пришел с сервера.

Возвращаемый тип:
`void`
