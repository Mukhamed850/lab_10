# Лабораторная 10
# Шаблонный класс

Реализовать шаблонный класс, соответствующий варианту.

Перегрузить оператор <<, который помещает объект вашего класса в поток в удобочитаемом виде. 

Работу методов класса следует проиллюстрировать в main. 

## Варианты:

### Вариант 0
##### Название
MyBinaryTree
##### Основной функционал
push(item) — добавляет элемент в дерево
##### Описание, принцип работы
Бинарное дерево — это упорядоченное дерево, каждая вершина которого имеет не более двух поддеревьев, причём для каждого узла выполняется правило: в левом поддереве содержатся только ключи, имеющие значения, меньшие, чем значение данного узла, а в правом поддереве содержатся только ключи, имеющие значения, большие, чем значение данного узла.

### Вариант 1
##### Название
MyPriorityQueue
##### Основной функционал
push(item) — добавляет элемент в очередь с учетом приоритета;
pop() — берёт элемент из очереди с учетом приоритета и удаляет его;
peek() — берёт элемент из очереди с учетом приоритета без удаления;
size() — возвращает количество элементов в очереди.
##### Описание, принцип работы
Реализация на усмотрение студента, объяснить решение на защите.

### Вариант 2
##### Название
MyDeck
##### Основной функционал
push_back(item) — вставка нового элемента в конец;
pop_back() — удаление последнего элемента;
push_front(item) — вставка нового элемента в начало;
pop_front() — удаление первого элемента;
size() — количество элементов в деке.
##### Описание, принцип работы
Deque (double ended queue, «очередь с двумя концами»)
Реализуется на основе двусвязного списка.


## Как определить свой вариант:

<Номер в списке в таблице ЯП СКБ22*> mod 3

*Пожалуйста, внимательно проверяйте свой вариант, выполнение не своего варианта не принимается!*
