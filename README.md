# Adding-scripts-to-interface
Это комплект настроек для Altium Designer в котором созданы элементы меню на некоторые полезные скрипты. 

Как получить и использовать скрипты:
Так как большинство авторов скриптов хранит их в репозиториях на GitHub, то целесообразно установить программу Github Desktop (https://desktop.github.com/) для синхронизации с репозиториями и всегда иметь самую актуальную версию скриптов.
Подробнее про работу со скриптами можно найти в видео: Как создать первый скрипт - https://youtu.be/P9qXXIj3vqg
и в документации: Scripting System Overview & Setup - https://www.altium.com/ru/documentation/altium-designer/scripting-system-overview-setup-ad.
Если скрипты будут храниться на рабочей машине в папке C:\Users\Public\Documents\Altium\ADScripts, то вы можете загрузить файл с настройками из этого репозитория, в котором использованы возможности кастомизации интерфейса (файл с настройками будет обновляться по мере появления новых скриптов). Для быстрого запуска скриптов создан Toolbar и выпадающий список со скриптами описанными в данной статье. А также назначены горячие клавиши на некоторые скрипты.  

Для загрузки настроек кастомизации:
1. Рекомендовано иметь чистую установку AltiumDesigner поскольку загружаемые настройки могут конфликтовать с имеющимися.
2. В окне Preferences нажать в левом нижнем углу кнопку Load. Выбрать файл DXPPrefScripts.DXPPrf. В окне Load preferences from file нажать кнопку Apply none. Затем нажать на Show options page list, раскрыть группу настроек System и установить флаг Apply напротив Customizations и нажать на кнопку Import.

Используя систему кастомизации можно создать пункты меню привязанные к скриптам самостоятельно. Для этого необходимо:
1. Откройте проект скрипта
2. Зайти в режим кастомизации щелкнув ПКМ по строке меню или панели инструментов и выбрав команду Customize. 
3. В диалоговом окне Customizing Editor на вкладке Commands в списке Categories выберите пункт Scripts. 
4. В списке Commands найдите стартовую процедуру для запуска скрипта (обычно это main, StartScript, Run или другая процедура с похожим названием). Затем левой кнопкой мыши перетяните стартовую процедуру скрипта в необходимый пункт меню.
5. В открывшемся окне Edit Command можно указать свое название для кнопки в поле Caption, указать ссылку на иконку в поле Bitmap File и назначить горячие клавиши в разделе Shortcuts.
Подробнее про кастомизацию можно найти в видео: Как создать первый скрипт в Altium Designer? - https://youtu.be/P9qXXIj3vqg
и в документации: Настройка и кастомизация Altium Designer - https://www.altium.com/ru/documentation/altium-designer/configuring-and-customizing-altium-designer

Перечень репозиториев которые нужно скопировать в папку C:\Users\Public\Documents\Altium\ADScripts
https://github.com/Altium-Designer-addons/scripts-libraries
https://github.com/BrettLMiller/Altium-DelphiScripts
https://github.com/igorpnk/SmartChoiceRouter
https://github.com/igorpnk/GetXYComponent
https://github.com/igorpnk/PasteMaskCalculator
https://github.com/igorpnk/NofittedNoPaste
https://github.com/igorpnk/Select_Script
