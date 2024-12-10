# Установка и запуск py-interpreter

Этот гайд поможет вам установить и запустить проект **py-interpreter** из репозитория GitHub. Мы рассмотрим все шаги, начиная с клонирования репозитория и заканчивая запуском основного скрипта.

## Шаг 1: Клонирование репозитория

Первым шагом необходимо клонировать репозиторий проекта с GitHub. Для этого откройте терминал и выполните следующую команду:

```bash
git clone https://github.com/Python-shik/py-interpreter.git
```

Эта команда создаст на вашем устройстве локальную копию репозитория. В результате, вы сможете работать с кодом проекта напрямую.

## Шаг 2: Переход в каталог репозитория

После клонирования репозитория вам нужно перейти в его директорию, чтобы продолжить установку и настройку. Используйте следующую команду:

```bash
cd py-interpreter/
```

Теперь вы находитесь в папке с проектом, что позволит вам выполнять дальнейшие действия по настройке.

## Шаг 3: Установка виртуального окружения

Рекомендуется использовать виртуальное окружение для изоляции зависимостей проекта от других программ на вашем компьютере. Виртуальное окружение позволяет избежать конфликтов между различными версиями библиотек.

Для создания виртуального окружения выполните следующую команду:

```bash
virtualenv venv
```

После создания виртуального окружения его нужно активировать. В зависимости от операционной системы, используйте одну из следующих команд:

- **Для Linux или macOS**:
  ```bash
  source venv/bin/activate
  ```

- **Для Windows**:
  ```bash
  venv\Scripts\activate
  ```

После активации виртуального окружения, в начале строки терминала должно появиться название окружения (например, `(venv)`), что означает, что теперь все команды выполняются в изолированном пространстве.

## Шаг 4: Установка зависимостей

Для корректной работы проекта необходимо установить все зависимости, перечисленные в файле `requirements.txt`. Сделать это можно с помощью следующей команды:

```bash
pip install -r requirements.txt
```

Эта команда скачает и установит все необходимые пакеты и библиотеки, чтобы проект работал корректно.

## Шаг 5: Запуск основного скрипта

Теперь, когда все зависимости установлены и виртуальное окружение активировано, можно запустить основной скрипт проекта. Используйте следующую команду:

```bash
python main.py
```

После этого скрипт **py-interpreter** начнет свою работу. Если возникнут какие-либо ошибки, убедитесь, что все зависимости установлены правильно и что виртуальное окружение активно.

## Заключение

Вы успешно клонировали репозиторий, создали виртуальное окружение, установили все зависимости и запустили проект. Теперь вы можете в полной мере использовать возможности **AI-interpreter**. Если вам понадобится остановить виртуальное окружение, просто выполните команду:

```bash
deactivate
```

Это вернет вас к стандартной командной строке вашей системы.

Если у вас возникли вопросы или сложности с выполнением шагов, не стесняйтесь обращаться к документации проекта или задавать вопросы в сообществе на GitHub. Удачи в использовании **py-interpreter**!

