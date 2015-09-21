# Cadesplugin

Альтернативная библиотека для работы с [плагином от КриптоПРО](https://www.cryptopro.ru/sites/default/files/products/cades/demopage/main.html).

Поддерживает плагин начиная с версии 2

Последняя протестированная версия 2.0.12245

Заменяет родную библиотеку [cadesplugin_api.js](http://www.cryptopro.ru/sites/default/files/products/cades/cadesplugin_api.js)

Отличия от родной библиотеки
--------------------------------------

1. Не запускает проверку плагина сразу при загрузке файла
2. Использует jQuery.Deferred вместо нативных промисов
3. Не создает лишних переменных в глобальной области видимости
