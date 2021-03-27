# course-platform-.NET-
Учебные лабораторные работы по дисциплине "Платформа .NET"(С#)
2.1. Создать иерархию классов Person-Student-Teacher. Каждый класс – в своей сборке. В каждом классе должны быть свойства, а также виртуальная функция Print и переопределенная функция ToString(). Основная программа создает массив объектов Person или их наследников, после чего выдает его на экран. У каждого Teacher должен быть список Students, которыми он руководит, у каждого Student - Teacher, который им руководит.

Замечание. В процессе реализации возникнет такая ошибка как циклическая зависимость сборок: сборка Student зависит от сборки Teacher и наоборот. Для устранения этой ошибки рекомендуется создать класс Student без поля Teacher, после чего создать производный класс StudentWithAdvisor с полем Teacher в отдельной сборке.

2.2. Для классов Person-Student-Teacher реализовать и оттестировать ToString(), Equals(), GetHashCode().

2.3. Для классов Person-Student-Teacher реализовать статические методы RandomPerson, RandomStudent, RandomTeacher, которые возвращают случайного из некоторого статического массива.

2.4. С помощью is, as, GetType определить, сколько в массиве персон, студентов и преподавателей и перевести всех студентов на следующий курс.

2.5. Для классов Person-Student-Teacher реализовать глубокое клонирование, определив виртуальный метод Clone(). Клон должен возвращать точную копию по значению и типу. Проиллюстрировать Clone на примере контейнера персон - должны создаваться клоны объекты ровно тех типов, которые содержатся в исходном контейнере.

(нет) 2.6. Используя метод GetType() класса Student и метод BaseType() класса Type, вывести всех предков класса Student (написать общий метод)
