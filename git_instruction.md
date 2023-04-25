# Rabota s Git i GitHub

## 1. NASTROYKA I USTANOVKA

 * A) Proverka nalichiya ustanovlennogo Git.
 V terminale nabrat komandu: 
 ```
  git --version 
  ```
 Esli Git ustanovlen - poyavitsa soobsheniye s info o versii programmi, inache vidast oshibku.

 * B) Ustanovka Git
 Zagrujayem poslednuyu versiyu Git s sayta:
  https://git-scm.com/book/ru/v2 
  Ustanavlivayem s nastroykami po umolchaniyu

 * C) Nastoyka Git
  Pri pervom ispolzovanii Git, neobxodimo predstavitsa. Dlya etogo v terminale neobxodimo vipolnit komandi:
  ```
git config --global user.email "your email"
git config --global user.name "your name"
  ```

  ```
  NOTE: 
  dlya proverki etix dannix nujno nabrat komandu:
  git cinfig --global --list
  ```

## 2. OSNOVNIYE KOMANDI Git

* `git init` - инициализация локального репозитория

* `git status` - получить информацию от git о его текущем состоянии

* `git add` - добавить файл или файлы к следующему коммиту

```
NOTE: 
mojno viponyat neskolko raz nakaplivaya izmeneniya pered tem, kak zafiksirovat s pomoshyu komandi `git commit` s komentariyem v ` -m"komentariy" 
```

 * `git commit-m "message"` - создание коммита.

```
NOTE: 
fiksaciya dobavlennix izmeneniy posle komandi  "git add", a takje mojno nabrat komandu: 
git commit -a -m "message", kotoraya vipolyayet 2 komandi:

 1. git add . (s tockoy!)-dlya soxraneniya izmeneniy vo VSEX FAILAX gde podklyuchen kontrol versiy Git
 
 2. git commit -m"message" dlya fiksacii i komentariy k nim
 ```

* `git log` - вывод на экран истории всех коммитов с их хеш-кодами 

```
NOTE: 
"git log -oneline"       dlya bolee korotkogo spiska commit-ov
"git log -oneline -2"    dlya otobrajeniya poslednix 2-x commit-ov
"git log -oneline -2 -p" pokajet s izmeneniyami mejdu etimi commit-ami
"git reflog"     dlya otslejivaniya vsex peremesheniy, vklyuchaya "poteryanniye" commit-i
```

* `git checkout "hachcode"` - переход от одного коммита к другому git checkout master вернуться к актуальному состоянию и продолжить работу
```
NOTE:
  "git checkout XXXX" gde "XXXX" eto perviye 4 simvola hechcoda, kotoriye mi poluchayem posle comandi "git log"
  "git checkout main" ili "git checkout master" dlya vozvrata na konecho-zafiksirovannoye polojeniye po qlavnoy vetke, kotoraya mojet nazivatsa kak "main" tak i "master"
  "git switch" - zamenyayet komandu checkout dlya peremesheniy
```

* `git diff` - увидеть разницу между текущим файлом и закоммиченным файлом

## 3. OSHIBKI I VARIANTI S KOMANDOY HELP

* `git commit (bez -m)`
```
NOTE:
eta komanda 
```
* `git help`
```
NOTE:
```
* `git commit -h`
```
NOTE:
```
