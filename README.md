# tmdb_api  
Упражнение на чтение кода. Фильмы с TMDB. 
## own_db_helpers  
Включает в себя лишь одну функцию, которая принимает файл формата json и открывает его для чтения в терминале.  
## search_in_db  
Пользователь указывает путь до файла, который хранит в себе названия фильмов. В случае если файл отсутствует в консоли выводится, что файл не найден.
Далее пользователь указывает слово в названии фильма и программа ищет фильмы по ключевому введенному слову, если такое слово есть в названиях фильма, то в консоли выводятся названия фильмов, где есть это слово.  
## find_similar  
Пользователь указывает путь до файла,который хранит в себе названия фильмов. В случае если файл отсутствует в консоли выводится, что файл не найден.
Далее пользователь указывает название фильма, если такой фильм есть в файле, то в консоли выводятся названия 8 фильмов максимально идентичных по параметрам к указанному фильму, сортированные в алфавитном порядке.  
## tmdb_helpers  
Файл содержит в себе три взаимосвязанные функции,при запуске основной из них пользователя просят ввести api ключ для получения данных с https://www.themoviedb.org/ .    
Итогом работы двух других функций является возврат данных о фильме , таких как жанр, бюджет и описание.    
## hello_api_TMDB  
Программа просит ввести пользователя api ключ для получения данных с https://www.themoviedb.org/.
При корректном вводе, в терминале отображается бюджет фильма "Пила 2".  
## make_own_bd  
Программа просит ввести пользователя api ключ для получения данных с https://www.themoviedb.org/.
Создает json файл с данными полученными о 1000 фильмах с https://www.themoviedb.org/.



