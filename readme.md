1) Формируем массив из консоли с помощью функции GetarrayFromString
2) Описание функции GetarrayFromString: 
2.1) Функция принимает строку из консоли
2.2) Формируем массив разделяя пробелами, с помощью функции StringSplitOptions.RemoveEmptyEntries удалем пустые элементы массива
2.3) Создаем массив с количеством элементов, которые были указаны в строке
2.4) В цикле for заполняем массив
2.5) Возвращаем массив result
3) Отображаю массив array
4) Формирую итоговый массив с поомщью функци CheckElements, в котором будут лежать все элементы, которые удовлетворяют условию задачи
5) Описание функции CheckElements:
5.1) Функция принемает готовый массив
5.2) С помощью цикла for считает количество элементов удовлетворяющих условию задачи
5.3) Формируем новый масив, в который положим элементы удовлетворяющие условию задачи
5.4) С помощью второго цикла for заполняем новый массив элементами удовлетворяющими условю задачи
6) Отображаем массив answerarray