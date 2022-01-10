## Домашнее задание к занятию "3.1. Работа в терминале, лекция 1

1. выполнено
2. выполнено
3. выполнено
4. ![1.jpg](./assets/1641671341006-1.jpg)
5. ![2.jpg](./assets/1641674046642-2.jpg)
6. Как добавить оперативной памяти или ресурсов процессора виртуальной машине? - путем изменения в Vagrantfile строчек:
   ![3.jpg](./assets/1641675929637-3.jpg)
7. ![4.jpg](./assets/4.jpg)
8. после команды `vagrant ssh` заходим в мануал - `man bash`, для поиска по страницам мануала использовал команду "/keyword" и кнопку "n" для перемещения по найденныи словам.

   - HISTFILESIZE - строка 690, HISTSIZE - строка 703
   - Если список значений включает в себя ignorespace, строки, начинающиеся с символа пробела, не сохраняются в списке истории. Значение ignoredups приводит к тому, что строки, соответствующие предыдущей записи истории, не сохраняются. Значение ignoreboth является сокращением для ignorespace и ignoredups.
9. BASH_SOURCE - Переменная массива, членами которой являются имена исходных файлов, где соответствующие имена функций оболочки в переменной массива FUNCNAME определены. Иначе говоря - цикличное выполнение команд.
10.

```
touch {1..100000}.txt
```

300000 создать не получилось, это слишком дилинный список аргументов
