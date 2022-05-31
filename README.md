# Git_XML

## XML
21. Создать внешний репозиторий c названием XML.
>Git_XML
22. Клонировать репозиторий XML на локальный компьютер.
>git clone git@github.com:vv-vasilyev08/Git_XML.git
23. Внутри локального XML создать файл “new.xml”.
>touch new.xml
24. Добавить файл под гит.
>git add new.xml
25. Закоммитить файл.
>git commit -m "add first file"
26. Отправить файл на внешний GitHub репозиторий.
>git push
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
>cat >> new.xml
```xml
<?xml version-"1.0" endcoding="UTF-8"?>
<new>
	<name>Лучший</name>
	<surname>Пухляш</surname>
	<age>22</age>
	<pets_number>5</pets_number>
	<salary>120000</salary>
</new>
```
>CTRL+D
28. Отправить изменения на внешний репозиторий.
>git commit -am "changes xml file"
29. Создать файл preferences.xml
>touch preferences.xml
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
>cat >> preferences.xml
```xml
<?xml version-"1.0" endcoding="UTF-8"?>
<preferences>
	<favorite_movie>На основе реальных событиях </favorite_movie>
	<favorite_TV_series>Нету</favorite_TV_series>
	<favorite_food>Овощное рагу</favorite_food>
	<favorite_season>Лето</favorite_season>
	<favorite_country>Не знаю</favorite_country>
</preferences>  
```
>CTRL+D
31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
>cat >> skills.xml
```xml
<?xml version-"1.0" endcoding="UTF-8"?>
<skills>
	<QA> Linux, Bash, Git, GitHub, API, HTTP/HTTPS, Web testing, Mobile testing, Proxy, VPN, SQL, JMeter </QA>
</skills>
```
>CTRL+D
32. Сделать коммит в одну строку.
>git add . ; git commit -m "add skills and preferences"
33. Отправить сразу 2 файла на внешний репозиторий.
>git push
34. На веб интерфейсе создать файл bug_report.xml.
>Создать файл в GitHub bug_report.xml
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>Файл bug_report.xml закоммитить в GitHub
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```xml
<?xml version-"1.0" endcoding="UTF-8"?>
<bug_report>
	<ID>VKS-2525</ID>
	<Title>Кнопка регистрации не активна на странице регистрации</Title>
	<Preconditions>Открыть страницу https://xyz.com , перейти в раздел регистрации</Preconditions>
	<STR>Заполнить валидными данными поля регистрации и нажать кнопку зарегистрироваться</STR>
	<ER>Регистрация успешно выполнена и на почту пришло письмо об успешной регистрации</ER>
	<AR>Кнопка регистрации не активна полсе заполнения всех необходимых полей регистрации</AR>
	<Attachments>Screenshot-001.png , Screencast-001.mp4</Attachments>
</bug_report>
```
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
>Сделать коммит bug_report.xml в GitHub
38. Синхронизировать внешний и локальный репозиторий XML
>git fetch  
>git pull
