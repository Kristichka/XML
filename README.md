# XML
 21. Создать внешний репозиторий c названием XML.
   Repositories -NEW - XML - Create repository
   
22. Клонировать репозиторий XML на локальный компьютер.
    git clone https://github.com/Kristichka/XML.git
  
 23. Внутри локального XML создать файл “new.xml”.
   cd XML
   new.xml
   
 24. Добавить файл под гит.
    git add .
    
 25. Закоммитить файл.
    git commit -m" add new file"
    
26. Отправить файл на внешний GitHub репозиторий.
    git push
    
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
     cat >> new.xml
<my_info>
<surname>Васюра</surname>
<first_name>Кристина</first_name>
<patronymik>Алексеевна</patronymik>
<age>30</age>
<pet>кошка -Малышка</pet>
<wages>2000</wages>
</my_info>
   Cntr+C
   
 28. Отправить изменения на внешний репозиторий.
   git add.
   git commit -m"my info"
   git push 
   
 29. Создать файл preferences.xml
     touch preferences.xml
     
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
  cat >> preferences.json
 {
  "favorite movie": "Batman",
  "favorite series": "Shameless",
  "favorite food": "chicken",
  "favorite season": "summer",
  "country": "Cyprus"
}
Cntr+C
 
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
  cat > sklls.json
<knowledge_on_the_course>тестирвание приложений и сайтов</knowledge_on_the_course>
Cntr+C
  
 32. Сделать коммит в одну строку.
   git commit -a -m"add two files"
   
 33. Отправить сразу 2 файла на внешний репозиторий.
      git push origin --all
 
 34. На веб интерфейсе создать файл bug_report.xml.
 
     add file - Create new file -  bug_report.xml.
 
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
     bug_report
      <ID_бага>124454656</ID_бага>
      
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 <bug_report>
  <ID_бага>124454656</ID_бага>
  <короткое_описание>Приложение зависает, при попытке сохранения текстового файла размером больше 50Мб</короткое_описание>
  <проект>текстовый редактор</проект>
  <версия_приложения>последняя версия iOS v11.2.3</версия_приложения>
 
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Делаем изменения - Commit changes
 
 38. Синхронизировать внешний и локальный репозиторий XML
 git pull
