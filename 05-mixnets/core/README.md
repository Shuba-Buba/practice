# Вариант ноды для микснетов

### TODO

1. [X] Работа с временем
2. [X] Предотвращение циклов
3. [ ] Обработка случаев отказа одной из нод

## Ограничения

* Не умеем запускать на разных портах, дефолтный порт 8000.
* Не умеем в рантайме добавлять новые ноды или новые контакты.

## Запуск

На вход программа сразу принимает адреса известных ей нод, ключи контактов, свой публичный ключ.
Инструкции описаны в `--help`

## Использование. Команды
* `an` - разослать анонс известным нодам
* `send \<recevier key> "\<message>"` - отправка сообщений
* `table` - таблица маршрутизации
* `friends` - контакты

## Тестирование
Тестовая среда расположена в файле `test_env.py`