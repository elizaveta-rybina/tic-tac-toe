# Tic-Tac-Toe PHP Game

Простая консольная реализация классической игры "Крестики-нолики" на PHP.

## 📦 Установка

### Глобальная установка через Composer:

```bash
composer global require elizaveta-rybina/tic-tac-toe-php
```

### Локальная установка:

```bash
git clone https://github.com/elizaveta-rybina/tic-tac-toe.git
cd tic-tac-toe
composer install
```

## 🚀 Запуск игры

После установки запустите игру командой:

```bash
tictactoe
```

Или из локальной копии:

```bash
php bin/tictactoe
```

## 🎮 Как играть

1. Игроки по очереди вводят координаты (x y) от 1 до 3
2. Первый игрок играет за X, второй за O
3. Побеждает тот, кто первым соберет 3 своих символа в ряд

Пример хода:

```
Player X, enter your move (x y, 1-3): 2 2
```

## 🔗 Ссылки

- [GitHub репозиторий](https://github.com/elizaveta-rybina/tic-tac-toe)
- [Пакет на Packagist](https://packagist.org/packages/elizaveta-rybina/tic-tac-toe-php)

## 📂 Структура проекта

```
bin/            - Исполняемый файл
src/            - Исходный код
├── Core/       - Игровая логика
└── Cli/        - Консольный интерфейс
```

## 💻 Системные требования

- PHP 8.4.5+
- Composer (для установки)
