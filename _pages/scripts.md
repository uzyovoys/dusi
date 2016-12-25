---
layout: default
title: Что такое Скрипты
permalink: /scripts/
---

Скрипты - это дополнительные функции Вашего виртуального ассистента в дополнение к штатным функциям.

Кроме того - это способ автоматизировать многие действия так, что Ваш ассистент начнет атоматически выполнять те или иные действия в зависимости от событий окружащего мира, без дополнительных команд с Вашей стороны.

По сути скрипт - это **сочетание** [событий](/scripts/events/) и [действий](/scripts/actions/), которые должен выполнить Ваш ассистент, когда происходят эти события.
Каждое действие скрипта может выполняться или пропускаться в зависимости от [условий](/scripts/conditions/), в которых можно оперировать значениями [переменных](/scripts/vars/) и использовать различные [функции](/scripts/functions/).

## Пример

Самым простым примером является возможность с помощью скрипта научить своего ассистента отвечать что-либо на какую-то определенную фразу.
В этом случае событием для ассистента будет просто Ваша фраза, а действием - его голосовой ответ на эту фразу.

### Шаблоны фраз

Фразы, активирующие скрипт, описываются с помощью [специальных шаблонов](/scripts/patterns/), что позволяет Вам использовать очень гибкие фразы, а не только какие-то определенные слова.

Пример посложнее - можно научить ассистента включать дома свет, как только вы пришли вечером домой.

## Как создаются скрипты

В самом приложении есть раздел Скрипты, где Вы можете создать новый скрипт, указать для него название, добавить любое количество событий и действий.
Далее скрипт можно тестировать или публиковать во внутреннем маркете скриптов.
