# - Основы сетевой безопасности

№1. Ритейл

1.) Для разграничения доступа из интернета к публикуемому сервису советую использовать межсетевой экран с использованием next generation firewall, так как в ней присутствует система предотвращения вторжений и включает все функции stateful firewall.

2.) Для определения и подавления DDoS атаки на интернет магазин рекомендую использовать СЗИ которые будут защищать интернет магазин от 2х типов атак: Волюметрических (использование Scrubbing center, строит профиль трафика и с увеличением сессии на странные (большие) кол-ва пользователей воспринимает как DDOS атака и может пропускать через себя трафик и очищать его)  и атаки уровня приложений (IPS, сфокусированный от DDOS атак, видит или позволяет определять пользователю что сетевой пакет является вредоносным и задействовать с внешним сенсором для блокирования).

3.) Для определения и блокирования сложных WEB атак на ваш интернет-магазин, когда злоумышленники используют SQL инъекцию для получения доступа к базе клиентов советую использовать средства защиты для входящего трафика применять Web application firewall (учитывает логику веб приложений, предотвращает атаки SQL- инъекциями). Определяет и блокирует уязвимости веб-приложений.

№2. Промышленность

1.) Для разграничения доступа из Интернета в DMZ советую использовать межсетевой экран с использованием next generation firewall, так как в ней присутствует система предотвращения вторжений и включает все функции stateful firewall.

2.) 

3.)  Для определения и блокирования вредоносного ПО рекомендую использовать антивирусную защиту (использовать подход: поиск аномалий). Каждый файл здесь может быть вредоносным и его нужно проверить (на виртуальной машине запускается файл и смотрит что он делает). Если будет обнаружена подозрительная активность, она может быть заблокирована.
Можно установить на МЭ.

4.)
