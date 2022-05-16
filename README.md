 # 1. Создать внешний репозиторий c названием XML.
 
    веб интерфейс github.com, залогинитьс, перейти в Repositories, создание новой репозитории New, имя XML, Add a ReadMe file, Create repository
    
 # 2. Клонировать репозиторий XML на локальный компьютер.
 
     cd ..
     git clone https://github.com/Ilyamrkl/XML.git
     
 # 3. Внутри локального XML создать файл “new.xml”.
 
     cd XML
     touch new.xml
     
 # 4. Добавить файл под гит.
     
     git add new.xml
     
 # 5. Закоммитить файл.
      
      git commit -m 'Create new.xml'
      
 # 6. Отправить файл на внешний GitHub репозиторий.
      
      git push
 
 # 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 
      vim new.xml
      
 # 8. Отправить изменения на внешний репозиторий.
 
       git commit -m 'Update new.xml' && git push
       
 # 9. Создать файл preferences.xml
 
      toush preferences.xml
      
 # 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 
       vim preferences.xml
       
 # 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 
      vim skills.xml
      
 # 12. Сделать коммит в одну строку.
 
        git add . && git commit -m 'Update file'
        
 # 13. Отправить сразу 2 файла на внешний репозиторий.
 
        git push
        
 # 14. На веб интерфейсе создать файл bug_report.xml.
 
       веб интерфейс Add file - Create new file создание файла - название bug_report.json
       
 # 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
         коммит Create bug_report.xml и сохранить
         
 # 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 # 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
      Update bug_report.json - Commit changes
      
 # 18. Синхронизировать внешний и локальный репозиторий XML
     
       git pull
