# Разбиение числа

Набор положительных чисел a<sub>1</sub>, a<sub>2</sub>, ..., a<sub>k</sub> называется разбиением натурального числа[^1] n, если n = a<sub>1</sub> + a<sub>2</sub> + ... + a<sub>k</sub>, где a<sub>1</sub> ⩾ a<sub>2</sub> ⩾...⩾ a<sub>k</sub> > 0.

Например, существует 5 различных разбиений числа 4:
* 1+1+1+1
* 2+1+1
* 2+2
* 3+1
* 4

Необходимо для заданных чисел n и k вычислить число возможных разбиений n на k частей.

Шаблон программы приведен в файле `partition.cpp`. В нём необходимо написать реализацию функции `partition`.

Числа n и k пользователь вводит с клавиатуры (n, k⩽500). Результатом работы программы является выведенное в консоль число разбиений n на k частей.

### Пример
**Вход:** `4 2`

**Выход:** `2`

## Требования к реализации
Программа не должна использовать контейнеры STL (std::vector, std::string и т. д.). 

[^1]: <https://en.wikipedia.org/wiki/Partition_(number_theory)>
