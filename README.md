# Method-Overloading-

Overloading

// Method overloading problem:

class Code {

    public int m1(int a, int b) {

        System.out.println("concatenation of a and b is: " + a + b);

        return a + b;

    }

    public float m1(float a, float b) {

        System.out.println("concatenation of c,d and f is: " + a+b);

        return a+b;

    }

    //Same signature of method with different data types is allowed, it is the method overloading concept

    public static void main(String... args) {

        System.out.println("Welcome to java programming");

        Code cc = new Code();

        cc.m1(1, 2);

        cc.m1(1,  3);

    }

}

/*

Welcome to java programming

concatenation of a and b is: 12

concatenation of a and b is: 13

 */
