# Gulp сборщик проектов

Что входит в сборку:
* Bower
* Browserify
* Babel
* Debowerify
* Envify

Для запуска сборки выполните следующие команды в терминале:

```
npm install
bower install
```

Запуск сборки по умолчанию осуществляется в **development** окружении, в этом окружении можно выводить свою дополнительную отладочную информацию. 
Создаются **source map's** для подключаемых browserify модулей.

Для запуска сборки в **production** выполните следующую команду:

```
NODE_ENV=production gulp
```