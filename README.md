# JSON


Подключаемся к GitHub используя SSH:   

a.) генерируем SSH-key: заходим в Git Bush и вводим:   
							  `$ ssh-keygen`  
						  	  * при желании назначаем пароль;   
						  	  * открываем созданный публичный ключ *.pub и копируем содержимое текста.  
б.) вставляем в настройках Git Hub - SSH  
в.) подгружаем данные login & e-mail:  
		  `$ git config --global user.name "ItGroupAlex"`  
		  `$ git config --global user.email "ItGroupAlex@gmail.com"`  
_________________________________________________________________________________  


JSON  
 
 4. Создать внешний репозиторий c названием JSON.  
 
 5. Клонировать репозиторий JSON на локальный компьютер:  
 	Заходим в нужную папку где будет создаваться локальная копия репозитория и запускаем оттуда Git Bush  
	`$ git clone git@github.com:ItGroupAlex/JSON.git`  
	`$ yes`  
	(Локальная копия создана)  
 6. Внутри локального JSON создать файл “new.json”.  
	`$ cd JSON`  
	`$ touch new.json`  
 7. Добавить файл под гит.  
	`$ git status`  
	`$ git add .`  
 8. Закоммитить файл.  
	`$ git commit -m "Added file json"`  
 9. Отправить файл на внешний GitHub репозиторий.  
	`$ git push origin`  
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
	`$ vim new.json`  
	`*i`  
	`{ "name": "Alex",`   
	`"age": 38,`   
	`"pets": 0,`   
	`"salary": 2000`   
	`}`  
	`:x `  
 11. Отправить изменения на внешний репозиторий.  
	`$ git status`  
	`$ git add .`  
	`$ git commit -m "Redacted file json"`  
	`$ git push origin`  
 12. Создать файл preferences.json  
	`$ touch preferences.json`  
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
	`$ vim preferences.json`  
	`*i`  
	`{ "film": "Человек у окна",`  
        `"series": "Твин пикс",`  
        `"food": "Суши",`  
        `"season": "Summer",`  
        `"country": "USA"`  
	`}`  
	`:x `  
 14. Создать файл skils.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
	`$ touch skils.json`  
	`$ vim skils.json`  
	`*.i`  
	`{ "Skils 1": "QA",`  
	`"Skils 2": "Python",`  
	`"Skils 3": "English"`  
	`}`  
	`:x`  
 15. Отправить сразу 2 файла на внешний репозиторий.  
	`$ git status`  
	`$ git add .`  
	`$ git commit -m "Added 2 files json"`  
	`$ git push origin`  
 16. На веб интерфейсе создать файл bug_report.json.  
	* в веб интерфейсе создаем файл bug_report.json  
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
	* вводим коммент и сохраняем  
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
	`{ "id": 1,`  
 	`"Title": "The buttom <Login> must redirect to login form",`  
 	`"ER": "buttom <Login> must redirect to login form",`  
 	`"AR": "error",`  
	`"Severity": "Critical",`  
 	`"Priority": "High"`  
	`}`    
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
	*Save  
 20. Синхронизировать внешний и локальный репозиторий JSON  
	`$ git clone git@github.com:ItGroupAlex/JSON.git`  
