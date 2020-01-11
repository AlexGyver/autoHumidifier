[![AlexGyver YouTube](http://alexgyver.ru/git_banner.jpg)](https://www.youtube.com/channel/UCgtAOyEQdAyjvm9ATCi_Aig?sub_confirmation=1)
# Автоматический увлажнитель воздуха
* [Описание проекта](#chapter-0)
* [Папки проекта](#chapter-1)
* [Схемы подключения](#chapter-2)
* [Материалы и компоненты](#chapter-3)
* [Настройка и использование](#chapter-4)
* [FAQ](#chapter-5)
* [Полезная информация](#chapter-6)

<a id="chapter-0"></a>
## Описание проекта
Увлажнитель с датчиком влажности
- Подробности в видео: https://youtu.be/EWCFQCREO4s

<a id="chapter-1"></a>
## Папки
- **DHT-sensor-library** - библиотека датчика, скопировать в  
`C:\Program Files (x86)\Arduino\libraries\` (Windows x64)  
`C:\Program Files\Arduino\libraries\` (Windows x86)
- **autoHumidifier** - прошивка для Arduino, файлы в папках открыть в Arduino IDE (читай [FAQ](#chapter-5))
- **XODhumidifier** - прошивка для Arduino, версия для [XOD](https://goo.gl/teWUBm) из видео

<a id="chapter-2"></a>
## Схема с DHT11
![СХЕМА](https://github.com/AlexGyver/autoHumidifier/blob/master/scheme1.jpg)

## Схема с DHT22
![СХЕМА](https://github.com/AlexGyver/autoHumidifier/blob/master/scheme2.jpg)

<a id="chapter-3"></a>
## Материалы и компоненты
* Испаритель https://ali.ski/2t1_nL
https://ali.ski/i9pkG
* Блок питания 24В https://ali.ski/LqN10
https://ali.ski/6YLoX
* Испаритель + БП https://ali.ski/UP5zWB
https://ali.ski/6blkB
* Arduino NANO https://ali.ski/tmUgl
* Датчик DHT11 https://ali.ski/oTfbx
* Датчик DHT22 https://ali.ski/mddtW
* MOSFET модуль https://ali.ski/pONHyR
* Понижайка https://ali.ski/Q9nGq
* Вентилятор https://ali.ski/gRJP95
* Потенциометры https://ali.ski/RXeuJv
* Светодиоды https://ali.ski/hX32z
* Резисторы https://ali.ski/aasgp

## Вам скорее всего пригодится
* [Всё для пайки (паяльники и примочки)](http://alexgyver.ru/all-for-soldering/)
* [Недорогие инструменты](http://alexgyver.ru/my_instruments/)
* [Все существующие модули и сенсоры Arduino](http://alexgyver.ru/arduino_shop/)
* [Электронные компоненты](http://alexgyver.ru/electronics/)
* [Аккумуляторы и зарядные модули](http://alexgyver.ru/18650/)

<a id="chapter-4"></a>
## Настройка и использование
* [Загрузка прошивки](http://alexgyver.ru/arduino-first/) - ультра подробная статья по началу работы с Ардуино
* Установить библиотеки в
`C:\Program Files (x86)\Arduino\libraries\` (Windows x64)  
`C:\Program Files\Arduino\libraries\` (Windows x86)
* Подключить Ардуино к компьютеру
* Запустить файл прошивки
* Настроить (COM порт, модель Arduino NANO 328)
* Нажать загрузить
* Пользоваться

## Настройки в коде
    DHTTYPE DHT11  // используемый датчик, DHT11 или DHT22


<a id="chapter-5"></a>
## FAQ
### Основные вопросы
В: Как скачать с этого грёбаного сайта?  
О: На главной странице проекта (где ты читаешь этот текст) вверху справа зелёная кнопка **Clone or download**, вот её жми, там будет **Download ZIP**

В: Скачался какой то файл .zip, куда его теперь?  
О: Это архив. Можно открыть стандартными средствами Windows, но думаю у всех на компьютере установлен WinRAR, архив нужно правой кнопкой и извлечь.

В: Я совсем новичок! Что мне делать с Ардуиной, где взять все программы?  
О: Читай и смотри видос http://alexgyver.ru/arduino-first/

В: Компьютер никак не реагирует на подключение Ардуины!  
О: Возможно у тебя зарядный USB кабель, а нужен именно data-кабель, по которому можно данные передавать

В: Ошибка! Скетч не компилируется!  
О: Путь к скетчу не должен содержать кириллицу. Положи его в корень диска.

В: Сколько стоит?  
О: Ничего не продаю.

### Вопросы по этому проекту

<a id="chapter-6"></a>
## Полезная информация
* [Мои видеоуроки по пайке](https://www.youtube.com/playlist?list=PLOT_HeyBraBuMIwfSYu7kCKXxQGsUKcqR)
* [Мои видеоуроки по Arduino](http://alexgyver.ru/arduino_lessons/)
* [Мой сайт](http://alexgyver.ru/)
* [Основной YouTube канал](https://www.youtube.com/channel/UCgtAOyEQdAyjvm9ATCi_Aig?sub_confirmation=1)
* [YouTube канал про Arduino](https://www.youtube.com/channel/UC4axiS76D784-ofoTdo5zOA?sub_confirmation=1)