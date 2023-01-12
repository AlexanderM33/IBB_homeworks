Домашнее задание к занятию «Основы сетевой безопасности»

Ритейл

Вы являетесь экспертом ИБ в крупной ритейл компании. Компания в условиях пандемии COVID-19 переводит продажи в онлайн (интернет) и запускает Интернет-Сайт.

![1-1](https://github.com/netology-code/ibnet-homeworks/blob/v2/08_basics/pic/retail.png)

Какие средства защиты информации вы порекомендуете:

#1 - для разграничения доступа из Интернета к публикуемому сервису я бы использовал правильно настроенный firewall (межсетевой экран) и выделил специальную демилитаризованную зону DMZ, которая позволяет улучшить безопасность сервисов, публикуемых в интернете.

#2 - для определения и подавления DDoS атаки на ваш интернет магазин  - для определения DDOS атаки будет использоваться ISP - система предотаращения вторжения, а для подавления второй межсетевой экран и балансировщик сетевой нагрузки

#3 - для определения и блокирования сложных WEB атак на ваш интернет-магазин, когда злоумышленники используют SQL инъекцию для получения доступа к вашей базе клиентов - в этом квадрате я бы использовал Web Application Firewall (WAF), так как он обеспечивает комплексную защиту от атак на веб-приложения, учитывает логику работы веб-приложений (сессии, cookies и т. д.), защищает веб-приложения лучше межсетевых экранов и систем обнаружения вторжений предоставляет защиту от веб-атак: SQL-инъекций, межсайтового скриптинга, небезопасных конфигураций и т. д., а также определяет и блокирует уязвимости веб-приложений



Промышленность

Вы являетесь экспертом ИБ в крупной промышленной компании. В компании появились новые инвестиции и руководство компании планирует модернизировать систему электронной почты и сделать более безопасным доступ сотрудников в Интернет.

![2-2](https://github.com/netology-code/ibnet-homeworks/blob/v2/08_basics/pic/industry.png)

Какие средства защиты информации вы порекомендуете:

#1 для разграничения доступа из Интернета в DMZ - межсетевой экран

#2 для защиты электронной почты от вирусов и спама - веб фильтр и антиспам шлюз для защиты от спама, а также антивирус с "песочницей" для защиты от вирусов и ограничения среды установки случайно полученных исполняемых файлов

#3 - для определения и блокирования вредоносного ПО - понадобится антивирус с "песочницей" для проверки потенциальных вредоносов на известные вирусные сигнатуры и виртуализации среды неизвестного ПО для анализа его поведения с целью определения его потенциальной вредоносности

#4 для контроля WEB трафика, URL фильтрации - web-прокси 

#5 для разграничения доступа между корпоративной сетью и DMZ - внутренний межсетевой экран (другого изготовителя, чем был в п1), (плюс при необходимости VPN-шлюз)

#6 для защиты от вредоносного ПО на рабочей станции - антивирус с песочницей



