# JavaCode:
Java adalah satu set perangkat lunak komputer dan spesifikasi yang dikembangkan oleh Sun Microsystems, yang kemudian diakuisisi oleh Oracle Corporation, yang menyediakan sistem untuk mengembangkan aplikasi perangkat lunak dan menerapkan hal itu dalam sebuah cross-platform lingkungan komputasi.
*Contoh dasar:*
+ **Menapilkan Teks Pada Java**
```java
public class MyClass {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```
> Hasilnya:
Hello World
+ **Menuliskan Komentar**
```java
public class MyClass {
  public static void main(String[] args) {
    System.out.println("Hello World"); // This is a comment
  }
}
```
> Hasilnya:
Hello World
+ **Menggunakan Variabel**
```java
public class MyClass {
  public static void main(String[] args) {
    String firstName = "Love ";
    String lastName = "You ";
    String fullName = firstName + lastName;
    System.out.println(fullName); 
  }
}
```
> Hasilnya:
Love You
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
```java
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
> Hasilnya:
true
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
+ **Menggunakan While Loop**
```java
public class MyClass {
public static void main(String[] args) {
int i = 0;
while (i < 5) {
System.out.println(i);
i++;
}
}
}
```
> Hasilnya:
0
1
2
3
4
+ **Menggunakan Break**
```java
public class MyClass {
public static void main(String[] args) {
for (int i = 0; i < 10; i++) {
if (i == 4) {
break;
}
System.out.println(i);
}
}
}
```
> Hasilnya:
0
1
2
3
+ **Menggunakan Array**
```java
public class MyClass {
public static void main(String[] args) {
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
cars[0] = "Opel";
System.out.println(cars[0]);
}
}
```
> Hasilnya:
Opel
+ **Menggunakan Method**
```java
public class MyClass {
static void myMethod() {
System.out.println("I just got executed!");
}

public static void main(String[] args) {
myMethod();
myMethod();
myMethod();
}
}
```
> Hsilnya:
I just got executed!
+ **Menggunakan Class / Object**
```java
public class MyClass {
int x = 5;
public static void main(String[] args) {

MyClass myObj = new MyClass();
System.out.println(myObj.x);
}
}
```
> Hsilnya:
5
+ **Menggunakan Class Atribut**
```java
public class MyClass {
int x;

public static void main(String[] args) {
MyClass myObj = new MyClass();
myObj.x = 40;
System.out.println(myObj.x);
}
}
```
> Hsilnya:
40
+ **Menggunakan Class Method**
```java
public class MyClass {
static void myMethod() {
System.out.println("Hello World!");
}

public static void main(String[] args) {
myMethod();
}
}
```
> Hsilnya:
Hello World !
+ **Menggunakan Constructors
```java
// Create a MyClass class
public class MyClass {
int x;

// Create a class constructor for the MyClass class
public MyClass() {
x = 5;
}

public static void main(String[] args) {
MyClass myObj = new MyClass();
System.out.println(myObj.x);
}
}
```
> Hasilnya:
5
# Penutup:
Itulah Contoh Pemrograman Java Dasar yang bisa kamu pelajari secara lebih lanjut. Semoga bermanfaat dan jangan lupa tekan Bintang ★ Start
