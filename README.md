# Задание по HTML/CSS для Школы Программистов HeadHunter 2017/2018

Доверстать страницу, используя:
* Макет (см. [PSD-файл](markup/Unicorn-PSD-Template.psd) или [JPG-файл](markup/Unicorn-PSD-Template.jpg)).
* CSS-методологию [БЭМ](https://ru.bem.info/method/key-concepts/) (только методологию).
* CSS-препроцессор [LESS](http://lesscss.org).
* [Модульную сетку из Twitter Bootstrap](https://getbootstrap.com/docs/4.0/layout/grid/) (желательно только сетку).

Плюсом будет:
* Аккуратность.
* Соблюдение рекомендаций, которые были даны на лекциях.

Для выполнения задания необходимо:
* [Форкнуть](https://help.github.com/articles/fork-a-repo/) этот репозиторий.
* Непосредственно доверстать страницу :).
* Сделать [пулл-реквест](https://help.github.com/articles/creating-a-pull-request/) и захостить верстку с помощью [gh-pages](https://pages.github.com), чтобы посмотреть дополненный проект можно было [аналогично данному](https://sergdenisov.github.io/hh-school-2017-html-css-homework/).
* Прислать ссылку мне в Slack :).

Страничку лучше отдавать с веб-сервера (статично может не работать). Если вы не знаете как это сделать, то простейший вариант — [`http-server`](https://www.npmjs.com/package/http-server). Для этого вам нужно:
1. Установить Node.js (если не установлена). Вот [тут есть инструкция](https://docs.npmjs.com/getting-started/installing-node.).
2. Проверить, что все ок. В данном случае, нас интересует `npm`. Должна показаться версия после выполнения команды: `npm -v`.
3. Поставить глобально сам сервер: `npm install http-server -g` (могут потребоваться права администратора).
4. Зайти в папку с проектом (в корень) и выполнить команду: `http-server -c-1 -a 127.0.0.1 -p 8080`.
5. В итоге, должно быть выведено что-то типа:
```bash
Starting up http-server, serving ./
Available on:
  http://127.0.0.1:8080
Hit CTRL-C to stop the server
```
Соответственно, нужно смотреть страницу в браузере уже на `http://127.0.0.1:8080`.
