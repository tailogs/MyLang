# Eye

![Eye Logo](https://github.com/tailogs/Eye/assets/69743960/238ea7db-d4a2-4969-a4bc-115133a571a8)

Eye - это простой интерпретируемый язык программирования, разработанный в рамках проекта для изучения компиляторных технологий. Eye преимущественно ориентирован на объектно-ориентированное программирование, но также включает элементы функционального программирования.

## Установка

1. **Клонировать репозиторий:**

   ```bash
   git clone https://github.com/tailogs/Eye.git
   cd Eye
   ```

2. **Запуск примера:**

   ```bash
   python3 Eye.py
   ```

## Возможности

- **Переменные:** поддерживаются переменные типов: числа, строки и булевы значения.
- **Функции:** можно определять функции с произвольным числом аргументов и возвращаемым значением.
- **Арифметические операции:** поддерживаются операции сложения, вычитания, умножения и деления.
- **Вывод на экран:** доступна функция `print` для вывода значений на экран.

## Примеры

Пример кода на Eye:

```eye
let x = 10;
let s = "Hello, world!";
let b = true;

fn add(a, b) {
    return a + b;
}

let y = add(x, 20);
print(y);    // Выведет: 30
print(s);    // Выведет: Hello, world!
print(b);    // Выведет: True
```

## Синтаксис

### Переменные

```eye
let x = 10;
let s = "Hello, world!";
let b = true;
```

### Функции

```eye
fn add(a, b) {
    return a + b;
}
```

### Вызов функций

```eye
let y = add(x, 20);
```

### Вывод на экран

```eye
print(y);
```

## Что планируется в будущем

Eye находится в стадии активной разработки, и разработчики планируют внедрить следующие возможности:

- **Условные операторы:** Добавление операторов `if`, `else`, `ifel (аналог elif)` для выполнения условных проверок и ветвлений в коде.

- **Циклы:** Реализация циклов `while` `do while` и `for` для многократного выполнения блоков кода в зависимости от условий или количества итераций.

- **Массивы:** Введение поддержки массивов для хранения упорядоченных коллекций данных одного типа.

- **Функции высшего порядка:** Возможность создания функций, которые принимают другие функции в качестве аргументов или возвращают их как результат.

- **Стандартная библиотека:** Разработка стандартной библиотеки функций и утилит для общих задач программирования, таких как работа со строками, математические операции и управление файлами и т.д.

- **Обработка ошибок:** Улучшение системы обработки ошибок для предоставления более информативных и полезных сообщений об ошибках.

- **Модульная система:** Введение модульной системы для организации кода на более крупном масштабе, позволяющая лучше структурировать проекты и повторно использовать код.

- **Оптимизации интерпретатора:** Улучшение производительности выполнения кода через оптимизацию.

- **Интеграция с другими языками:** Разработка возможности интеграции Eye с другими языками программирования для улучшения совместимости и расширения возможностей разработки.

- **Комментарии** Введение поддержки однострочных (начинающихся с символов `--`) и многострочных комментариев.

- **Компилирование** Переписать исходный код данного языка программирования на любой компилируемый язык программированя.

- **Самосборка** Переписать исходный код данного языка программирования на самого себя (возможно реализовать только после реализации пункта "Компилирование").

- **ООП** Реализация всех возможностей и трех главных принципов ООП.

- **Декларативность** Реализовать некоторые из возможностей функциональных языков, но не более того.

Эти шаги направлены на постепенное расширение функциональности Eye, делая его более мощным и универсальным инструментом для создания программ, при этом учитывая текущие ограничения и возможности языка.

## Зависимости

- Python 3.x

## Лицензия

[MIT](LICENSE)

---

Этот README.md предоставляет общее представление о языке Eye, включая установку, возможности, примеры кода, планы на будущее и информацию о синтаксисе.