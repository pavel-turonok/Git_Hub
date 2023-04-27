 <div>
 <img src="https://github.com/devicons/devicon/blob/master/icons/git/git-original-wordmark.svg" title="Git" **alt="Git" width="40" height="40"/>
 </div> 
 
 ### GitHub/Branch
 ___
 ### GitHub_HW
 
 #### JSON
 1. Создать внешний репозиторий c названием JSON.
 ``` 
  1)Переходим во вкладку Repositories и жмем New,
  2)Вводим имя репозитория, ставим radio buttom Public и Add a README file.
 ```
 2. Клонировать репозиторий JSON на локальный компьютер.
 ```
  1)Копируем ссылку на рипозиторий в буфер обмена во вкладке Code
  2)git clone + скопируемая ссылка
 ```
 3. Внутри локального JSON создать файл “new.json”.
 ```
  touch new.json
 ```
 4. Добавить файл под гит.
 ```
 git add . либо git add touch new.json
 ```
 5. Закоммитить файл.
 ```
 git commit -m "messege"
 ```
 6. Отправить файл на внешний GitHub репозиторий.
 ```
 git push
 ```
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 ```
 vim new.json
 ```
 8. Отправить изменения на внешний репозиторий.
  ```
  1)git add . либо git add touch new.json
  2)git commit -m "messege"
  3)git push
 ```
 9. Создать файл preferences.json
 ``` 
  touch preferences.json
 ```
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```  
 vim preferences.json
```
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 ```
 cat > skills.json
 ```
 12. Отправить сразу 2 файла на внешний репозиторий.
  ```
  git add .
  git commit preferences.json skills.json -m "messege"
  git push
 ```
 13. На веб интерфейсе создать файл bug_report.json.
  ```
  1) Жмем открываем вкладку add file, жмем create new file
  2) Вводим имя и формат файла
 ```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ``` 
  Жмем Commit new file 
 ```
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 ```
  На нужном нам файле жмем Edit this file
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ``` 
  Жмем Commit new file
 ```
 17. Синхронизировать внешний и локальный репозиторий JSON
  в git bush:
 ```
  git pull
```
___
#### XML
 1. Создать внешний репозиторий c названием XML.
 ```
 1)Переходим во вкладку Repositories и жмем New,
 2)Вводим имя репозитория, ставим radio buttom Public и Add a README file.
 ```
 2. Клонировать репозиторий XML на локальный компьютер.
 ```
 1)Копируем ссылку на рипозиторий в буфер обмена во вкладке Code
 2)git clone + скопируемая ссылка
 ```
 3. Внутри локального XML создать файл “new.xml”.
 ```
 touch new.xml
 ```
 4. Добавить файл под гит.
 ```
 git add . либо git add touch new.xml
 ```
 5. Закоммитить файл.
 ```
 git commit -m "messege"
 ```
 6. Отправить файл на внешний GitHub репозиторий.
 ```
 git push
 ```
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
 ```
 vim new.xml
 ```
 8. Отправить изменения на внешний репозиторий.
 ```
 1)git add . либо git add touch new.xml
 2)git commit -m "messege"
 3)git push
 ```
 9. Создать файл preferences.xml
 ```
 touch preferences.xml
 ```
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 ```
 vim preferences.xml
 ```
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 ```
 cat > skills.xml
 ```
 12. Сделать коммит в одну строку.
 ```
 git add -A && git commit -m "messege"
 ```
 13. На веб интерфейсе создать файл bug_report.xml.
 ```
 1) Жмем открываем вкладку add file, жмем create new file
 2) Вводим имя и формат файла
 ```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Жмем Commit new file 
 ```
 15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 ```
 На нужном нам файле жмем Edit this file
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Жмем Commit new file
 ```
 17. Синхронизировать внешний и локальный репозиторий XML
  в git bush:
 ``` 
 git pull
 ```
 ___
#### TXT
1. Создать внешний репозиторий c названием TXT.
```
1)Переходим во вкладку Repositories и жмем New,
2)Вводим имя репозитория, ставим radio buttom Public и Add a README file.
```
2. Клонировать репозиторий TXT на локальный компьютер.
```
1)Копируем ссылку на рипозиторий в буфер обмена во вкладке Code
2)git clone + скопируемая ссылка
```
3. Внутри локального TXT создать файл “new.txt”.
``` 
touch new.txt
``` 
4. Добавить файл под гит.
```
git add . либо git add touch new.txt
``` 
5. Закоммитить файл.
```
git commit -m "messege"
```
6. Отправить файл на внешний GitHub репозиторий.
```
git push
``` 
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
vim new.txt
```  
8. Отправить изменения на внешний репозиторий.
```
1)git add . либо git add touch new.txt
2)git commit -m "messege"
3)git push
```
9. Создать файл preferences.txt
 ```
 touch preferences.txt
 ```
 10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
 ```
 vim preferences.txt
 ```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 ``` 
 cat > skills.txt
 ```
 12. Сделать коммит в одну строку.
 ```
 git add -A && git commit -m "messege"
 ```
 13. На веб интерфейсе создать файл bug_report.txt.
 ```
 1) Жмем открываем вкладку add file, жмем create new file
 2) Вводим имя и формат файла
 ```
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Жмем Commit new file 
 ```
 15. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 ```
 На нужном нам файле жмем Edit this file
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```
 Жмем Commit new file
 ```
 17. Синхронизировать внешний и локальный репозиторий TXT
  в git bush:
 ```
 git pull
 ```
  ___
 ### GitBranch_HW
 1. На локальном репозитории сделать ветки для:

Postman

Jmeter

CheckLists

Bag Reports

SQL

Charles

Mobile testing

1.1. Создать на GitHub репозитрой.

1.2. Клонируем внешний репозиторий на локальный репозиторий
```
git clone https://github.com/pavel-turonok/git_branch.git
```
1.3. Заходим в склонированный репозиторий
```
cd git_branch/
```
1.4. Создаем ветки Postman, Jmeter, CheckLists, Bag Reports, SQL, Charles, Mobile testing:
```
git branch Postman
git branch Jmeter
git branch CheckLists
git branch SQL
git branch Charles
git branch Mobile_testing
```
2. Запушить все ветки на внешний репозиторий
```
git push -u origin Postman
git push -u origin Jmeter
git push -u origin CheckLists
git push -u origin BagReports
git push -u origin SQL
git push -u origin Charles
git push -u origin Mobile_testing
```
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
```
git checkout BagReports
cat >>  bagrep.txt --> добавляем структуру баг репорта
нажимаем ctrl+c
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add . && git commit -m "add new file" && git push
```
5. Вмержить ветку Bag Reports в Main
```
git checkout main
git merge BagReports
```
6. Запушить main на внешний репозиторий.
```
git push -u origin main
```
7. В ветке CheckLists набросать структуру чек листа
```
git checkout CheckLists
cat >> CheckLists.json
забиваем структуру чек-листа в формате JSON
```
8. Запушить структуру на внешний репозиторий
```
git add . && git commit -m "add new file" && git push
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
```
Переходим на внешний репозиторий в ветку CheckLists, нажимаем кнопку Compare&pull requset
```
10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout main
git fetch - просмотрим действительно ли были какие-то изменения на внешнем репозитории
git pull
```
