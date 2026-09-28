# Команды для тестирования мода в креативе

## Базовые команды

### Добавить путь игроку
```
/path add @s warrior
/path add @s hunter
/path add @s miner
```

### Установить уровень пути на 20
```
/path setlevel @s warrior 20
/path setlevel @s hunter 20
/path setlevel @s miner 20
```

### Добавить опыт
```
/path addxp @s warrior 5000
```

### Посмотреть свои пути
```
/path list @s
```

### Сбросить все пути
```
/path reset @s
```

## Быстрая настройка для тестирования

### Воин (20 уровень)
```
/path add @s warrior
/path setlevel @s warrior 20
```

### Охотник (20 уровень)
```
/path add @s hunter
/path setlevel @s hunter 20
```

### Пиромаг (20 уровень)
```
/path add @s pyromancer
/path setlevel @s pyromancer 20
```

## Тестирование способностей

После установки 20 уровня нажмите **R** для использования финальной способности.

### Кулдауны способностей:
- Воин: 5 минут
- Охотник: 3 минуты
- Шахтёр: 10 минут
- Фермер: 15 минут
- Алхимик: 20 минут
- Чародей: 30 минут
- Исследователь: 5 минут
- Защитник: 8 минут
- Пиромаг: 7 минут
- Криомаг: 7 минут
- Инженер: 15 минут
- Ночной Странник: 8 минут

## Управление

- **P** - Открыть меню путей
- **R** - Использовать финальную способность (требуется 20 уровень)

## Примеры комбинаций для тестирования синергий

### Мастер оружия (Воин + Охотник)
```
/path add @s warrior
/path add @s hunter
/path setlevel @s warrior 20
/path setlevel @s hunter 20
```

### Мастер стихий (Пиромаг + Криомаг)
```
/path add @s pyromancer
/path add @s cryomancer
/path setlevel @s pyromancer 20
/path setlevel @s cryomancer 20
```

### Индустриал (Шахтёр + Инженер)
```
/path add @s miner
/path add @s engineer
/path setlevel @s miner 20
/path setlevel @s engineer 20
```
