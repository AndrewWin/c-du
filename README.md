# Ответы на вопросы
1) Что такое ООП и для чего оно нужно ? 
 * ООП, объектно-ориентированное программирование - это методология программирования, где каждый объект выступает в роли класса, который имеет свои свойства, методы. Каждый класс может иметь как одного родителя, так и несколько дочерних классов.
  * Три основных свойств, присуще ООП:
    * Наследование
    * Полиморфизм
    * Инкапсуляция
  * ООП нужно для упрощения программирования и создания четкой структуры, иерархии приложения.

2) Что такое наследование, полиморфизм, инкапсуляция ?
 * Наследование - это процесс, в результате которого один объект может перенять свойства другого объекта, то есть родительского, и в последствии их переопределять. Наследоваться можно только от одного объекта(родителя), а дочерних объектов может быть бесконечное количество.
 * Полиморфизм - это свойство, возможность которого использовать одно и то же имя для решения нескольких схожих, но технически разных задач.
 * Инкапсуляция - объединяет данные и код, позволяет скрывать или защищать данные, которые не нужны определенному классу. 
  * Три основных свойства: 
    * public - полный доступ(видимость)
    * protected - доступ(видимость) внутри класса и классам наследников
    * private - доступ(видимость) только внутри класса

3) Что такое MVC и в чём на Ваш взгляд его основное преимущество ?
 * MVC - это способ построения приложения, в котором идет чёткое разделение ответственности за определённый функционал. Это три основных компонента: Model, View, Controller. 
  * Model - обработка данных
  * View - представление данных(внешний вид)
  * Controller - обработка запросов пользователя, формирование представления и вывод пользователю
 
 Основное преимущество MVC - четкое разделение model, view, controller что позволяет удобно работать над одним проектом сразу нескольким людям. Каждый занимается своей частью разработки, не трогая и не изменяя части других. 

4) Что такое фреймворк ?
 * Фреймворк - это ряд инструментов, библиотек, правил, функций, позволяющих ускорить разработку как простых, так и сложных приложений. 
 * Структуру приложения созданного с использованием фреймворка, можно разделить на две части: 
  * 1. Основа - неизменяемая часть. 
  * 2. Дополнение - изменяемая часть добавленная разработчиком.

5) Какую реализацию технологии ORM использует фреймворк YII ?
 * ActiveRecord

6) Для чего нужна нормализация баз данных ? 
 * Нормализация баз данных - удаление в базе данных лишнего, повторяющегося, путем создания новых таблиц и индексированием записей(налаживанием связей). Например: есть база данных сотрудников, у каждого есть должность. До нормализации базы данных, должность записывалась в запись сотрудника. После нормализации базы данных, должность хранится в отдельной таблице, а в записи сотрудника в поле должность, ставится индекс(путь к записи должности).

7) Для чего нужно пространство имен ? 
 * Пространство имен - это область, в которой определяются различные функции, переменные и т.д которые доступны из определенного места. Так например переменная с именем param, может иметь несколько значений.

8) Какие плюсы использования JavaScript в веб-приложении ?
 * JavaScript изначально создавался под веб-приложения. 
 * Высокая скорость работы.
 * Поддерживается всеми популярными браузерами.
 * Скрипты не требуют компиляции(написал - запустил).
 * Довольно лёгкий язык программирования в освоении.
 * Может выполняться не только в бразуере, но и на сервере.

9) Что такое область видимости переменных ? 
 * Область видимости переменных - это область, в которой переменная доступна и хранит свое значение. За пределами области видимости, данная переменная может иметь уже другое значение или же быть неопределенной.

10) Что такое AJAX и в чём на Ваш взгляд его основное преимущество ? 
 * AJAX - это технология JavaScript, позволяющая обмениваться данными с сервером в фоновом режиме, незаметно для пользователя. Главное преимущество AJAX - обновление контента, части страницы, блока без перезагрузки страницы.

11) Что такое JSON ? 
 * JSON - это текстовый формат данных, легко воспринимается и читается человеком, а также может быть использован почти в любом языке программирования, это одно из главных преимуществ. Данные передаются и принимаются в виде пары - ключ:значение

