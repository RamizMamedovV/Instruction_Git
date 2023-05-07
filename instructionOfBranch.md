##  **RABOTA S VETKAMI**

* `git branch`- <span style = "color: yellow;"> посмотреть список веток в репозитории </span>
```
NOTE:
v spiske tekushaya vetka budet videlena cvetom i oboznachena (*)
````

* `git branch nameOfBranch` - создать ветку "nameOfBranch"

* `git branch -d nameOfBranch` - удалить ветку "nameOfBranch"
```
NOTE:
Komanda git branch -D nameOfBranch udalit etu vetku, esli daje v ney ne bilo fiksacii - commit
```

* `git checkout nameOfBranch^` - переход на ветку"nameOfBranch"
```
NOTE:
git checkout nameOfBranch^ (zamenyayet 2 komandi "inache mi delelibi tak": 1. git log, zatem skopirovalibi
"hach cod" predidushego commita i vipolnili comandu git checkout "hach cod")
 - переход по ветке "nameOfBranch" в предидщее состояние, t.e. HEAD perydet po vetke vishe.
 git checkout nameOfBranch^^ - toje samoye, no na 2 shaga nazad "^^^- 3 shaga i t. d."

 git checkout nameOfBranch~"num" (git checkout HEAD~4) - qde num mojet bit lyubaya cifra.
 crazu peremestit na num- kolichestvo commitov nazad 
```
* `git checkout nameOfBranch` - переход на ветку"nameOfBranch"

* `git checkout -b newNameOfBranch` - создать ветку и сразу переход на нёё "newNameOfBranch"
```
NOTE:
Mojno takje vospolzovatsa novoy rekomendaciyey git i sovershit sozdaniye i momentalniy perexod odnoy komandoy
git switch -c newNameOfBranch
```

* `git merge nameOfBranch` - для слияния ветки
```
NOTE:
- Ne zabivayem pered vixoda iz lyuboy vetki i posle vipolneniya merge vipolnyat komandi fiksacii git add i git commit

- Dlya OTMENI sliyaniya ispolzuem komandu git merge --abort pered fiksaciyey git add i git commit
```