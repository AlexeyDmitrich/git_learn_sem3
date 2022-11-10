# ** Git: инструкция по эксплуатации

## Предварительная настройка git

Чтобы представиться программе git нужно ввести команды:

    git config --global user.name "имя пользователя"

    git config --global user.email "адрес почты"

## создание репозитория

чтобы инициализировать репозиторий прописываем

    git init

## добавление в индекс

чтобы добавить в индекс для фиксации в следующем коммите нужно ввести команду

    git add <имя файла>

## фиксация изменений

чтобы зафиксировать изменения, добавленные в индекс, нужно ввести команду 

    git commit

лишняя строка

todo:

git commit -m

git commit -a

git commit -am

git log

git log --oneline

git log --all

git diff

git diff \<hash1> \<hash2>

git checkout

git status

