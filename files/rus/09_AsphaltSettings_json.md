# __Бот для игры Asphalt Legends (Android) v.5.0__

### [СОДЕРЖАНИЕ](https://github.com/AUTOPILOTyoutube/bot-asphalt-legends-android/blob/main/README.md)  

 ## 😊 AsphaltSettings.json

 [ВИДЕОУРОК: AsphaltSettings.json](https://youtu.be/ooLLJdu3mHs)

Файл AsphaltSettings.json находится в папке BotAphalt9  
Этот файл необходим для настройки некоторых параметров бота.

Редактировать файл можно в любом текстовом редакторе, но я рекомендую установить редактор QuickEdit.

## 😊 Способы установки редактора текстовых файлов QuickEdit

1. Редактор текстовых файлов QuickEdit можно установить через GooglePlay:  
https://play.google.com/store/apps/details?id=com.rhmsoft.edit

2. Полную версию QuickEdit можно найти и установить с момощью сайта 4pda (необходимо зарегистрироваться на данном сайте):  
https://4pda.to/forum/index.php?showtopic=625901  


## 😊 Отображение координат касаний по экрану  
Перед изменением содержимого файла AsphaltSettings.json нам потребуется включить отображение координат касаний по экрану. Это делается в параметрах разработчика:

![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/01_show_cordinats.png)  

[ВИДЕОУРОК: отображение координат касаний по экрану](https://youtu.be/7DOHhMlvm54)



## 😊 Содержимое файла AsphaltSettings.json  

```json
{  
    "NitroXY": [1350,550],  
    "BrakeXY": [250,550],  
    "RunGameLeftSwipe": [600,350,350,350],  
    "RunGameRightSwipe": [950,350,1150,350],  
    "CarSelectWorldSeriesSwipe": [1350,350,350,350,7],  
    "DailyEventsCarHuntSelectSwipe": [1300,600,300,600],  
    "SpecialEventsCarHuntSelectVerticalSwipe": [370,530,370,320],  
    "GamePackageOriginal":"com.gameloft.android.ANMP.GloftA9HM",  
    "GamePackageChina":"com.gameloft.android.HUAW.GloftA9HW.HUAWEI"  
}
```
Начало отсчёта координат - левый верхний угол (Х=0, У=0)  
![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/02.png)  

NitroXY - x,y координаты значка нитро  
BrakeXY – x,y координаты значка тормоз  
![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/03.png)  

RunGameLeftSwipe – x1,y1,x2,y2 координаты левого горизонтального свайпа (выбирает повороты, трамплины...)  
![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/04.png)  

RunGameRightSwipe – x1,y1,x2,y2 координаты правого горизонтального свайпа  
![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/05.png)  

CarSelectWorldSeriesSwipe[x1,y1,x2,y2,COUNT] – x1,y1,x2,y2 координаты левого горизонтального свайпа (выбор машин в сетевой игре "Мировая Серия")  
COUNT - количество свайпов, которые делает бот при поиске машины (по умолчанию 7)


![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/06.png)  

DailyEventsCarHuntSelectSwipe – x1,y1,x2,y2 координаты левого горизонтального свайпа (выбор события "Охота за тачкой" в ежедневных событиях)  
![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/07.png)  

SpecialEventsCarHuntSelectVerticalSwipe – x1,y1,x2,y2 координаты вертикального свайпа (выбор события "Охота за тачкой" в сезонных событиях)  
![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/09_AsphaltSettings/08.png)  

GamePackageOriginal - название оригинальной версии игры  
GamePackageChina - название китайской версии игры  

[Как узнать название игры](https://github.com/AUTOPILOTyoutube/bot-asphalt-legends-android/blob/main/files/rus/06_version.md)  