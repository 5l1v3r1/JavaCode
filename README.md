# JavaCode:
Java adalah satu set perangkat lunak komputer dan spesifikasi yang dikembangkan oleh Sun Microsystems, yang kemudian diakuisisi oleh Oracle Corporation, yang menyediakan sistem untuk mengembangkan aplikasi perangkat lunak dan menerapkan hal itu dalam sebuah cross-platform lingkungan komputasi.
*Contoh sederhana:*
+ **Menapilkan Teks Pada Java**
```java
public class MyClass {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
> Hasilnya: Hello World
+ **Menuliskan Komentar**
```java
public class MyClass {
  public static void main(String[] args) {
    System.out.println("Hello World"); // This is a comment
  }
}
```

> Hasilnya: Hello World
+ **Menggunakan Variabel**
```java
public class MyClass {
  public static void main(String[] args) {
    String firstName = "Cinta ";
    String lastName = "Kamu ";
    String fullName = firstName + lastName;
    System.out.println(fullName); 
  }
}
```
> Hasilnya ```Cinta Kamu```
+ **Menggunakan Tipe Data**
```java
public class MyClass {
  public static void main(String[] args) {
    int myNum = 5;               // integer (whole number)
    float myFloatNum = 5.99f;    // floating point number
    char myLetter = 'D';         // character
    boolean myBool = true;       // boolean
    String myText = "Hello";     // String   
    System.out.println(myNum);
    System.out.println(myFloatNum);
    System.out.println(myLetter);
    System.out.println(myBool);
    System.out.println(myText);
  }
}
```
> Hasilnya:
5
5.99
D
true
Hello
+ **Menggunakan Operator**
```java
public class MyClass {
  public static void main(String[] args) {
    int sum1 = 100 + 50;
    int sum2 = sum1 + 250;
    int sum3 = sum2 + sum2;
    System.out.println(sum1);
    System.out.println(sum2);
    System.out.println(sum3); 
  }
}
```
> Hasilnya:
150
400
800
+ **Menggunakan String**
```jav
public class MyClass {
public static void main(String[] args) {
String txt = "Hello World";
System.out.println(txt.toUpperCase());
System.out.println(txt.toLowerCase());
}
}
```
> Hsilnya:
HELLO WORLD
hello world
+ **Menggunakan Boolean**
```java
public class MyClass {
public static void main(String[] args) {
int x = 10;
int y = 9;
System.out.println(x > y); // returns true, because 10 is higher than 9
}
}
```
> Hasilnya
tru
+ **Menggunakan IF dan Else**
```java
public class MyClass {
public static void main(String[] args) {
if (20 > 18) {
System.out.println("20 is greater than 18"); // obviously
}
}
}
```
> Hasilnya:
20 is greater than 18
