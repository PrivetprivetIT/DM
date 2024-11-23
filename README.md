# DM описание игры

### (Впервые работаем с ***ветками***)


## Описание кода:
### 1.Импортирование библиотеки:

***from tkinter import***
Импортируем все функции и классы из модуля tkinter, который используется для создания графического интерфейса.

### 2.Инициализация переменных:
Устанавливаем размеры окна (w и h), размер игрока (player_size) и начальные координаты первого игрока (x1, y1). Также определяем цвет игрока ('red') и конечную точку финиша (x_finish).
### 3.Функция обработки нажатий клавиш:
Функция key_handler вызывается при отпускании клавиши. Она перемещает прямоугольник игрока на 10 пикселей вправо каждый раз, когда пользователь нажимает любую клавишу.
### 4.Создание окна и холста:
Создаем главное окно приложения (Tk()), задаем ему заголовок и создаем холст (Canvas), где будет происходить игра. Затем размещаем холст внутри окна.
### 5.Отображение объектов:
На холсте рисуем два объекта: красный прямоугольник (игрок) и черный финишный столбик. Игрок отображается слева вверху, а финишный столб находится справа.
### 6.Привязка событий к клавишам:
Привязываем событие отпускания любой клавиши к функции key_handler.
### 7.Запуск главного цикла программы:
Запускаем главный цикл программы, чтобы окно оставалось активным до тех пор, пока пользователь не закроет его.
## Правила игры:
Игрок управляет красным прямоугольником, пытаясь дойти до черного столбика, расположенного справа. Для перемещения нужно просто нажать любую клавишу на клавиатуре. Каждый раз при нажатии игрок продвигается вперед на 10 пикселей. Цель игры — добраться до финиша как можно быстрее.
=======
## План работы:
+ создать репозиторий DM
+ добавить окружение
+ в ветке **main** написать часть кода
+ закоммитить изменения
+ создать ветку **new_branch**
+ дописать код в только что созданной ветке
+ закоммитить изменения **new_branch**
+ объединить ветки
+ радоваться результату
>>>>>>> 17ebad649be36f212ab0c286ee7a90449489f345
