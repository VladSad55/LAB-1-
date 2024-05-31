# Лабораторна робота № 6

## Тема: Дублювання коду

### Мета
Рефакторинг коду з проблемою «Дублювання коду» для підвищення читабельності, підтримуваності та повторного використання коду.

### Завдання 1

#### Опис проблеми
У початковому коді функції `calculate_total_price` і `calculate_total_price_with_tax` містять дубльований код, який розраховує загальну ціну продуктів з урахуванням знижки.

#### Рішення
Об'єднано функції в одну, додавши параметр для податку, що дозволяє зменшити дублювання коду.

### Завдання 2

#### Опис проблеми
У початковому коді класу `DataAnalyzer` методи `calculate_total` і `calculate_average` використовують дубльований код для обчислення загальної суми і кількості елементів.

#### Рішення
Розділення логіки на окремі методи для кожного обчислення, що дозволяє уникнути дублювання коду та спрощує підтримку.

### Висновок
Рефакторинг дозволив зменшити дублювання коду, підвищити його читабельність і забезпечити легшу підтримку і розширення в майбутньому.