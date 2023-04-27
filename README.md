Learning how to use GitHub
<hr>


**1. Создать внешний репозиторий с названием TXT**

**2.Клонировать репозиторий TXT на локальный компьютер**
```
$ git clone git@github.com:KristinaMarkevich/TXT.git
```
**3.Внутри локального TXT создать файл “new.txt”**
```
$ touch new.txt
```
**4.Добавить файл под гит**
```
$ git add new.txt
```
**5. Закоммитить файл**
```
$ git commit -m "new.txt"
```
**6. Отправить файл на внешний GitHub репозиторий**
```
$ git push
```
**7. Отредактировать содержание файла “new.txt” - написать информацию о себе**
```
$ cat > new.txt
Name - Kristina Markevich
Age - 25
Pets - cat Kuzya
Future wanted salary - 400 USD
```
**8. Отправить изменения на внешний репозиторий**
```
$ git add new.txt
$ git commit -m "new.txt"
$ git push
```
**9. Создать файл preferences.txt**
```
$ touch preferences.txt
```
**10.  В файл preferences.txt” добавить информацию о своих предпочтениях**
```
$ cat > preferences.txt
Favorite movie - Titanic,
Favorite TV-Show - Breaking bad,
Favorite food - ramen,
Favorite season - summer,
Country i'd like to visit - Japan 
```
**11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**
```
$ cat > skills.txt
skill #1 - termimal,
skill #2 - SQL,
skill #3 - postman,
skill #4 -creating bug reports 
```
**12. Сделать коммит в одну строку**
```
$ git add . 
$ git commit -m "comment"
```
**13. Отправить сразу 2 файла на внешний репозиторий**
```
$ git push
```
 **14. На веб интерфейсе создать файл bug_report.txt**
 
 **15. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
 
 **16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT**
 
 **17. Сделать Commit changes (сохранить) изменения на веб интерфейсе**
 
 **18. Синхронизировать внешний и локальный репозиторий TXT**
 ```
$ git pull
```
