25.04.2023 tuesday
21:34
# Instructions for working with GIT #
Второй конфликт:
![Конфликт при мерже с веткой data](/conflict2.png "При конфликте принял изменения")
1. add "File name" - добавляет файлу версионность(обновляет после внесения изменений).
2. add . - добавляет всем файлам с которыми велась работа версионность. 
3. commit - Record changes to the repository(сохраняет изменения в репозитории + можно оставить комментарий -m"Message")
4. init - Create an empty Git repository or reinitialize an existing one(создает локальный репозиторий в нашей папке)
5. diff - Show changes between commits, commit and working tree, etc(различия между сохраненной версией и текущей)  
5. log - Show commit logs (перечень сохраненных версий)
7. log -- oneline - перечень сохраненных версий более удобно ![пример](/oneline.jpg) 
Конфликт <image src="conflict.png" alt="Конфликт">.
7. log --oneline --graph - графически показывает ветки.
7. checkout - выбор сохраненной версии.
7. chekout master - возвращение к текущему (актуальному) состоянию.
8. status  -  Show the working tree status (показывает состояние процесса в отслеживаемой папке)
9. *restore   Restore working tree files*
10. branch <название_ветки> или chekout -b <название ветки> - создает новую ветку
11. merge <название_ветки> - сливание двух версий файла в одну (при совместной работе)