# HW_2 : TXT

1. Создать внешний репозиторий c названием TXT;

2. Клонировать репозиторий TXT на локальный компьютер - `git clone URL`;

3. Внутри локального TXT создать файл “new.txt” - `touch new.txt`;

4. Добавить файл под гит - `git add .`;

5. Закоммитить файл - `git commit -m "create new file"`;

6. Отправить файл на внешний GitHub репозиторий - `git push`;

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT:

```
Info:
ФИО Богданец Алена Николаевна
Возраст 32
Количество домашних животных 1
Зарплата $1000
```

8. Отправить изменения на внешний репозиторий - `git commit -am "updated file"`;

9. Создать файл preferences.txt - `touch preferences.txt`;

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT:

```
Любимый фильм -Сплит
Любимый сериал Друзья
Любимая еда Мясо
Любимое время года Лето
```

11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT - `touch skills.txt`:

```
Skills:
        1. Базовая теория;
        2. Что такое клиент-серверная архитектура;
        3. HTTP Методы запросов на сервер;
        4. Коды ответов HTTP сервера;
        5. Структуры HTTP запросов и ответов;
        6. Что такое JSON, XML. Их структура;
        7. Тестирование API через Postman (JS, автотесты API);
        8. Снятие и чтение логов c внешнего сервера;
        9. Снифинг http web трафика через Charles и Fiddler;
        10. Dev Tools веб браузеров (Google Chrome, FireFox);
        11. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов);
        12. Мобильное тестирование;
        13. Особенность iOS, Android, гайдлайны;
        14. Сборка iOS приложений на XCode. (У кого нет Mac компьютера, просто посмотрят);
        15. Сборка Android приложений на Android Studio;
        16. ADB (управление андройд девайсами);
        17. Настройка прокси и vpn на iOS и Android;
        18. Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android;
        19. Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса);
        20. Основы bash скриптинг, автоматизация рутинных задач на сервере;
        21. Доступ к удалённым серверам;
        22. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join);
        23. База данных Postgres (установка, настройка и использование);
        24. Нереляционная база данных Redis (установка, настройка и использование);
        25. Нагрузочное тестирование в Jmeter;
        26. Методология разработки Scrum.
```

12. Сделать коммит в одну строку - `git add . && git commit -m "new 2 files"`;

13. Отправить сразу 2 файла на внешний репозиторий - `git push`;

14. На веб интерфейсе создать файл bug_report.txt;

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе;

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT:

```
Bug report:
      ID: 1
      Reporter:	Alona Bohdanets	
      Assigned to:	31_qa_group	 
      Status:	Open	
      Type: 	Bug	
      Severity:	major	
      Priority:	medium	
	    Browser:	Google Chrome 104.0.5112.81	OS:	Windows	OS version	10x64	
	    Summary:	The link of main site is disabled after clicking					
	    Pre-conditions:						
	      Site https://vos-jewelry.com opened in the browser. 					
	    Steps to reproduce:						
	    	Click the link in the form of logo "Vos-jewerly" in the top of the page					
	    Actual result:						
	      The link of main site is disabled						
	    Expected result:						
	      The user is redirected to the main site according to mockups						
```

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе;

18. Синхронизировать внешний и локальный репозиторий TXT - `git pull`.
