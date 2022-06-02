# TXT
 1. Создать внешний репозиторий c названием TXT.
    
          repositories->new->create repository
          
 2. Клонировать репозиторий TXT на локальный компьютер.
		
	        $ git clone https://github.com/kaminska1313/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.
		
	        $ cd TXT
	        $ touch new.txt

 4. Добавить файл под гит.
		
	        $ git add .

 5. Закоммитить файл.
		
	        $ git commit -m "created new.txt"

 6. Отправить файл на внешний GitHub репозиторий.
		
	        $git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
		
	        $ cat >> new.txt
	        *text here*
	        ctrl+c

 8. Отправить изменения на внешний репозиторий.
		
	        $ git commit -am "edited new.txt"
	        $ git push

 9. Создать файл preferences.txt
		
	        $ touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
		
	        $ cat >> preferences.txt
	        *text here*
	        ctrl+c

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
		
	        $ touch skills.txt
	        $ cat >> skills.txt
	        *text here*
	        ctrl+c

 12. Сделать коммит в одну строку.
		
	        $ git commit -am "added 2 files"

 13. Отправить сразу 2 файла на внешний репозиторий.
		
	        $ git push

 14. На веб интерфейсе создать файл bug_report.txt.
		
	        add file->create new file

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
		
	        ->commit new file

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
		
	        bug_report.txt->edit this file
	        *text*

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
		
	        ->commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT
		
	        $ git pull
