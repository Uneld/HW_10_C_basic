# Домашнее задание №10

## Задача 1. Пары соседних символов

В файле `.txt` записаны символы. Необходимо разработать функцию, которая меняет местами пары соседних символов, не обращая внимание на символы пробел. Если количество символов нечетно (пробелы не считаем), то последний символ не меняем. Результат записать в файл `.txt`.

### Данные на входе

Строка из английских букв, пробелов и знаков препинания. Не более 1000 символов.

### Данные на выходе

Строка из английских букв, пробелов и знаков препинания.

### Пример №1

**Данные на входе:**

Hello world!

**Данные на выходе:**

eHllw orodl!

### Пример №2

**Данные на входе:**

abc def

**Данные на выходе:**

bad cfe

## Задача 2. Удалить пробелы из текста

В файле `.txt` необходимо удалить все лишние пробелы (в начале предложения и сдвоенные пробелы). Для решения задачи разработать функцию. Результат записать в `.txt`.

### Данные на входе

Строка из английских букв, знаков препинания и пробелов. Не более 1000 символов.

### Данные на выходе

Строка из английских букв, знаков препинания и пробелов.

### Пример

**Данные на входе:**

Hello world!

**Данные на выходе:**

Hello world!

## Задача 3. Изменить расширение

В файле `.txt` записан полный адрес файла (возможно, без расширения). Необходимо изменить его расширение на ".html" и записать результат в файл `.txt`.

### Данные на входе

Строка состоящая из символов: a-z, A-Z, 0-9, /

### Данные на выходе

Исходная строка с измененным расширением.

### Пример №1

**Данные на входе:**

/DOC.TXT/qqq

**Данные на выходе:**

/DOC.TXT/qqq.html

### Пример №2

**Данные на входе:**

/DOC.TXT/qqq.com

**Данные на выходе:**

/DOC.TXT/qqq.html
