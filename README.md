# Java_01
public class Dz1 {
    public static void main(String[] args) {
    }

    /**
     * step 2
     * Создать переменные всех пройденных типов данных, и инициализировать их значения;
     */
    static void task2() {
        byte b = 127;
        short st = 12419;
        char ch = 'A';
        int integer = 24;
        long lg = 124124L;
        float fl = 12.345949f;
        double dl = 4323.45345;
        boolean bool = true;
    }

    /**
     * step 3
     * Написать метод вычисляющий выражение a * (b + (c / d)) и возвращающий результат,
     * где a, b, c, d – входные параметры этого метода;
     */
    static double calc(double a, double b, double c, double d) {
        return a * (b + (c / d));
    }

    /**
     * step 4
     * Написать метод, принимающий на вход два числа, и проверяющий что их сумма лежит в
     * пределах от 10 до 20(включительно), если да – вернуть true, в противном случае – false;
     */
    static boolean range(int one, int two) {
        int sum = one + two;
        return sum > 9 && sum < 21;
    }

    /**
     * step 5
     * Написать метод, которому в качестве параметра передается целое число, метод должен
     * напечатать в консоль положительное ли число передали, или отрицательное;
     * Замечание: ноль считаем положительным числом
     */
    static void printPositiveOrNegative(int num) {
        String word = "Положительное";
        if (num < 0) word = "Отрицательное";

        System.out.println(word);
    }

    /**
     * step 6
     * Написать метод, которому в качестве параметра передается целое число, метод должен
     * вернуть true, если число отрицательное;
     */
    static boolean isNegative(int num) {
        return num < 0;
    }

    /**
     * step 7
     * Написать метод, которому в качестве параметра передается строка, обозначающая имя,
     * метод должен вывести в консоль сообщение «Привет, указанное_имя!»;
     */
    static void sayHello(String name) {
        System.out.printf("Привет, %s!\n", name);
    }

