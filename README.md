# Task3

#### Необходимое ПО
* Android Studio

#### Используемые технологии
* Java
* Java JDK

#### Инструкция по запуску приложения
1. Git clone ````https://github.com/PROCuuuba/Task3````
2. Далее необходимо запустить проект внутри Android Studio:
* Нужно нажать ````File```` в левой верхней части Android Studio, затем нажать ````Open```` и перейти по директории где находится проект, после чего выбрать проект и нажать ````Ok````.
3. После того как проект прогрузится, нужно будет подключить ваше мобильное устройство (перед этия включить отладку по USB в настройках устройства) или открыть эмулятор.

#### Для того чтобы запустить проект через эмулятор надо создать виртуальное устройство:
* В начальном меню выбора проектов Android Studio нажимаем на «три точки», далее жмём ````Virtual Device Manager````.
* В открывшемся окне нажимаем ````Create Device```` и выбираем понравившийся вам из телефонов Google Pixel (советую выбирать последние модели или на одну по старше).
* Далее надо выбрать версию Android на которой будет работать наше виртуальное устройство (не советую выбирать последние версии, так как они могут быть не стабильными).
* Открывается последнее окно с выбором названия вашего виртуального устройства, его ориентации и так далее. Жмём Finish и ваше виртуальное устройство создано.
* Чтобы запустить проект на виртуальном устройстве вам надо в правом верхнем углу самого Android Studio выбрать виртуальное устройство и нажать «зелёный треугольник».

#### Для того чтобы запустить проект через ваше мобильное устройство:
* Сначала надо включить режим разработчика на вашем мобильном устройсте, как это сделать можно посмотреть в интернете, найдя любой похожий телефон от этого же производителя.
* Далее нужно зайти в ````Настройки```` -> ````Параметры разработчика```` и найти здесь ````Отладка по USB```` и включить её.
* После чего подсоединяете ваше мобильное устройство к компьютеру и нажимаете на «зелёный треугольник» в верхней правой части Android Studio.

#### Инструкция по работе с приложением
Запустив приложение и зайдя в ````LogCat```` в ````Android Studio```` вы увидите следуюшие логи:
* ````Обычное сообщение```` в логе для ````LogCat```` обозначаемое буквой ````I```` ````зелёного цвета````.
* ````Обычное сообщение```` в логе для ````Timber```` обозначаемое буквой ````I```` ````зелёного цвета````.
* ````Подробное сообщение```` в логе обозначаемое буквой ````V```` ````белого цвета````.
* ````Отладочное сообщение```` в логе обозначаемое буквой ````D```` ````синего цвета````.
* ````Информационное сообщение```` в логе обозначаемое буквой ````I```` ````зелёного цвета````.
* ````Предупреждающее сообщение```` в логе обозначаемое буквой ````W```` ````жёлтого цвета````.
* ````Ошибка```` в логе обозначаемая букаой ````E```` ````красного цвета````.
