# Volgait
Задание
1 залание
Выделены заглавные буквы, которые образуют некое послание. Попробуем их собрать:
uS
Our
General
BOth
First
foR
looK
wEb
stEal
Perform
This
backgRound
You
Include
In additioN
Describing
Получается ответ : US Our General BO First for looK Web steal Perform This background You Include In addition describing
2 задание:
Откроем файл в текстовике
 
PK   	 c ®{$Y+І};D   )    
 flag.txt™  AE 0@ћ4
•ў°T‘Q‡еЬёS 
D¶ЊWдпЦО { 
ѓБјЙд“Л‰°MхRЪ.ВОBЗ‘C|Uѕмц_ШЋ@г’
jД 4PK+І};D   )   PK¬  	 c ®{$Y+І};D   )   /               flag.txt
         eя ґЅюЪАиMѕюЪ‹aЅюЪ™  AE PK      e   …   @ aHR0cHM6Ly9naXRodWIuY29tLzRpcG9rL3ZvbGdhX2l0XzIwMjQtaWItLmdpdA==
похоже на base64-кодирование. Декодировав это, ты получишь URL: https://github.com/4ipok/volga_it_2024-ib.git .
Ответ:
 
3 задание
Знаете как заинтересовать человека? BkFlSbAmUbuCdTsAmMcMdMdAmMtMdEu
Выполнение:
Bk - Берклий
Fl - Флеровий
Sb - Сурьма
Am - Америций
Cd - Кадмий
Ts - Теннессин
Mc - Московий
Md - Менделевий
Mt - Мейтнерий
Eu – Европий
4 задание
 
Ответ:
Это изображение показывает вид на Ниагарский водопад с высоты. Он находится на границе между Канадой и США, в частности между провинцией Онтарио и штатом Нью-Йорк. Видна набережная с людьми, гуляющими вдоль водопада, а также здания и дорога с автомобилями и автобусом. Водопад создает множество брызг и пены.
5 задание:
При анализе захваченного сетевого трафика между IP-адресами 193.23.143.43 и 10.0.0.2 на порту 1433, было обнаружено несколько пакетов, содержащих необычные данные, которые не соответствуют классическим SQL-инъекциям. Учитывая, что порт 1433 используется Microsoft SQL Server для общения, это может означать попытку установления или манипуляции сеансом базы данных.
Пакет от 193.23.143.43 к 10.0.0.2:
12 01 00 2f 00 00 01 00 00 00 1a 00 06 01 00 20
00 01 02 00 21 00 01 03 00 22 00 04 04 00 26 00
01 ff 09 00 00 00 00 00 00 00 00 00 00 48 00
Ответный пакет от 10.0.0.2 к 193.23.143.43:
04 01 00 25 00 00 01 00 00 00 15 00 06 01 00 1b
00 01 02 00 1c 00 01 03 00 1d 00 00 ff 08 00 07
f7 00 00 02 00
Пакеты включают в себя строки, указывающие на попытки изменения контекста базы данных и языковых настроек:
... Changed database context to 'tempdb' ...
... Changed language setting to us_english ...
