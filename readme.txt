LiCharts: объединение статистики LI

Скрипт LiCharts объединяет статистику ваших сайтов из LiveInternet, строя график по суммарным данным посещаемости, а так же предоставляя удобный мониторинг текущей активности всех сайтов на одной странице.

Возможности скрипта:

    Суммарная посещаемость добавленных сайтов
    Графики по дневным/недельным/месячным отчетам
    Работа с запароленной статистикой
    Показ сегодняшних данных с изменением
    Закрытие доступа паролем (раскомментируйте в начале скрипта 6 строчку)
    Группы сайтов
    Открытый исходный код, не требуется база данных 

Изменения в версии 1.3 (18 апреля 2017):
	Добавлен раздел "Устройства" для доли мобильных пользователей
	Добавлен раздел "Mail/Bing" для этих поисковых систем
	Мобильный вид теперь стал лучше - график автоматически подстраивается под ширину экрана, при ограниченной ширине скрываются кнопки управления и вторая колонка данных в таблице
	Под графиком отображается дата обновления данных (загрузки страницы)
	Ссылки на статистику LI изменены на HTTPS
	Исправлен баг нового года (повторно)

Изменения в версии 1.2 (28 июня 2015):
	Фикс бага с CURLOPT_FOLLOWLOCATION при неустановленном open_basedir
	Фикс бага обработки данных новых сайтов без статистики 
	"Итого" дублируется сверху для групп с более чем 5 сайтов
	Простой экспорт текущего списка сайтов в txt
	Небольшие косметические изменения (выравнивание фавиконок, число сайтов)
	Спонсорская ссылка в скрипте
	В группировке сайтов появилась кнопка выбора всех сайтов
	Хинт - то ссылка на сайт находится в месте фавиконки, слева от домена сайта.
	Хинт #2 - можно создать новую группу и добавить сайты сразу туда


Изменения в версии 1.1 (7 июня 2015): 

	Кеширование данных графиков удалено из-за багов (кеширование устаревших данных)
	Зато данные с LI теперь парсятся многопоточно - в <strong>5 раз</strong> быстрее
	Добавлено число сайтов в группах
	>При бане IP выводится сообщение об ошибке 
	Добавлена фавиконка


Изменения в версии 1.0 (29 апреля 2015):

    Группировка сайтов по категориям
    Кеширование данных для графиков
    Смена пароля для скрипта через GUI
    Исправлен баг с number_format
    Исправлен баг "прыгающего" графика
    Весь скрипт переписан с нуля 

Особенности установки:
	Выставите права 777 на папку /data/