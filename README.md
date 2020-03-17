# ZaurNatok.github.io
Форма отправки данных с валидацией полей.   
https://zaurnatok.github.io/form/
*Версия 1.5* Исправлены pattern проверки полей: Имя, Email и Телефон

:white_check_mark: **Валидация поля "Имя".** 1. только кириллица 2. первая буква заглавная 3. можно ввести от 2 до 20 символов 4. возможна запись двойных имён — например Анна-Мария.    
:white_check_mark: **Валидация поля "Email".** 1. только латиница 2. «собака» @ — обязательный символ 3. Точка . — тоже обязательный символ 4. Цифры, подчерк, тире — разрешённые символы    
:white_check_mark: **Валидация поля "Номер телефона".** Шаблон для телефона должен находить номера в таких форматах: +7(925)900-90-90, +7(925) 900-90-90, +7 925-900-90-90, +79259009090, 89259009090    
:white_check_mark: **Валидация поля "Веб сайт".** 1. Адрес сайта может начинаться с http:// или https:// 2. затем www. — это необязательная группа 3. IP-адрес — 255.255.255.255 или доменное имя — mysite.ru 4. порт — тоже необязательная группа. Порт начинается с двоеточия, за которым идут от 2 до 5 цифр. Например: :8080 5. путь — последовательность из цифр, слешей и латинских букв, на конце которого может стоять решётка #.     
