# Test-Rep-1

Hello world
Hello local PC
rep-2

## Конфликт локальный

## Конфликт

# Отмена изменений последнего коммита
git revert HEAD

# Отмена изменений предпоследнего коммита
git revert HEAD~1

# Отмена изменений первого коммита
git revert HEAD~2

# Отмена последнего коммита (оставляет изменения в рабочей директории)
git reset --soft HEAD^
git restore .

# Отмена предпоследнего коммита (отмена изменений в рабочей директории)
git reset --mixed HEAD^
git restore .

# Отмена первого коммита (удаление изменений)
git reset --hard HEAD~2
