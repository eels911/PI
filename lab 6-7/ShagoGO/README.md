**ShagoGO - это шагомер под Android**

Приложение совместимо с Android 4.4 (API 19) и выше.

# Краткое описание
После того, как я не нашел на Play Market шагомера, который бы полностью удовлетворял мои ожидания и желания, было создано это приложение.
Шагомер для своей работы использует данные акселерометра. В приложении во главу угла было поставлено пройденное расстояние, а не количество сделанных шагов. Также в приложении отсутствует информация о потраченных калориях.

# Поддерживаемые языки
- английский (по умолчанию)
- русский
- украинский

![Image](/screenshots/1.png)

# Описание основного функционала
На главном экране приложения можно посмотреть пройденное за сегодня расстояние, время, скорость и количество шагов. Кнопка запускает/останавливает подсчет шагов. На графике отображается расстояние, которое было пройдено за каждый час. Таким образом, можно визуально оценить насколько, например, большее или меньшее расстояние было пройдено вечером нежели утром.

![Image](/screenshots/2.png)

На notification для foreground сервиса показывается пройденное расстояние за сегодня, а также находится кнопка включения/выключения шагомера. Таким образом, одним движением можно посмотреть пройденное расстояние, двумя - запустить/остановить шагомер.

![Image](/screenshots/3.png)

# Дополнительный функционал и вкладки
![Image](/screenshots/4.png)

## Домой 
Возврат на главный экран шагомера

## Таймер
Позволяет засечь время и пройденное расстояние. Удобно для определения расстояния между пунктами А и Б. 

![Image](/screenshots/5.png)

## История
Позволяет просмотреть историю за день, неделю или месяц. 

![Image](/screenshots/6.png)

## Удалить историю
Позволяет удалить историю, требует при этом дополнительного подтверждения.

![Image](/screenshots/7.png)

## Настройки
Позволяет настроить порог чувствительности, ширину шага и ожидаемое расстояние, которое проходится за день. Первые два параметра используются для правильного подсчета шагов и расстояния. Последний параметр используется для цветового отображения пройденного расстояния на главном экране.

![Image](/screenshots/8.png)
![Image](/screenshots/9.png)

## Выход
Выход из приложения с остановкой foreground сервиса