# Инструкция по Git

Прежде чем создавать репозиторий и инициализировать Git, проверьте текущую установленную версию пограммы:

    git --version

После установки необходимо «представиться» системе контроля версий. Это нужно сделать всего один раз, и Git запомнит Вас. Для этого нужно ввести в терминале 2 команды: 

    • git config --global user.name "[name]"
    • git config --global user.email "[email address]"

## Основные команды Git
`- Инициализация репозитория:`

    git init  

`- Показыть текущее состояние git:`

    git status

`- Добавить содержимое рабочего каталога 
в индекс (staging area) для последующего коммита:`

    git add [name_file]
    git add .

`- Зафиксировать или сохранить изменения:`  

    git commit -m "Comment"
    git commit -am "Comment"

`-  Показать журнал изменений:`  

    git log
    git log --oneline
    git log --graph 

`- Переключение между версиями:`  

    git checkout [hash] (master)

`- Показать разницу между текущим файлом и сохранённым:`    

    git diff


`- Создать новую ветку;`

    git branch [name branch]

`- Создать новую ветку и перейте в нее:` 

    git checkout -b [name branch]

`- Слить две ветки :`

    git merge [master] [branch]

 `- Отменить слияние:`

    git merge --abort  

`- Удалить ветку:`   

    git branch -d [branch]