#### Task 1

Решение:
1. Тесты(юнит-тесты)

* добавление нового контакта - проверяет корректность работы функции добавления нового контакта в базу данных;
* удаление контакта - проверяет корректность работы функции удаления контакта из базы данных;
* редактирование контакта - проверяет корректность работы функции редактирования контакта в базе данных;

  Вместо реальной базы данных испольуют mock-заклушку.
* Проверка на правильность заполнения полей - тестирует функции добавления полей,тем самым гарантируя, что все поля заполнены правильно при редактировании, добавлении или удалении контакта.
2. Тесты(интеграционные)
* Вывод конкретного контакта на экран - тестирует корректно ли приложение возвращает контакт из бд;
* Вывод, имеющихся контактов на экран - тестирует корректно ли приложение возвращает все контакты из бд;

в этих тестах уже используется действительная база данных

3. Тест(сквозной) "Проверка полного цикла программы" - тестирует правильность выполнения полного цикла программы создание контакта, поиск контакта, редактирование контакта, вывод на экран и
   при необходимости его удаление

#### Task 2

1. Это юнит-тест, т.к это проверка конкретной функциональности - добавление контакта
2. Это интеграционный тест, т.к этот тест проверяет как различные части системы взаимодействуют между собой
3. это сквозной тест, т.к этот тест охватывает все этапы работы с контактом и проверяет, что каждый из них выполняется
   корректно



