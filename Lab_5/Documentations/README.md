#cutting-segments-and-polygons
Данное приложение разработано для Лабораторной работы №5 "Алгоритмы отсечения отрезков и многоугольников".

Использованные языки и среды программирования:

C++
Qt Creator Использовался комплект "Qt 5.14.4"
Основные объекты приложения:

Рабочее окно, где отображена система координат, иллюстрирующая работу алгоритмов отсечения отрезков и многоугольников
RadioButton, которые позволяют выбрать режим работы
PushButton, который дает возможность подгрузить текстовый файл с координатами отрезков и многоульника
Используемые библиотеки:

QMainWindow(основное поле приложения)
QVector (предоставляет работу с векторами)
QPoint (описывает точку на плоскости, используя целочисленную точность)
QPainter (выполняет низкоуровневое рисование на виджетах и других устройствах рисования)
QFile (позволяет считывать информцию с файлов)
QFileDialog(функционал для работы с файловой системой)
Реализованный функционал:

Отображение системы координат в основном поле приложения.
Выполнение отсечения отрезков алгоритмом средней точки.
Реализация отсечения выпуклого многоугольника.
Отображение отсекающего окна красным цветом; отрезки (многоугольники), входящие в отсекающее окно – зеленым; отрезки (многоугольники), не входящие в
отсекающее окно – синим.
Основные файлы:

cuttingpolygons.cpp
cuttingpolygons.h
main.cpp
Примечание:

Данное приложение было написано с помощью комплектов, предназначенных для Ubuntu(Linux) и Windows.
В папке release содержится сборка приложения, его .exe и все необходимые библиотеки и файлы для корректного запуска, однако, не гарантируется отсутствие некорретктного визуального отображения на Windows.