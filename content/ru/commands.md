+++
title = "Консольные команды"
+++

Программа также имеет консольный интерфейс

**Использование:** `crow [опции] текст`

| Опция                      | Описание                                                                                             |
| -------------------------- | ---------------------------------------------------------------------------------------------------- |
| `-h, --help`               | Показать справку                                                                                     |
| `-v, --version`            | Показать информацию о версии                                                                         |
| `-c, --codes`              | Показать все коды языков                                                                             |
| `-a, --audio-only`         | Показывать только текст для озвучивания при использовании  `--speak-translation` or `--speak-source` |
| `-s, --source <code>`      | Указать язык исходного текста (по умолчанию движок попытается определить язык самостоятельно)        |
| `-t, --translation <code>` | Указать язык(и) перевода, соединенные через '+' (по умолчанию используется язык системы)             |
| `-l, --locale <code>`      | Указать язык переводчика (по умолчанию используется системный язык)                                  |
| `-e, --engine <engine>`    | Указать движок переводчика ('google', 'yandex' или 'bing'), Google используется по умолчанию         |
| `-p, --speak-translation`  | Озвучить перевод                                                                                     |
| `-u, --speak-source`       | Озвучить исходный текст                                                                              |
| `-f, --file`               | Считать исходный текст из файлов. Аргументы будут интерпретироваться как пути к файлам               |
| `-i, --stdin`              | Добавить данные из stdin в исходный текст                                                            |

**Примечание:** Если не передать программе аргументы запуска, то запустится графический интерфейс.