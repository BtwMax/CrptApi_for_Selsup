# Тестовое задание для компании Selsup

## Задача
Необходимо реализовать на языке Java (можно использовать 17
версию) класс для работы с API Честного знака. Класс должен быть
thread-safe и поддерживать ограничение на количество запросов к
API. Ограничение указывается в конструкторе в виде количества
запросов в определенный интервал времени. Например:
public CrptApi(TimeUnit timeUnit, int requestLimit)
timeUnit – указывает промежуток времени – секунда, минута и пр.
requestLimit – положительное значение, которое определяет
максимальное количество запросов в этом промежутке времени.

Реализовать нужно единственный метод – Создание документа для
ввода в оборот товара, произведенного в РФ. Документ и подпись
должны передаваться в метод в виде Java объекта и строки
соответственно.

Решение должно быть оформлено в виде одного файла
CrptApi.java. Все дополнительные классы, которые используются
должны быть внутренними.

## Стек технологий:
* Java 17
* Maven
* Lombok
* Apache HttpClient
*  Gson для сериализации объектов в JSON