# pz5-db

Задачи проекта
1.	Установить и настроить PostgreSQL локально.
2.	Подключиться к БД из Go с помощью database/sql и драйвера PostgreSQL.
3.	Выполнить параметризованные запросы INSERT и SELECT.
4.	Корректно работать с context, пулом соединений и обработкой ошибок.

---

## Установка и запуск

(Необходимы предустановленные Go, Git и PostgreSQL)

Клонировать репозиторий:

```
git clone https://github.com/Unpatches/pz5-db
cd pz5-db
```

Команда запуска сервера:

```
go run .
```


------

## Структура проекта

```plaintext
pz5-db/
├── .env
├── db.go                               
├── go.mod
├── go.sum
├── main.go                 
└── repozitory.go        
```

## Отчёт о проделанной работе

### БД
<img width="603" height="791" alt="image" src="https://github.com/user-attachments/assets/ef668588-d089-4a76-ad7c-4df793bd4b05" />

### Запуск сервера
<img width="521" height="201" alt="image" src="https://github.com/user-attachments/assets/6490d030-c2d7-418e-8756-0455b15e694e" />

### Запуск сервера после изменений
<img width="789" height="341" alt="image" src="https://github.com/user-attachments/assets/4df9d665-5a44-4d1c-93f4-f622fc882236" />

### в psql
<img width="599" height="249" alt="image" src="https://github.com/user-attachments/assets/611ddcc1-465c-4bf2-87c1-63bb5fc54c3b" />




