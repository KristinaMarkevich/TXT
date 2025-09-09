# TXT
 
 **1. Создать внешний репозиторий c названием TXT.**
 **2. Клонировать репозиторий TXT на локальный компьютер.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github
$ git clone https://github.com/KristinaMarkevich/TXT.git
```
 **3. Внутри локального TXT создать файл “new.txt”.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ touch new.txt
```
 **4. Добавить файл под гит.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git add new.txt
```
 **5. Закоммитить файл.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git commit -m "add file"
```
 **6. Отправить файл на внешний GitHub репозиторий.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git push
```
 **7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ cat > new.txt
 Info
  Surname Markevich
  Name>Kristina
  Age>28
  Cat 1
  Future wanted salary 1000
```
 **8. Отправить изменения на внешний репозиторий.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git add new.txt
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git commit -m "add new imfo"
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git push
```
 **9. Создать файл preferences.txt**
 **10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ cat > preferences.txt
i like pizza
```
 **11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ cat > skills.txt
being extra cool
```
 **12. Сделать коммит в одну строку.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git add .
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git commit -m "add new files"
```
 ****13. Отправить сразу 2 файла на внешний репозиторий.**
 ```
 Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git push
```
 **14. На веб интерфейсе создать файл bug_report.txt.**
 **15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 **16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.**
 **17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
 
 **18. Синхронизировать внешний и локальный репозиторий TXT**
 ```
Kristina@DESKTOP-CPUR73B MINGW64 ~/desktop/github/TXT (main)
$ git pull
```
