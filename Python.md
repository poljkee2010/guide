# Python

## Цель
Существует большое количество языков программирования и все не изучишь. 

Однако мы настоятельно рекомендуем освоить Python. Его можно изучать как в качетсве основного языка, так и в качестве вспомогательного.

**Python** - один из самых популярный скриптовый язык, который используется в очень больших спектрах задач.

Существует много причин изучить Python, вот несколько из них:
1. **Python** - это язык бизнес процессов.
Это своего рода "язык-клей", с помощью которого удобно склеивать
различные блоки системы.
1. Если нужно выбрать "вспомогательный" язык, обычно выбирают Python
1. На **Python** можно быстро спроектировать программу, он может выступать как язык *быстрой* разработки.
1. **Python** - это язык [R&D](https://ru.wikipedia.org/wiki/%D0%9D%D0%98%D0%9E%D0%9A%D0%A0).
Если нужно быстро что-то сделать, посмотреть рабочая ли гипотеза, то обычно используют Python. 
1. **Python** используют как язык анализа данных, в том числе для разработки Data Science систем.
Даже если вы не планируете быть "датасаентистом", получить элементарный навык работы с данными - не помешает совсем.

## С чего начать

Python - это как акварельные краски. 
Кажется что просто, но чтобы стать мастером потребуется время.

Как и для изучения любого языка программирования
оптимальный вариант - это столкнутся с ЗАДАЧЕЙ, для 
которой требуется Python. Список интереснейших, но сложных задач ниже.

### Книги
1. Марк Лутц. Изучаем Python. 
2. Подборка книг - https://tproger.ru/books/free-python-books/

### Видеокурсы
1. https://www.coursera.org/specializations/python#courses
2. https://stepik.org/course/67/promo
3. https://stepik.org/course/3206/promo
4. https://geekbrains.ru/courses/13

## Примеры задач

### Начальный уровень
С задачами для начального уровня можно ознакомиться в [разделе про программирование](https://github.com/drewxa/guide/blob/master/Programming.md#tasks)

### Продвинутый уровень
*  написание портала по шифрованию отправленного контента. 
Написать его можно на 
[Flask](https://palletsprojects.com/p/flask/) 
или 
[Django](https://www.djangoproject.com/),
сам алгоритм шифрования сделать на чистом Си 
(это уже защищённая работа **прошлого** НИРС-а)
и 
[прикрутить его в виде модуля Python-а](https://realpython.com/build-python-c-extension-module/).

* Написание проекта по обнаружению 
лиц, продающие наркотические вещества 
(или иные, запрещённые законом товары),
в социальной сети вКонтакте.

* Написать краулер, который в darknet-е  ищет объявления
о продаже украденных пластиковых карт.
Работает в две фазы:
  1. Сначала извлекает [выдачу из поисковика](https://duckduckgo.com/?q=%D0%9A%D1%83%D0%BF%D0%B8%D1%82%D1%8C+%D1%81%D0%B1%D0%B5%D1%80%D0%B1%D0%B0%D0%BD%D0%BA%D0%BE%D0%B2%D1%81%D0%BA%D0%B8%D0%B5+%D0%BA%D0%B0%D1%80%D1%82%D1%8B&t=h_&ia=web).
  1. Смотрит все страницы, и по [алгоритму TF-IDF](https://ru.wikipedia.org/wiki/TF-IDF) находит нужные страницы.

* Сделать анализ патентов по ИБ в стране Х за последние 5 лет. 
Использовать [Jupyter](https://jupyter.org/).

* Найти эксплойты для Meterpreter/Metasploit-а
и сделать портал, который... автоматически проверяет ваш комьютер,
пытаясь его взломать :)

* Написать парсер сообщений в каналах Telegram на 
обнаружение новостей по ИБ

* [Написать плагин для IDA](https://xakep.ru/2011/06/23/55780/#toc05.)

* С помощью [pyshark](https://kiminewt.github.io/pyshark/)
напишите правило обнаружения зловреда для [WAF-а](https://ru.wikipedia.org/wiki/%D0%A4%D0%B0%D0%B9%D1%80%D0%B2%D0%BE%D0%BB_%D0%B2%D0%B5%D0%B1-%D0%BF%D1%80%D0%B8%D0%BB%D0%BE%D0%B6%D0%B5%D0%BD%D0%B8%D0%B9)
Сам [pcap](https://ru.wikipedia.org/wiki/Pcap) файл получите с помощтю Meterpreter/Metasploit-а

Ну и для самых крутых:

* Посмотрите проект [Cuckoo](https://cuckoosandbox.org/download),
потом [исходники](https://github.com/cuckoosandbox)
и... придумайте себе задание :) Согласуйте с преподавателем -- и сделайте!

* Создание стенда по CTF.
  1. Изучите как работает [Docker](https://www.docker.com/).
  1. Выгрузите стабильную, но оооочень старую версию
Apache Server отсюда: https://github.com/apache/httpd
  1. Запишите CTF-флаг. Соберите проект и взломайте его.
  1. Соберите докер-контейнер
  1. Напишите скрипт на Python-е, который запускает список контейнеров 
  (в данном случае список из одного вашего сервера)
  1. ещё раз взломайте
  1. найдите другие open source проекты, выгрузите старые версии и напишите README.md
  1. попросите друга протестировать всё.

## Спецкурс Data Science in Information Security
На основе [КИБ](https://t.me/kibinfo) проходит спецкурс **Data Science in Information Security**. Чтобы попасть на этот курс, необходимы базовые знания **Python**. С материалами курса можно ознакомиться [по ссылке](https://github.com/kib-courses/dsis).
