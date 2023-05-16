 # __Бот для игры Asphalt Legends (Android) v.5.0__

### [СОДЕРЖАНИЕ](https://github.com/AUTOPILOTyoutube/bot-asphalt-legends-android/blob/main/README.md)

## ВЫБОР ВЕРСИИ ИГРЫ - ОРИГИНАЛЬНАЯ или КИТАЙСКАЯ

Бот может управлять двумя версиями игры:
- оригинальная версия
- китайская версия

Чтобы выбрать версию игры:

1. Запустите бота

    ![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/04_interface/int_full.png)

2. Войдите в настройки (кнопка "SET") и в диалоговом окне "Game Version" выберите версию игры - ORIGINAL (оригинальная), CHINA (китайская)

    ![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/04_interface/GameVersion.jpg)


## ВОЗМОЖНЫЕ НЕИСПРАВНОСТИ

В файле настроек бота BotAphalt9/AsphaltSettings.json уже указано имя оригинальной и китайской версии игры:
- "com.gameloft.android.ANMP.GloftA9HM"
- "com.gameloft.android.HUAW.GloftA9HW.HUAWEI"

Имя игры находится в следующих строчках файла AsphaltSettings.json:  
"GamePackageOriginal":"com.gameloft.android.ANMP.GloftA9HM",
"GamePackageChina":"com.gameloft.android.HUAW.GloftA9HW.HUAWEI"

Но имя игры когда-нибудь может измениться.  
Тогда при нажатии на кнопку START бот не сможет запустить игру (оригинальную или китайскую), так как он будет искать старое имя игры, указанное в файле AsphaltSettings.json.

Необходимо открыть файл AsphaltSettings.json и указать там новое имя игры (оригинальной и китайской).

Чтобы узнать текущее имя игры потребуется установить бесплатное приложение "Package Names" или "Package Name Viewer", его можно скачать с плей маркета:

[Package Names](https://play.google.com/store/apps/details?id=com.csdroid.pkg)

![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/04_interface/PackageNames00.png)

Запустите приложение и в списке установленных приложений найдите игру Асфальт:

![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/04_interface/PackageNames01.png)

После нажатия на игру появится всплывающее окно, где Вы увидите полное имя игры:

![Иллюстрация к проекту](https://github.com/autopilotyoutube/bot-asphalt-legends-android/raw/main/files/pictures/04_interface/PackageNames01.png)

Это имя игры должно совпадать с именем игры в файле AsphaltSettings.json.
Если имя не совпадает, то в файле AsphaltSettings.json необходимо написать новое имя игры. 

И теперь, при нажатии на кнопку START, бот сможет запустить игру.