## Задачи по структуре репозитория
* ~~Перенести уровни в поддиректории, с учетом скриптов сборки, так чтобы не возникло проблем с путями~~
* Написать документацию для контрибьюта
* Написать Readme (добавить readme из лаб)
* Убрать chainXX в подпапку chain. Цепочек уже довольно много, нужно их спрятать, а то глазом не охватывается

## Задачи по игровой платформе
* ~~Разобраться с костылем с сетью в докере~~
* ~~Изменить способ доставки флагов для заданий с внешней проверкой~~

## Задачи по сборке тасков
* ~~Автоматизировать все таски, так чтобы уровень гененерировался не руками. Все должно собираться скриптами 4, 10+~~
* ~~Допилить все сборки тасков, так чтобы докер считывал флаг аргументом (как в таске 12).
  Флаги не должны дублироваться, они должны лежать в одном конфиге~~
* ~~Разобраться со сборкой заданий, где должны удаляться лишние бинарники (5-9 задания)~~
* ~~Пофиксить кривоскрипт сборки build.sh (переписать на питоне или рубях например)~~
* Найти и поправить кронжоб, запускающий kill docker. Где-то что-то лишнее есть (сравнить с продом)
* Поправить сборку тасок с серверной частью. Сейчас ансиблу приходится дважды заводить одного и того же юзера.
* Разобраться с задачами 10,11,12. 11,12 одинаковые, нужно оставить только 12ю задачу. написать 2 новых - 10,11.
* В будущем, если вдруг концепция именования suzenX и suzenXserver изменится, нужно будет исправить скачивание образов