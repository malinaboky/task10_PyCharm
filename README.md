# White&Black filter
______________
### -Размер блока пикселей: 10 pix
### -Градация света: 50

# Исходное изображение :
_______________________________________________
![](picture.jpg)

## -Запуск filter.py

<img height="150" src="https://github.com/malinaboky/task10_PyCharm/blob/main/pics/1.png" width="250"/>
<img height="150" src="D:\task10_PyCharm\2.png" width="250"/>
<img height="150" src="D:\task10_PyCharm\new_pic.jpg" width="250"/>

## -Запуск old_filter.py

<img height="150" src="D:\task10_PyCharm\3.png" width="250"/>
<img height="150" src="D:\task10_PyCharm\4.png" width="250"/>
<img height="150" src="D:\task10_PyCharm\old_pic.jpg" width="250"/>

## -Запуск filter_with_filename.py

<img height="150" src="D:\task10_PyCharm\6.png" width="250"/>
<img height="150" src="D:\task10_PyCharm\5.png" width="250"/>

Такая колоссальная разница времени выполнения отрефакторенного и старого кода вызвана пользовательским вводом в filter.py: программа осуществляется не сразу, ожидая ввод пользователя.
Для проверки этой гипотезы бал создан файл filter_with_filename.py, в котором изначало прописано имя картинки и прочие необходимые параметры.
За счет этого время выполнение программы существенно сократилось: 29638мс ---> 1108мс. Полученное время намного меньше времени выполнение old_filter.py(18813мс).
Из этого следует, что отрефакторенный код намного быстрее первоначального.

# Тестирование:
_______________________________________________

<img height="150" src="D:\task10_PyCharm\тест.jpg" width="250"/>
<img height="150" src="D:\task10_PyCharm\кон.jpg" width="250"/>

# Отладчик:
_____________________________________________________
<img height="150" src="D:\task10_PyCharm\деб.jpg" width="250"/>