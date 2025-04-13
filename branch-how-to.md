## Как пользоваться ветками в Git

### 1. Создание новой ветки
```bash
git branch your-surname
```

### 2. Переключение на новую ветку
```bash
git checkout your-surname
```

### 3. Добавление и коммит нового файла

Создай файл

Проверь статус репозитория:
```bash
git status
```
Добавь файл в индекс:
```bash
git add branch-how-to.md
```
Снова проверь статус:
```bash
git status
```
Сделай коммит:
```bash
git commit -m "branch instructions"
```
### 4. Отправка ветки на сервер
```bash
git push -u origin your-surname
```
Теперь твоя ветка и изменения окажутся на GitHub