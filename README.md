Задачи для отработки навыков работы с git:
===

I. Основные
---
1. Зарегистрироваться на githab
2. Создать репозиторий с названием "lesson_001"
3. Добавить первый файл "index.php"
```php
<?php

echo 'Hello world!';
```
4. Создать ветку "dev"
```bash
git checkout -b dev
```
5. В ветке "dev" отредактировать index.php
```php
<?php

echo 'Hello Dmitriy!';
```
6. В ветке "master" отредактировать index.php
```bash
git checkout master
```
```php
<?php

echo 'Hi world!';
```
7. Объединить dev с master
```bash
git merge dev
```
8. Пригласить меня, логин "DmitriyRudenskiy"

II. Дополнительные
---
1. Разница между "rebase" и "merge"
2. Зачем нужен "rebase", если есть "merge"
3. Как вернуться (откатиться) к более раннему "commit"