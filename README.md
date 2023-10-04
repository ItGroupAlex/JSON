# JSON

 1. Создать внешний репозиторий c названием JSON.  
 
 2. Клонировать репозиторий JSON на локальный компьютер:  
 	Заходим в нужную папку где будет создаваться локальная копия репозитория и запускаем оттуда Git Bush  
	`$ git clone git@github.com:ItGroupAlex/JSON.git`  
	`$ yes`  
	(Локальная копия создана)  
 3. Внутри локального JSON создать файл “new.json”.  
	`$ cd JSON`  
	`$ touch new.json`  
 4. Добавить файл под гит.  
	`$ git status`  
	`$ git add .`  
 5. Закоммитить файл.  
	`$ git commit -m "Added file json"`  
 6. Отправить файл на внешний GitHub репозиторий.  
	`$ git push origin`  
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
	`$ vim new.json`  
	`*i`

``` js
	 {"name": "Alex",  
	"age": 38,   
	"pets": 0,   
	"salary": 2000   
	}
 
	:x
```     
  
 8. Отправить изменения на внешний репозиторий.  
	`:x`  
	`$ git status`  
	`$ git add .`  
	`$ git commit -m "Redacted file json"`  
	`$ git push origin`  
 9. Создать файл preferences.json  
	`$ touch preferences.json`  
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
	`$ vim preferences.json`  
	`*i`  
	`{`  
	`"film": "Человек у окна",`  
        `"series": "Твин пикс",`  
        `"food": "Суши",`  
        `"season": "Summer",`  
        `"country": "USA"`  
	`}`  
	`:x `  
 11. Создать файл skils.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON  
	`$ touch skils.json`  
	`$ vim skils.json`  
	`*.i`  
	`{ "Skils 1": "QA",`  
	`"Skils 2": "Python",`  
	`"Skils 3": "English"`  
	`}`  
	`:x`  
 12. Отправить сразу 2 файла на внешний репозиторий.  
	`$ git status`  
	`$ git add .`  
	`$ git commit -m "Added 2 files json"`  
	`$ git push origin`  
 13. На веб интерфейсе создать файл bug_report.json.  
	* в веб интерфейсе создаем файл bug_report.json  
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
	* вводим коммент и сохраняем  
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
	`{`  
	`"id": 1,`  
 	`"Title": "The buttom <Login> must redirect to login form",`  
 	`"ER": "buttom <Login> must redirect to login form",`  
 	`"AR": "error",`  
	`"Severity": "Critical",`  
 	`"Priority": "High"`  
	`}`    
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
	*Save  
 17. Синхронизировать внешний и локальный репозиторий JSON  
	`$ git pull`  
