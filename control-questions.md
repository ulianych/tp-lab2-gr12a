# Контрольные вопросы

1. Командная оболочка (командный интерпретатор) - это программа, которая позволяет пользователю взаимодействовать с операционной системой путем ввода и выполнения команд. 
2. В операционной системе macOS используется командный интерпретатор zsh (Z shell). 
3. Приложение Terminal в macOS предназначено для работы с командной строкой, выполнения команд и управления файлами и процессами. 
4. Полный путь к домашней папке может быть, например, `/Users/username`. Для определения текущего каталога можно воспользоваться командой `pwd`, для перехода в домашний каталог можно воспользоваться командой `cd ~`. 
5. Содержимое каталога системных конфигурационных файлов можно вывести командой `ls -la /etc`. 
6. Чтобы изменить командный интерпретатор с zsh на bash, можно воспользоваться командой `chsh -s /bin/bash`. 
7. Инициализация репозитория выполняется при создании нового проекта или когда необходимо начать отслеживание изменений. Командой для инициализации репозитория является `git init`. 
8. Коммит - это операция в Git, при которой происходит сохранение изменений в репозитории. 
9. Перед созданием новой ветки важно создать коммит, чтобы сохранить текущее состояние проекта и иметь возможность легко вернуться к нему в случае необходимости. 
10. Файл в репозитории может находиться в трех состояниях: неотслеживаемый, отслеживаемый, измененный. Изменение состояния файла происходит при выполнении команд `git add` и `git commit`. 
11. Ветка - это абстракция в Git, которая позволяет работать над изменениями проекта отдельно от основной ветки. 
12. Обязательным условием для формирования ветки master после клонирования репозитория или его инициализации является наличие хотя бы одного коммита в репозитории. 
13. HEAD - это указатель на текущий коммит в Git. 
14. Способы создания веток в Git: командой `git branch <branch_name>`, командой `git checkout -b <branch_name>`, командой `git switch -c <branch_name>`. 
15. Текущую ветку можно узнать командой `git branch`. 
16. Для переключения между ветками можно использовать команду `git checkout <branch_name>` или команду `git switch <branch_name>`. 
17. Для слияния двух веток можно воспользоваться командой `git merge <branch_name>`. 
18. Для подключения внешнего репозитория к локальному нужно использовать команду `git remote add <remote_name> <repository_URL>`. 
19. Последний коммит можно отменить командой `git reset HEAD^`. 
20. Команда `rebase` используется для переноса коммитов с одной ветки на другую, чтобы создать линейную историю коммитов. 
21. Создание форка требуется, например, для внесения изменений в проект, не имея прямого доступа к исходному репозиторию. Для создания форка можно воспользоваться кнопкой "Fork" на GitHub или командой `git fork <repository_URL>` в консоли.
