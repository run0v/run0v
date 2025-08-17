---
title: "Шпаргалка по Git"
date: 2025-08-05
draft: false
---

## Основные команды Git

```bash
# Клонировать репозиторий
git clone https://github.com/user/repo.git

# Добавить изменения
git add .

# Закоммитить
git commit -m "Сообщение"

# Отправить на сервер
git push origin main

# Обновить локальную копию
git pull
```

### Полезные алиасы
```bash
alias gs="git status"
alias gl="git log --oneline --graph"
alias gd="git diff"