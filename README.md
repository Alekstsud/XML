# XML

 21. Создать внешний репозиторий c названием XML.               Create repository

 22. Клонировать репозиторий XML на локальный компьютер.   git clone https://github.com/Alekstsud/XML.git

$ cd xml 
 23. Внутри локального XML создать файл “new.xml”.  touch new.xml

 24. Добавить файл под гит.    git add . new.xml
 25. Закоммитить файл.       git commit -m "add xml"

 26. Отправить файл на внешний GitHub репозиторий.  git push
 
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

Внести изменения: vim new.xml
нажать клавишу "i" ввести текст

<new>
 <name>Tsudzila Aliaksandr</name>
 <age>32</age>
 <pets>0</pets>
 <future_desired_salary>1000</future_desired_salary>
</new>

Cохранить и выйти: "esc" ":wq"

28. Отправить изменения на внешний репозиторий.   git commit -m "edit xml"
                                                  git push
 
29. Создать файл preferences.xml       touch preferences.xml

30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
  
Вносим изменения: vim preferences.xml
нажать клавишу "i" ввести текст

<preferences>
 <favorite_movie>Star Wars</Favorite_movie>
 <favorite_series>The Big BangTheory</Favorite_series>
 <favorite_food>Lasagna</favorite_food>
 <favorite_time_of_year>Summer</favorite_time_of_year>
 <country_you_like_to_visit>China</country_you_like_to_visit>
</preferences>
Cохранить и выйти: "esc" ":wq"

 31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML 

Создать файл: touch skills.xml
Внести изменения: vim skills.xml
нажать клавишу "i" ввести текст

<skills>

 <Googling></Googling>
 <Postman></Postman>
 <Git></Git>
 <Charles></Charles>
 <Jmeter></Jmeter>
 <Android_Studio></Android_Studio>

</skills>

Cохранить и выйти: "esc" ":wq"

 32. Сделать коммит        git commit -m "add new xml"

 33. Отправить сразу 2 файла на внешний репозиторий.
                                                     git add preferences.xml  skills.xml
                                                     git commit -m "edit new xml"
                                                     git push

 34. На веб интерфейсе создать файл bug_report.xml.         - Add file
							    - Create new file
							    - Commit new file
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе. -edit this file
                                                                     в строке Commit changes написать новый Commit
                                                                     Commit changes

 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

<Summary></Summary>
<Description>
    <Steps_to_reproduce></Steps_to_reproduce>
    <Expected_Results></Expected_Results>
    <Actual_Results></Actual_Results>
    <Reproducibility></Reproducibility>
    <Environment></Environment>
</Description>

 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.    в строке Commit changes написать новый Commit
                                                                     Commit changes
 38. Синхронизировать внешний и локальный репозиторий XML   git pull
