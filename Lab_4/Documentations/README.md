# raster-algorithms
Данное приложение разработано для Лабораторной работы №4 "Базовые растровые алгоритмы".

Использованные языки и среды программирования:
  - C++
  - Qt Creator Использовался комплект "Qt 5.14.4"

Основные объекты приложения:
  - Рабочее окно, где отображена система координат, иллюстрирующая работу базовых растровых алгоритмов  
  - Labels, которые отображают название переменной, которую мы хотим изменить
  - SpinBoxes, где отображаются все переменные, которые можно изменить
  - Combobox для выбора конкретного алгоритма

Используемые библиотеки:

  - QMainWindow(основное поле приложения)
  - QVector (предоставляет работу с векторами)
  - QPoint (описывает точку на плоскости, используя целочисленную точность)
  - QActionGroup (используется для группировки действий)
  - QPainter (выполняет низкоуровневое рисование на виджетах и других устройствах рисования)
 

Реализованный функционал:

  - Отображение работы всех растровых алгоритмов на сетке.
  - Возможность выбора конерктного растрового алгоритма в Combobox.
  - Возможность изменения координат и радиуса.
  

Основные файлы:

  - raster-algorithms.cpp
  - raster-algorithms.h
  - main.cpp
  
  Примечание:

  - Данное приложение было написано с помощью комплектов, предназначенных для Linux(Ubuntu) и Windows.  
  - В папке Executable содержится сборка приложения, его .exe и все необходимые библиотеки и файлы для корректного запуска, однако, не гарантируется отсутствие некорретктного визуального отображения на Windows.
