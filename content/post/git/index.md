---
title: Управление версиями. Git. 
subtitle: В этом посте я расскажу некоторые сведения на тему "Управление версиями. Git."

# Summary for listings and search engines
summary: Управление версиями Git.


# Link this post with a project
projects: []

# Date published
date: '2023-03-16T00:00:00Z'

# Date updated
lastmod: '2023-03-616T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

authors:
  - admin
  - Тимур Митрофанов

tags:
  - Academic


categories:
  - GIT
  
---

## Система контроля версий (Version Control System) 

**Система контроля версий** (Version Control System)– это инструмент, который используется для отслеживания, внесения и управления изменениями в программном коде. Это также можно назвать просто контролем версий.

Системы контроля версий помогает разработчикам сохранять изменения, внесенные в файл, на разных этапах, чтобы и они сами, и их коллеги могли их увидеть позже.

Существует три типа систем контроля версий:

- Локальные системы контроля версий \
- Централизованные системы контроля версий \
- Распределенные системы контроля версий.

## Что такое Git?

**Git** – это бесплатная распределенная система контроля версий с открытым исходным кодом, которую можно использовать для отслеживания изменений в ваших файлах. В Git можно работать над всеми типами и размерами проектов.

С помощью Git вы можете добавлять изменения в свой код, а затем фиксировать их (или сохранять), когда это необходимо. Это означает, что у вас есть возможность вернуться к ранее внесенным изменениям. Git работает рука об руку с GitHub. 

## Что такое GitHub?

**GitHub** – это веб-интерфейс, в котором можно хранить свои репозитории Git, а также эффективно отслеживать и управлять своими изменениями. С его помощью разные разработчики имеют доступ к коду одного проекта. У вас есть возможность вносить свои собственные изменения в проект одновременно с другими разработчиками.

Например, если вы вдруг допустили какую-то ошибку во время внесения изменений, вы можете легко вернуться к предыдущему этапу, где ошибки еще нет.

## Принципы работы с Git.

Принципы работы с Git
При работе с Git в среде разработчиков принято руководствоваться тремя принципами:

1. Регулярно коммитить ― сохранять изменения в Git. Такой подход позволит сохранять более подробную историю версий и быстро замечать ошибки в коде.

2. Создавать новые ветки. Они позволяют легко управлять изменениями, особенно параллельными. Лучше создать ещё одну ветку, чем что-то испортить в старой.

3. Чётко и лаконично описывать коммиты. Изменения кода, которые отправляются в Git, обязательно должны содержать пояснения и комментарии по добавленным правкам, доработкам и изменениям. Это значительно облегчает совместную работу и помогает быстрее разбираться в своем старом коде.

## Основные команды Git

Контроль версии Git — представляет собой набор программ командной строки, это 
распределенная система контроля версий, что означает, что каждый разработчик имеет свою 
собственную копию репозитория с полной историей изменений. Рассмотрим основные 
команды для работы с Git.

Есть несколько основных команд Git, которые должен знать каждый разработчик:

- git config - эта команда используется для того, чтобы установить имя пользователя, адрес электронной почты и ветку пользователя, чтобы определить, кто зафиксировал изменения при работе над проектом. \

- git init - эта команда используется для того, чтобы запустить Git в своем проекте для отслеживания изменений, внесенных в проект. \

- git remote add origin -  установит источник для нашего репозитория, где хранить наш код в облаке. \

- git add - эта команда добавляет ваш файл в промежуточную область (staging area). \

- git commit - эта команда фиксирует любой файл, который был добавлен с помощью команды git add, а также все файлы в промежуточной области. \

- git clone - эта команда используется для того, чтобы скопировать существующий репозиторий в другую область из одного места в другое. \

- git push - эта команда используется для того, чтобы загрузить/отправить файлы из локального репозитория/хранилища в другое хранилище, например, в удаленное, такое как GitHub. \

- git rm - эта команда используется для того, чтобы удалить файл из рабочего репозитория. \

- git branch - эта команда используется для того, чтобы проверить текущую ветку, над который вы работаете, main или master. \

- git diff - Git покажет вам разницу между кодом, который у вас есть сейчас, и кодом, когда он был сохранен в последний раз. \

- git log - мы можем просмотреть сделанные нами коммиты. \

- git checkout - вернуться и увидеть изменения в нашем коде из предыдущего коммита. \

- git merge - возьмет все коммиты, которые вы сделали в этой ветке, и вставит их в основную ветку, сохранив вашу работу. \

- git status – посмотреть статус коммитов (их количество, внесенные изменения).


```python
import libr
print('hello')
```
