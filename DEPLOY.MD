# Настройка базы данных

# Установка 
 ```
 pip install -r requirements.txt 
 ```

 # Запуск
 ```
 python main.py
 ```

 # Дополнительные команды

1. Удалённое сохранение БД локально:

```
pg_dump "External URL" -Fc > backup_$(date +%F).dump
```
2. Проверка БД:

```
psql "External URL" -c "SELECT 1;"
```
