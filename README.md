# familya_testwork
Редакторы и работа с текстом
Вот скрипт test.sh, который складывает число и длину строки для получения результата 3336:

#!/bin/bash

# Объявляем числовую переменную a
a=3333

# Объявляем строковую переменную b
b="abc"

# Вычисляем длину строки b
len_b=${#b}

# Складываем число a и длину строки b
result=$((a + len_b))

# Выводим результат
echo $result

Описание работы скрипта:


#!/bin/bash: Указывает, что скрипт должен выполняться с помощью bash.
a=3333: Присваивает переменной a числовое значение 3333.
b="abc": Присваивает переменной b строковое значение "abc".
len_b=${#b}: Вычисляет длину строки b и присваивает ее переменной len_b. В данном случае длина строки "abc" равна 3.
result=$((a + len_b)): Складывает значение переменной a (3333) и значение переменной len_b (3) и присваивает результат (3336) переменной result.
echo $result: Выводит значение переменной result (3336) в консоль.
