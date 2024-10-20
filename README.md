# Игра-Тир на Pygame

Это проект представляет собой простую игру-тир, разработанную с использованием библиотеки Pygame. Игроку предлагается стрелять по мишеням, которые появляются на экране, зарабатывая очки за каждое попадание.

## Требования

- Python 3.x
- Библиотека Pygame

Вы можете установить библиотеку Pygame с помощью pip:

```bash
pip install pygame
```

## Как играть

1. **Цель игры**: 
   - Попадать в мишени, которые появляются на экране, чтобы заработать как можно больше очков за отведенное время.

2. **Управление**:
   - Используйте мышь для прицеливания и стрельбы.

3. **Игровой процесс**:
   - Игра начинается с пустого экрана. Мишени появляются случайным образом, и ваша задача — успеть по ним попасть.
   - За каждое попадание начисляются очки. Ваша цель — набрать как можно больше очков до окончания времени.

## Как это работает

Игра состоит из следующих основных компонентов:

1. **Инициализация**: 
   - Настройка окна игры и загрузка необходимых ресурсов, таких как изображения мишеней и звуки выстрелов.

2. **Игровой цикл**:
   - Обработка пользовательского ввода для прицеливания и стрельбы.
   - Анимация появления мишеней и учет попаданий.
   - Обновление экрана и отображение текущего счета.

3. **Завершение игры**:
   - Игра завершается, когда время истекает. Отображается итоговый счет, и игрок может начать заново.

## Дальнейшее развитие

Эту базовую игру можно расширить, добавив:

- Различные уровни сложности
- Дополнительные типы мишеней с различными свойствами
- Возможность улучшения оружия или бонусы
- Таблицу рекордов для хранения лучших результатов

## Лицензия

Этот проект является открытым и доступен по лицензии MIT.
