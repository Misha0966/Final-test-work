Итоговая проверочная работа.

1. Создать репозиторий на GitHub
2. Нарисовать блок-смеху алгоритма( можно обойтись блок-схемой основной содержательной части, если вы выделяете её в
отдельный метод)
3. Снабдить репозиторий оформленным текстовым описанием решения (файл README.md)
4. Написать программу, решающую поставленную задачу.
5. Использовать контроль версий в работе над этим небольшим проектом( Не должно быть такого что все залито одним коммитом,
как минимум этапы 2, 3 и 4 должны быть расположены в разных коммитах) 

Задача: Написать программу, которая из имеющегося строк массива формирует массив из строк, длина которых меньше
либо равна 3 символа. Первечный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма.

При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Примеры :

["hello", "2", "word", ":-)"] ->["2", ":-)"]
["1234", "1567", "-2", "computer science"]->["-2"]
["Russia","Denmark", "Kazan"] -> [] 

Описание решения:

1. Создать новый строковый массив, задать количество элементов;
2. Создать метод для заполнения массива – ввод через клавиатуру;
3. Вывести созданный массив на экран;
4. Создать метод для сортировки массива в зависимости от длины содержащихся в нем строк (<=3);
5. Вывести на экран отсортированный массив.
