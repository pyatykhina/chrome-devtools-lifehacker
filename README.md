# chrome-devtools-lifehacker
### Анализ открытия сайта lifehacker.ru


## Вкладка Network
[Профиль загрузки ресурсов при открытии страницы](lifehacker.ru.har)

1.	дублирование ресурсов
* sodar?sv=200&tid=gda&tv=r20210601&st=env
![sodar?sv=200&tid=gda&tv=r20210601&st=env](/screenshots/duplicate/sodar?sv=200&tid=gda&tv=r20210601&st=env.jpeg)
* show_ads_impl_fy2019.js
![show_ads_impl_fy2019.js](/screenshots/duplicate/show_ads_impl_fy2019.jpeg)
* osd.js
![osd.js](/screenshots/duplicate/osd.jpeg)
* integrator.js?domain=lifehacker.ru
![integrator.js?domain=lifehacker.ru](/screenshots/duplicate/integrator.js?domain=lifehacker.ru.jpeg)
* cookie.js?domain=lifehacker.ru
![cookie.js?domain=lifehacker.ru](/screenshots/duplicate/cookie.js?domain=lifehacker.ru.jpeg)
* adsbygoogle.js
![adsbygoogle.js](/screenshots/duplicate/adsbygoogle.jpeg)
* adfox-adx-stub.js
![adfox-adx-stub.js](/screenshots/duplicate/adfox-adx-stub.jpeg)
* zrt_lookup.html
![zrt_lookup.html](/screenshots/duplicate/zrt_lookup.jpeg)
* adfox-adx-stub.html
![adfox-adx-stub.html](/screenshots/duplicate/adfox-adx-stub-html.jpeg)

2.	лишний размер ресурса
* favicon-32x32
![favicon-32x32](/screenshots/excess/favicon-32x32.jpeg)
* adjson?t=adfox
![adjson?t=adfox](/screenshots/excess/adjson?t=adfox.jpeg)
* bid
![bid](/screenshots/excess/bid.jpeg)
* hbid_yandex
![hbid_yandex](/screenshots/excess/hbid_yandex.jpeg)
* adfox-adx-stub.html
![adfox-adx-stub.html](/screenshots/excess/adfox-adx-stub.html.jpeg)
* pixel.gif
![pixel.gif](/screenshots/excess/pixel.jpeg)
* event
![event](/screenshots/excess/event.jpeg)
* integrator.js?domain=lifehacker.ru
![integrator.js?domain=lifehacker.ru](/screenshots/excess/integrator.js?domain=lifehacker.ru.jpeg)
* cookie.js?domain=lifehacker.ru
![cookie.js?domain=lifehacker.ru](/screenshots/excess/cookie.js?domain=lifehacker.ru.jpeg)
* event
![event](/screenshots/excess/event2.jpeg)

3.	медленно загружающиеся ресурсы
* ab5bba4
![ab5bba4](/screenshots/slow/ab5bba4.jpeg)
* context
![context](/screenshots/slow/context.jpeg)
* gtm.js?id=GTM-5BWRBVT
![gtm.js?id=GTM-5BWRBVT](/screenshots/slow/gtm.js?id=GTM-5BWRBVT.jpeg)
* adsbygoogle
![adsbygoogle](/screenshots/slow/adsbygoogle.jpeg)
* tag
![tag](/screenshots/slow/tag.jpeg)

4.	ресурсы, блокирующие загрузку
![block](/screenshots/block/block.jpeg)



## Вкладка Performance
[Профиль загрузки страницы](Profile-20210606T111658.json)

1. время в миллисекундах от начала навигации до событий
* First Paint - 4723.9 ms
* First Meaningful Paint - ?
* DOM Content Loaded - 4383.6 ms
* Load - 9011.4 ms

2. сколько времени в миллисекундах тратится на разные этапы обработки документа
* Loading - 164 ms
* Scripting - 8498 ms
* Rendering - 651 ms
* Painting - 175 ms



## Вкладка Coverage
![coverage](/coverage.jpeg)

1. объём неиспользованного CSS в ходе загрузки страницы - 84,5кБ
![css](/screenshots/unused/css.jpeg)

2. объём неиспользованного JS в ходе загрузки страницы - 2415,5кБ
![js](/screenshots/unused/js.jpeg)
