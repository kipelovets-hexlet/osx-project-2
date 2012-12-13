VKPlayer
========

Плеер музыки из ВКонтакте для iOS.


Проблема, которую решает приложение
-----------------------------------

Приложение позволяет меломанам прослушивать музыку из сети ВКонтакте на устройстве iPhone или iPod Touch, подключенному к WiFi.

Аудитория приложения
--------------------

Меломаны, состоящие в сети ВКонтакте и обладающие iPhone или iPho Touch.

Пример сценария использования приложения
----------------------------------------

Меломан включает приложение VKPlayer на своем устройстве и (после аутентификации) видит список своих аудиозаписей. Он может выбрать одну из аудиозаписей и начать ее прослушивать, или перейти к поиску и прослушать одну из найденных по ключевым словам аудиозаписей.

Описание поведения
------------------

При первой загрузке приложения отображается диалоговое окно аутентификации ВКонтакте. После успешной авторизации, отображается главный экран со списком аудиозаписей меломана и вкладками, которые позволяют перейти к списку плейлистов и к поиску. При тапе на аудиозапись, отображается экран прослушивания, начинается загрузка аудиозаписи, затем ее проигрывание. 
На экране прослушивания есть кнопка для возврата на предыдущий экран, кнопки "Пауза", "Вперед" и "Назад".
В верхней части главного экрана есть кнопка "Исполняется", открывающая экран прослушивания. В нижней части главного экрана — вкладки "Мои аудиозаписи", "Мои плейлисты" и "Поиск". В "Моих плейлистах" отображается список плейлистов меломана, при тапе на которые открывается список аудиозаписей, входящих в выбранный плейлист. В "Поиске" сначала отображается только строка поиска; после ввода поискового запроса и нажатия клавиши "Ввод" виртуальной клавиатуры — список аудиозаписей. 
При тапе на аудиозапись на любом экране, открывается экран прослушивания, и начинается ее загрузка и проигрывание. При нажатии на кнопки "Вперед" и "Назад" на экране прослушивания, начинается загрузка и проигрывание предыдущей или следующей аудиозаписи в том списке, в котором была выбрана аудиозапись для прослушивания.