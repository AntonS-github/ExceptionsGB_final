# ExceptionsGBCourse
Working with exceptions studying (with Java)

# Домашнее задание №1
![Картинка задания](./HomeWork%201/%D0%97%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5.png)



1.  [Код задачи 1](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%201/Homework11.java)

2.  * вместо числа в строке может быть что угодно (java.lang.NumberFormatException)
    * выход за границу массива если в строке меньше 5-ти значений (java.lang.ArrayIndexOutOfBoundsException)
    * если на вход вместо массива придёт Null (java.lang.NullPointerException)
    
3.  [Код задачи 3](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%201/Homework13.java)

4.  [Код задачи 4](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%201/Homework14.java)



# Домашнее задание №2
![Домашнее задание2](./HomeWork%202/%D0%94%D0%97%202.png)

1. [Код задачи 1](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%202/Homework21.java)

2. [Код задачи 2](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%202/Homework22.java)
Так как применяются массив, то кроме арифметики хорошо бы ещё отследить возможные проблеммы с массивом (такие как выход за границы массива). Ну и так как мы осущесвтляем действия которые требует наличия данных перехватываем так же null, (но по хорошему надо проверку делать и не допускать null'ы изначально?)

3. [Код задачи 3](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%202/Homework23.java)
Зачем прокидывать throw Exception если мы о них уже сообщили и обработали (убираем). Меням очерёдность исключений и добавляем так как есть деление на всякий случай обработку деления на 0. Во внешней функции сложения зачем-то прокидываем Ошибку которой там обзароваться не может (так же просто защитились на случай null значений считаем их 0 - но этот вопрос нужно уточнять по "ТЗ" какое поведение ожидаемо)


4. [Код задачи 4](https://github.com/AlexanderSibirko/ExceptionsGBCourse/blob/main/HomeWork%202/Homework24.java)