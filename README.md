### Установка:
Чтобы установить бота необходимо:
1. Скачать и установить [Python 3.7+](https://www.python.org/downloads/) c официального сайта.
2. Скачайте репозиторий бота в ZIP архиве.
3. Распакуйте ZIP архив **в любое место**.

Дополнительно:
* Необходимо установить все требующиеся модули для Python, находящиеся в файле ****requirements.txt**. Делается это при помощи команды `pip3 install -r requirements.txt`, которую необходимо ввести в **cmd** или **powershell** перейдя предварительно в папку с ботом.
* После распаковки необходимо открыть файл `Settings.py` и заменить присутствующие там параметры на свои.
____
### Запуск бота:
Чтобы запустить бота вам необходимо открыть **cmd** или **powershell**, затем перейти в папку при помощи команды `cd /ПУТЬ_К_ПАПКЕ` и ввести в командную строку `python3 VKbot.py`.
____
### Добавление новых команд:
Чтобы добавить свою собственную команду или редактировать уже существующую вам необходимо открыть файл **Commands.py**.

Для создания своей собственной команды вам нужно скопировать предствленный в файле пример и вставить его перед ним, а после можно отредактировать только что вставленный блок кода.

Для редактирования существующей команды необходимо найти блок кода, в котором будет: `if userText == ВАША_КОМАНДА:`. После указанной строчки кода идет ваша команда, можете редактировать ответ бота или изменить алгоритм
____
### Измение сообщений выводящихся в консоль:
Чтобы изменить по своему желанию сообщения, которые выводит бот в консоль во время свой работы, вам необходимо открыть файл **VKbot.py** и найти строчку `class Logging():`. Далее идут различные ответы боты на происходящие события. Вы можете заменить сообщения или настроить свой алгоритм.
