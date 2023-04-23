# Rabota s Git i GitHub

 ## 1. Proverka nalichiya ustanovlennogo Git.
 V terminale nabrat komandu: ` git --version `. Esli Git ustanovlen - poyavitsa soobsheniye s info o versii programmi, inache vidast oshibku.

 ## 2. Ustanovka Git
 Zagrujayem poslednuyu versiyu Git s sayta:
  https://git-scm.com/book/ru/v2 
  Ustanavlivayem s nastroykami po umolchaniyu

  ## 3. Nastoyka Git
  Pri pervom ispolzovanii Git, neobxodimo predstavitsa. Dlya etogo v terminale neobxodimo vipolnit komandi:
  ```
git config --global user.email "your email"
git config --global user.name "your name"
  ```

  ## 4. Основные команды Git

* git init - инициализация локального репозитория

* git status - получить информацию от git о его текущем состоянии

* git add - добавить файл или файлы к следующему коммиту

* git commit-m "message" - создание коммита.

* git log - вывод на экран истории всех коммитов с их хеш-кодами

* git checkout - переход от одного коммита к другому git checkout master вернуться к актуальному состоянию и продолжить работу

* git diff - увидеть разницу между текущим файлом и закоммиченным файлом