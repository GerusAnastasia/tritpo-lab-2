# Требования к проекту
### Содержание
1. [Введение](#1) <br>
  1.1. [Назначение](#1.1) <br>
  1.2. [Бизнес-требования](#1.2) <br>
      1.2.1. [Границы проекта](#1.2.1) <br>
  1.3 [Аналоги](#1.3) <br>
2. [Требования пользователя](#2) <br>
  2.1. [Программные интерфейсы](#2.1) <br>
  2.2. [Интерфейс пользователя](#2.2) <br>
  2.3. [Характеристики пользователей](#2.3) <br>
  2.4. [Предположения и зависимости](#2.4) <br>
3. [Системные требования](#3.) <br>
  3.1. [Функциональные требования](#3.1) <br>
  3.2. [Нефункциональные требования](#3.2) <br>
     3.2.1. [Атрибуты качества](#3.2.1) <br>
     3.2.2. [Внешний интерфейс](#3.2.2) <br>


### 1. Введение <a name="1"></a>
#### 1.1 Назначение <a name="1.1"></a> 

[VMSiS Simulator]() - приложение для ОС Android, предназначение которого заключается в донесении до абитуриентов и студентов БГУИРа, каково учиться на специальности ВМСиС факультета компьютерных сетей и систем.

#### 1.2 Бизнес-требования <a name="1.2"></a>
##### 1.2.1. Границы проекта <a name="1.2.1"></a>

Приложение предоставляет следующие возможности:

* Выбор уровня сложности
* Ветвление сюжета
* Прохождение игры

#### 1.3 Аналоги <a name="1.3"></a>

* Симулятор Гаишника - шуточный текстовый симулятор жизни типичного гаишника.
* Симулятор жизни Ютубера - симулятор, в котором нужно играть роль ютубера и всячески развивать свой канал.
* BitLife - текстовый симулятор жизни, в котором нужно пройти весь жизненный путь персонажа, выбирая его действия.

### 2. Требования пользователя <a name="2"></a>
#### 2.1. Программные интерфейсы <a name="2.1"></a>

* [Kotlin](https://kotlinlang.org/) - статически типизированный объектно-ориентированный язык программирования, работающий поверх Java Virtual Machine. Активно заменяющий Java как основной язык в сфере разработки для ОС Android.
* [LibGdx](https://libgdx.badlogicgames.com/) - фреймворк для разработки игры на языке Java. Он позволяет писать кроссплатформенные игры и приложения используя один код.

#### 2.2. Интерфейс пользователя <a name="2.2"></a>
Графический интерфейс проекта представлен с помощью мокапов

#### 2.3. Характеристики пользователей <a name="2.3"></a>

Абитуриенты, желающие поступить на ВМСиС, и студенты, не знающие, каково там учиться.

#### 2.4. Предположения и зависимости <a name="2.4"></a>
Данное приложение поддерживается на устройствах под управлением ОС Android версии 5.1 и выше. 

### 3. Системные требования <a name="3"></a>

Операционная система Android 5.1 и выше.

#### 3.1. Функциональные требования <a name="3.1"></a>

Пользователю предоставлены возможности, представленные в таблице.

Функция | Требования
--- | ---
Выбор уровня сложности | Приложение должно предоставить выбор уровня сложности игры.
Ветвление сюжета | Должны быть предусмотрены различные варианты развития сюжета.
Адаптивный интерфейс | Приложение должно поддерживать различные устройства и иметь одинаковое отображение на различных экранах.


#### 3.2. Нефункциональные требования <a name="3.2"></a>

##### 3.2.1. Атрибуты качества <a name="3.2.1"></a>
* Производительнось. Рациональное использование ресурсов устройства для корректной работы на слабых телефонах.
* Понятность. Интуитивный и удобный интерфейс.


##### 3.2.2 Внешний интерфейс <a name="3.2.2"></a>
Пользовательский интерфейс приложения должен быть удобным и не отвлекающим от игры.

