# Изучить материал

* https://learn.javascript.ru/prototype
* https://learn.javascript.ru/new-prototype
* https://learn.javascript.ru/native-prototypes
* https://learn.javascript.ru/classes

# Практика

1) Создать 4-х уровневый калькулятор
<br />
* 1ый уровень самый главный. 
Будет иметь метод render(x), который отобразит текущее значение переменной х.
Будет иметь метод clear(x), очищает значение переменной на 0.
<br />
* 2ой уровень наследует 1ый
<br />
Будет иметь методы на основные математические операции, но в квадрате.
Методы Sum, Div, Mul,  которые получают 2 числа и выполняют операцию, и возвращают результат в квадрате.
Например Sum(2, 5) -> (2+5)^2=49
<br />
* 3ий уровень наследует 2ой
<br />
Будет свойство-массив arr, в котором генерируются случайные числа от 0 до 50. Длина массива arr.length = 200;
Тут будет метод reInit(arr), который переопределяет массив arr
<br />
* 4ий уровень наследует 3ий
<br />
Пустой
<br />
* Экземпляры создаются от 4 уровня

## <hr />

2) Создать класс SuperMath. Добавить к экземпляру метод - check(obj), параметр obj которого имеет свойства X, Y, znak. Метод должен подтвердить у пользователя хочет ли он произвести действие znak c Х и У. Если -да, сделать мат действие znak(которое описано в прототипе), иначе - запросить ввод новых данных через метод input() класса SuperMath.
Пример обекта: `obj = { X:12, Y:3, znak: “/”}`, возможные варианты znak=>  `+ - / * %`.
При вводе znak нужно сделать проверку корректности ввода на возможные математические действия
