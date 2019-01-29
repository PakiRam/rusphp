# rusphp

Набор php-классов (и их методов)

## Использование

О способах использования (*установки*) [читайте здесь](http://fkn.ktu10.com/node/8592).

Версии и совместимость с PHP:
* Версии `v1.*` -- для поддержки кода php5.5 и старше (например, для `array()` вместо `[]`),
   эти же версии кода попадают в остальные ветки, но в `1.*` можно найти (добавить) код, адоптированный под старые версии.
* Остальные версии ориентированы на работу в `php7` и выше.

## Цели и задачи библиотеки

Писать сюда функции общего назначения, которые можно было бы использовать в разных проектах 
-- как минимум это касается удобных функций-обёрток (как `ItForFree\rusphp\Log\SimpleEchoLog.php`), 
как максимум -- нового полезного функционала для специфических областей (`ItForFree/rusphp/Html/Table/ArrayRebuilder.php`)

## Что уже есть (основной функционал)

Содержит классы/функции/методы для работы c:

* С [Логами (журналирования для отладки)](docs/logging.md)
* С [Картинками (обрезка изображений "на лету")](src/File/Image/README.md)
* C SSH соединением
* Архивами
* Измерение используемой оперативной памяти
* URL: `ItForFree\rusphp\Network\Url` позволяет удобно работать с URL (адресами ссылок)
* [Создание файла c исходным кодом проекта](src/Documentaion/FileCreator/README.md)
* [Работа с телефонными номерами](src/Common/Phone/PhoneNumber/README.md)
* [Безопасноть (в частности секрентые ключи/токены)](src/PHP/Security/README.md)
* [Работа с онлайн-картами (яндекс и google maps)](src/Common/Map/README.md)
* [Для работы с доменами](src/Network/Domain/README.md)
* [Для работы с временем/временными периодами (в том числе интервалы между запросами к API)](src/Common/Time/README.md)

### Дополнения к другим системам/библиотекам

* Тестирование [с помощью codeception](docs/codeception.md)


## Потомки rusphp ;) (вынесено в отделные пакеты)

* Web-клиенты к различным системам: https://github.com/it-for-free/php-web-clients


