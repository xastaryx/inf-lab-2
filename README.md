# Отчет по лабораторной работе 2

Чтобы написать скрипт, который будет преобразовывать десятичный IP адрес в двоичный, первым делом я создала массив с помощью команды `declare -a`

На stackoverflow я узнала, что существует встроенная команда `D2B`, с помощью которой можно преобразовывать десятичные числа в двоичные.

В переменную `ip4` я заношу считываемое с терминала число.

`IFS='.'` означает, что вместо пробелов число будет разделено точкой.

Затем пишу цикл в промежутке от первого числа до третьего, который выводит преобразованное двоичное число без перехода на новую строку (-n) и с точкой на конце. Затем вывожу отдельно преобразованное последнее число без точки на конце.


![Снимок экрана 2024-10-03 212341](https://github.com/user-attachments/assets/eb520f4d-b626-4dc2-b38b-9a03069900bc)

Убеждаюсь, что скрипт работает так, как задумано.

![Снимок экрана 2024-10-07 193854](https://github.com/user-attachments/assets/7e96d608-84ac-4348-9f93-64bd5808fb1a)



