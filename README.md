# -API
Лабораторная работа
Что такое API ?

API - это сокращение от Application Programming Interface. В общем каждая программа, операционная система и т.д. имеет свой API. Windows - API состоит из целого ряда функций, которые позволяют Вам использовать системные Windows-конструкции. Все Windows-API-функции были написаны в C++, но ваши программы смогут спокойно их использовать из Visual Basic'a. API-функции должны быть обязательно продекларированы! Декларация API-функций имеет следующий синтаксис:

[Public | Private] Declare Function name Lib "libname" [Alias "aliasname"] [([arglist])] [As type]

Ключевое слово Lib указывает, в какой библиотеке Visual Basic может найти нужную функцию. Имеются в виду библиотеки динамических связей (*.dll). Но в aliasname указывать расширение не надо. Alias указывает под каким именем программа должна искать заданую функцию в библиотеке. Arglist - это передаваемые параметры.Windows-API позволяет две вещи: проведение определённых заданий и доступ к системным ресурсам. Список различных API-функций и их деклараций Вы можете просмотреть при помощи стандартной программы API-Viewer.

Примечание: Если АPI-функция ждёт от вас переменной, Вы должны обязательно объявить её и заполнить пробелами. Т.е. переменная должна быть определённой пользователем. Это черты языка С++, на котором и был написан Windows-API.

Правка....
