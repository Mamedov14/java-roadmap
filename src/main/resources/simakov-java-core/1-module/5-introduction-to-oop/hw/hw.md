### Задача 1
- Создать класс "Сотрудник" с полями: ФИО, должность, email, телефон, зарплата, возраст.
### Задача 2
- Конструктор класса должен заполнять эти поля при создании объекта.
### Задача 3
- Внутри класса «Сотрудник» написать метод, который выводит информацию об объекте в консоль.
### Задача 4
- Создать массив из 5 сотрудников.

Пример:
```java
Person[] persArray = new Person[5]; // Вначале объявляем массив объектов
persArray[0] = new Person("Ivanov Ivan", "Engineer", "ivivan@mailbox.com", "892312312", 30000, 30); // потом для каждой ячейки массива задаем объект
persArray[1] = new Person(...);
...
persArray[4] = new Person(...);
```

### Задача 5
- С помощью цикла вывести информацию только о сотрудниках старше 40 лет.