# A. Быстрый поиск в массиве

- **Ограничение времени:** 3 секунды
- **Ограничение памяти:** 64Mb
- **Ввод:** стандартный ввод или `input.txt`
- **Вывод:** стандартный вывод или `output.txt`

Задача состоит в эффективном ответе на запросы о количестве чисел в заданном диапазоне в массиве.

## Формат ввода

В первой строке задано число `N` (1 ≤ N ≤ 10^5), количество элементов массива. В следующей строке перечислены `N` целых чисел массива. После этого задано число запросов `K` (1 ≤ K ≤ 10^5). В последующих `K` строках находятся пары чисел `L`, `R` (−10^9 ≤ L ≤ R ≤ 10^9) — запросы, где нужно найти количество чисел в массиве со значениями от `L` до `R`.

## Формат вывода

Вывести `K` чисел, каждое из которых является ответом на соответствующий запрос о количестве чисел в заданном диапазоне.

### Пример

#### Ввод

```
5
10 1 10 3 4
4
1 10
2 9
3 4
2 2
```

#### Вывод

```
5 2 2 0
```

Каждое число в выводе соответствует количеству элементов массива в диапазоне от `L` до `R` для каждого запроса.

Решение в файле [*A.java*](A.java).