# Общие знания
Объясните, что делает этот код

```Java
((n & (n – 1)) == 0)
```
Объясните, зачем может использоваться этот код
```Java
b |= c
a |= c
```


# SQL
1. Что такое и зачем используется первичный ключ
2. Что такое транзакции и как они работают
3. Дана таблица
| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | 

# GIT

# Java

### Basics
Что такое модификатор доступа protected

### Collections
Разница между Array и ArrayList

### Strings
1 Назовите разницу в инициализации
```Java
String s1 = "Test";
String s2 = new String("Test");
```

2 Почему строка - это хороший ключ для HashMap

### Streams
```Java
public static void main(String[] args) {
        List<Integer> integers = Arrays.asList(1, 2, 3, 4, 5, 6, 7, 8);
        int increment = 0;
        integers.stream()
                .filter(i -> i > 4)
                .forEach(i -> ++increment);
        System.out.println(increment);
    }
```