# Algorithms & Data Structures in C++

## Описание проекта

Репозиторий с реализациями популярных алгоритмов и структур данных на C++.

Проект содержит шаблоны и реализации алгоритмов, часто используемых в:
- спортивном программировании
- олимпиадном программировании
- технических интервью
- курсах по алгоритмам и структурам данных

## Структура проекта

```text
Algorithms-Data-Structures/
├── Dijkstra's algo (with heap,set and brute force)      # алгоритм Дейкстры
├── Floyd and Ford-Bellman (+cycles)                     # Floyd-Warshall и Ford-Bellman
├── LCA (+ min on tree path)                             # Lowest Common Ancestor
├── Math_template                                        # математические шаблоны
├── Minimum_spanning_tree_search+DSU                     # MST + DSU
├── Z and prefix functions                               # Z-function и prefix-function
├── binary_search                                        # бинарный поиск
├── hash_machine                                         # алгоритмы хеширования
├── merge and quick sort                                 # merge sort и quick sort
├── queue-mn_mx(...)                                     # очередь с min/max
├── segment_tree (set on segm, sum on segm)              # дерево отрезков
├── sparse_table                                         # sparse table
└── README.md
```

## Реализованные алгоритмы

### Графовые алгоритмы
- Алгоритм Дейкстры
- Floyd-Warshall
- Ford-Bellman
- Поиск минимального остовного дерева
- DSU (Disjoint Set Union)

### Структуры данных
- Segment Tree
- Sparse Table
- Queue with minimum/maximum
- DSU

### Строковые алгоритмы
- Z-function
- Prefix-function
- String hashing

### Алгоритмы сортировки
- Merge Sort
- Quick Sort

### Алгоритмы на деревьях
- LCA (Lowest Common Ancestor)
- Minimum on tree path

### Прочее
- Binary Search
- Mathematical templates

## Используемые технологии

- C++
- STL
- Algorithms
- Data Structures

## Сборка и запуск

Компиляция файла:

```bash
g++ filename.cpp -o main
```

Запуск:

```bash
./main
```

Для Windows:

```bash
main.exe
```

## Цель проекта

- Практика алгоритмов и структур данных
- Подготовка к олимпиадам и соревнованиям
- Подготовка к техническим интервью
- Создание собственной библиотеки шаблонов
