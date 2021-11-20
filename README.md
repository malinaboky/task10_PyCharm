# White&Black filter
______________
### -Размер блока пикселей: 10 pix
### -Градация света: 50

# Исходное изображение :
_______________________________________________
![](picture.jpg)

## -Запуск filter.py

<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/1.png" width="900"/>
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/2.png" width="900"/>
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/new_pic.jpg" width="900"/>

## -Запуск old_filter.py

<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/3.png" width="900"/>
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/4.png" width="900"/>
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/old_pic.jpg" width="900"/>

## -Запуск filter_with_filename.py

<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/6.png" width="900"/>
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/5.png" width="900"/>

Такая колоссальная разница времени выполнения отрефакторенного и старого кода вызвана пользовательским вводом в filter.py: программа осуществляется не сразу, ожидая ввод пользователя.
Для проверки этой гипотезы бал создан файл filter_with_filename.py, в котором изначало прописано имя картинки и прочие необходимые параметры.
За счет этого время выполнение программы существенно сократилось: 29638мс ---> 1108мс. Полученное время намного меньше времени выполнение old_filter.py(18813мс).
Из этого следует, что отрефакторенный код намного быстрее первоначального.

# Тестирование:
_______________________________________________

<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/%D1%82%D0%B5%D1%81%D1%82.jpg" width="900"/>
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/%D0%BA%D0%BE%D0%BD.jpg" width="900"/>

# Отладчик:
_____________________________________________________
<img height="600" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/%D0%B4%D0%B5%D0%B1.jpg" width="900"/>