## HW_GitHub_1.1

1. Создать внешний репозиторий c названием XML. – done
2. Клонировать репозиторий XML на локальный компьютер. –
git clone https://github.com/AnatolyTyurin/Ksendzov_XML.git
3. Внутри локального XML создать файл “new.xml”. - touch new.xml
4. Добавить файл под гит. - git add new.xml
5. Закоммитить файл. - git commit -am "adding new xml"
6. Отправить файл на внешний GitHub репозиторий. – git push
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
<?xml version="1.0" encoding="UTF-8"?>
        <first_name>Anatoly</first_name>
        <last_namr>Tyurin</last_name>
        <age>35</age>
        <pets>no pets</pets>
        <desired_salary>USD 1000</desired_salary>
8. Отправить изменения на внешний репозиторий. – 
git commit -am "add text to new.xml" && git push
9. Создать файл preferences.xml - touch preferences.xml
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
<?xml version="1.0" encoding="UTF-8"?>
    <favourite_film>Existenz</favourite_film>
    <favourite_TV_series>The Sopranos</favourite_TV_series>
    <favourte_food>mama's homemade food</favourite_food>
    <favourite_season>summer</favourite_season>
    <desired_country_to_visit>State of Maine, the USA</desired_country_to_visit>

11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
<?xml version="1.0" encoding="UTF-8"?>
<skills>

        <basic_testing_theory>QA,QC,testing</basic_testing_theory>
        <basic_testing_theory>bug reports</basic_testing_theory>
        <basic_testing_theory>testing documentation</basic_testing_theory>
        <basic_testing_theory>types and methods of testing</basic_testing_theory>
        <basic_testing_theory>SDLC</basic_testing_theory>
        <basic_testing_theory>STLC</basic_testing_theory>
        <HTTP>client-server architecture</HTTP>
        <HTTP>HTTP methods of requests</HTTP>
        <HTTP>HTTP server response codes</HTTP>
        <HTTP>Structures of HTTP requests and responses</HTTP>
        <data_interchange_format>JSON</data_interchange_format>
        <data_interchange_format>XML</data_interchange_format>
        <API>Postman</API>
        <API>JS</API>
        <API>API autotests</API>
        <sniffing>Charles</sniffing>
        <sniffing>Fiddler</sniffing>
        <DevTools>Google Chrome</DevTools>
        <DevTools>FireFox</DevTools>
        <VPN>General info</VPN>
        <Mobile_testing>IOS</Mobile_testing>
        <Mobile_testing>Android</Mobile_testing>
        <Mobile_testing>XCode</Mobile_testing>
        <Mobile_testing>Android Studio</Mobile_testing>
        <Mobile_testing>ADB</Mobile_testing>
        <Mobile_testing>Proxy and vpn settings on iOS and Android</Mobile_testing>
        <Mobile_testing>Sniffing traffic using Charles and Fiddler on IOS and Android</Mobile_testing>
        <Linux_Terminal>Copying, creating, viewing, moving files and etc.</Linux Terminal>
        <Linux_Terminal>Base of Bash scripting</Linux Terminal>
        <Linux_Terminal>Access to remote servers</Linux Terminal>
        <SQL>Create, Delete, Drop, Insert Into, Select, From, Where, Join</SQL>
        <SQL>PostgreSQL</SQL>
        <SQL>Redis</SQL>
        <Load_testing>Jmeter</Load_testing>
        <Development_methodology>SCRUM</Development_methodology>
        <Programming_language>Base of Python</Programming language>
12. Сделать коммит в одну строку. -
git add . && git commit -am "add preferences.xml and skills.xml"
13. Отправить сразу 2 файла на внешний репозиторий. – git push
14. На веб интерфейсе создать файл bug_report.xml. - done
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - done
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
<?xml version="1.0" encoding="UTF-8" ?>
	<bug_report>
	<Bug-ID>1</Bug-ID>
	<Title>There is no onboarding during first launch of the application</Title>
	<STR>1. Download the application</STR>
	<STR>2. Open the application</STR>
	<AR>Lessons main screen is displayed</AR>
	<ER>Onboarding screen is displayed</ER>
	<Environment>Xiaomi Mi9, Android 10</Environment>
	<Severity>Minor</Severity>
	<Priority>N/a</Priority>
	<Author>Anatoly Tyurin</Author>
	</bug_report>
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - done
18. Синхронизировать внешний и локальный репозиторий XML – git pull
