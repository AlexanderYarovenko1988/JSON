##JSON
 1. Создать внешний репозиторий c названием JSON.
>GitHub -> Create New Repository JSON 
 2. Клонировать репозиторий JSON на локальный компьютер.
>git clone git@github.com:AlexanderYarovenko1988/JSON.git 
 3. Внутри локального JSON создать файл “new.json”.
>cd JSON && touch new.json
 4. Добавить файл под гит.
>git add new.json
 5. Закоммитить файл.
>git commit -m "newfile"
 6. Отправить файл на внешний GitHub репозиторий.
>git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
>vim new.json
>>{
>>  "surname": "Yarovenko",
>>  "name": "Alexander",
>>  "patronymic": "Yarovenko",
>>  "age": 34,
>>  "pets": 0,
>>  "future salary": "1000$"
>>}
 8. Отправить изменения на внешний репозиторий.
>git commit -am "change json" && git push
 9. Создать файл preferences.json
touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
>vim preferences.json
>>{
>>    "Film" : "Patriot",
>>    "TV series" : "Friends",
>>    "Food" : "dumplings",
>>    "Season" : "Autumn",
>>    "Country" : "Kanada"
>>}
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
>touch sklls.json vim skills.json
>>{
>>    "Skills" : "Hard and soft skills"
>>}
 12. Отправить сразу 2 файла на внешний репозиторий.
>git add . && git commit -m "preferences and skill" && git push
 13. На веб интерфейсе создать файл bug_report.json.
>GitHub -> add file -> create new file -> bug_report.json
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>GitHub -> Commit changes
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
>GitHub -> bug_report.json -> edit this file
>>{ "Summary" : "In CTR (Click through ratio) ‘Total’ row calculation is wrong", "Product" : "Example product", "Version" : 1.0, "Platform" : "PC", "Version" : >>"Windows 2000", "Status" : "NEW", "Severity" : "Major", "Priority" : "P1", "Component" : "Publisher stats", "Steps to reproduce" : 1, "Expected result" : "wow" }
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>GitHub -> commit changes
 17. Синхронизировать внешний и локальный репозиторий JSON
>git pull
