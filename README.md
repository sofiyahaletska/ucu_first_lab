# UCU_OP
Загальна інформація:
Модуль Map_builder.py будує карту з п'ятьма шарами.
Після запуску модуля вказати рік, тоді:
На першому шарі будуть відображенні мітки зі всіма фільмами за це рік у локаціях де вони були зняті
Другий шар це відображення кількості населення на карті світу за допомогою кольорів: червоного(від 50 млн і більше), жовтого(від 10 млн до 50 млн), зеленого(менше 10 млн)
Третій шар також відображає кількість населення, проте станом на 1900 рік і лише у трьох локаціях: Кути, КутиСтарі, Брустури(області обведені у фіолетовий колір)
Четвертий шар показує те ж саме, що і третій, проте станом на 1914 рік (області обведено білим кольором)
П'ятий аналогічно до попередніх двох ілюструє кількість населення станом на 1938 рік
Для зручності на 3-ьох останніх нарах була введенна така система порівнянь:
Червоний - більше 3,5 тис
Жовтий - від 2 до 3,5 тис 
Зелений - менше 2 тис
Структура тегів:
<!DOCTYPE html> - визначає тип документа
<head> - вказує технічну інформацію про документ
<meta> -  визначає метатеги, які зберігають службову інформацію для браузерів та пошукових систем charset, content, http-equiv, name
<script> -  призначений для опису скриптів. Може містити посилання на програму або її текст asyne, type charset defer,src
<link> - встановлює зв'язок із зовнішнім документом href, hreflang, media, rel, sizes, type
<style> - встановлює зв'язок із зовнішнім документом href, hreflang, media, rel, sizes, type
<body> - визначає елемент body(тіло документа)
<div> - визначає розділ(частину, блок) документа.
Висновок: 
За допомогою такого модуля можемо побудувати карту з мітками там, де знімалися фільми певного року вказаного при запуску цього модуля, також 
побачити зміну кількості населення в трьох локаціях в різні роки і порівняти всі країни на Землі за кількістю населення користуючись кольоровими позначками на карті  
#Я не додала в репозиторій файл locations.csv, який використовувала в модулі Map_builder.py, оскільки він важить більше 25MB  
