# Модель Лотки–Вольтерры

Программа для численного моделирования системы хищник–жертва.

## Возможности

- решение системы дифференциальных уравнений методом Рунге–Кутты 4 порядка;
- изменение параметров модели;
- построение временных графиков;
- построение фазового портрета;
- экспорт результатов в CSV.

## Поддерживаемые системы

Windows 10/11  
Linux Debian-based

## Запуск

### Windows

Скачать:
`Lotka_Volterra_Windows.exe`

Запустить файл.

### Linux

Скачать:
`Lotka_Volterra_Linux`

Выдать права:

```bash
chmod +x Lotka_Volterra_Linux
```

Запуск:

```bash
./Lotka_Volterra_Linux
```

### Запуск из исходников

Требуется Python 3.13.

Установка зависимостей:

```bash
pip install -r requirements.txt
```

Запуск:

```bash
python main.py
```

---

# requirements.txt

Создай:

```bash
pip freeze > requirements.txt
```
