- 1. 

Which of these statements are true?
The are 2 correct answers

All classes must explicitly define a constructor.
x A constructor can be declared private.
A constructor can declare a return value.
A constructor must initialize all the member variables of a class.
x A constructor can access the non-static members of a class.


__________________________________________________
- 2. 

What will happen when the following program is compiled and run?

public class SM

{

   public String checkIt(String s)

   {

      if(s.length() == 0 || s == null)

      {

          return “EMPTY”;

      }

      else return “NOT EMPTY”;

   }

    

    public static void main(String[] args)

    {

      SM a = new SM();

      a.checkIt(null);

    }

   

}

The are 1 correct answers

It will print EMPTY.
It will print NOT EMPTY.
x It will throw NullPointerException.
It will print EMPTY if || is replaced with |.


_____________________________________________________

- 3. 

Which of the following statements concerning the switch construct are true?
The are 3 correct answers

- x A character literal can be used as a value for a case label.

x A ‘long’ cannot be used as a switch variable.

x An empty switch block is a valid construct.

A switch block must have a default label.

If present, the default label must be the last of all the labels.



_____________________________________________________
- 4. 
What will the following statement print?

int marks = 90;

String exam = “OCJA”;

System.out.printf(“I scored %d marks in the %s exam!”,  exam, marks );

The are 1 correct answers

I scored 90 marks in the Java Foundations exam!
I scored OCAJF marks in the 90 exam!
x Exception will be thrown at run time.
Compilation error

__________________________________________________
- 5. 

Which of the following expressions correctly implement the following equation:
y = 10x² + 20x + 30

Assume that all variables are of type ints.

The are 2 correct answers

y = 10**x + 20*x + 30;
- [x] y = x*(10*x + 20) + 30;
y = 10*x^2 + 20*x +20;
- [x] y = 10*x*x + 20*x + 30;
y = 10*x** + 20*x + 30;




___________________________________________________-
6 / 45

Which of the following features are provided by the JDK?
The are 2 correct answers

x A Java Runtime Environment (JRE).
Machine learning
x API for Java SE Standard
Database engine
Integration libraries





___________________________________________________

7 / 45
What will the following program print?
public class TestClass

{

  static int someInt = 10;

  public static void changeIt(int a)

  {

    a = 20;

  }

  public static void main(String[] args)

  {

    changeIt(someInt);

    System.out.println(someInt);

  }

}

The are 1 correct answers

x 10
20
It will not compile.
It will throw an exception at runtime.
None of the above.







___________________________________________________

8 / 45


Which of the following four constructs are valid….

1)

switch(5){
default:

}

2)

switch(5){
default: break;

}

3)

switch(8);

4)

int x = 0;
switch(x){}


1, 3
1, 2, 3
All are valid.
3, 4
x 1, 2, 4.




___________________________________________________
9 / 45
Consider the following code snippet:

for(int i=INT1; i<INT2; i++)

{

System.out.println(i);

}

where, INT1 and INT2 can be any two integers.

Which of the following will produce the same result?

The are 1 correct answers

for(int i=INT1; i<INT2; System.out.println(++i));

for(int i=INT1; i++<INT2; System.out.println(i));

int i=INT1; while(i++<INT2) { System.out.println(i); }

- [x] int i=INT1; do { System.out.println(i); }while(i++<INT2);
None of these.





___________________________________________________

10 / 45
Which of the following are valid operators in Java?
The are 3 correct answers
x !
!!
x &&
x %=
$



___________________________________________________
11 / 45
What will the following program print?

public class TestClass {

public static void main(String[] args) {
unsigned byte b = 0;
b−−;
System.out.println(b);
}
}

 

The are 1 correct answers
0
-1
255
-128
x It will not compile.

___________________________________________________
12 / 45
What will the following code print when run?

public class Mambo {

static int m = 10, n = 20;

public static void main(String args[]){

int m = 0, n = 10;

Mambo mb = new Mambo();

while(m<3) {

m++; n−−;

}

System.out.println(m+”, “+n);

}

}

The are 1 correct answers
10, 20
9, 19
- [x]  3, 7
None of these.




___________________________________________________


13 / 45
What is the result of executing the following code when the value of i is 5:

switch (i)

{

    default:

    case 1:

        System.out.println(1);

    case 0:

        System.out.println(0);

    case 2:

        System.out.println(2);

        break;

    case 3:

        System.out.println(3);

}

The are 1 correct answers

- [x] It will print 1 0 2
It will print 1 0 2 3
It will print 1 0
It will print 1
Nothing will be printed.




___________________________________________________
14 / 45
What will the following statement print?
System.out.printf(“This is %s %s”, “what”, “it”, “is”);

The are 1 correct answers

- [x] This is what it
This is it is
Exception will be thrown at run time because the number of arguments and the number of format specifiers in the input string do not match.
Compilation failure





___________________________________________________

15 / 45
What is the effect of compiling and running this class ?

public class TestClass

{

public static void main (String args [])

{

int sum = 0;

for (int i = 0, j = 10; sum > 20; ++i, −−j)      // 1

{

sum = sum+ i + j;

}

System.out.println(“Sum = ” + sum);

}

}

The are 1 correct answers
Compile time error at line 1.
- [x] It will print Sum = 0
It will print Sum = 20
Runtime error.
None of the above.



___________________________________________________

16 / 45
Which of the following correctly declare a variable which can hold an array of 10 integers?
The are 2 correct answers

- [x] int[ ] iA
int[10] iA
- [x] int iA[ ]
Object[ ] iA
Object[10] iA







___________________________________________________

17 / 45
Given:
package strings;

public class StringFromChar {

    

    public static void main(String[] args) {

        String myStr = “good”;

        char[] myCharArr = {‘g’, ‘o’, ‘o’, ‘d’ };

        

        String newStr = null;

        for(char ch : myCharArr){

            newStr = newStr + ch;

        }

        System.out.println((newStr == myStr)+ ” ” + (newStr.equals(myStr)));

        

    }

}

What will it print when compiled and run?

The are 1 correct answers

true true
true false
false true
- [x] false false







___________________________________________________

18 / 45
What is the result of executing the following fragment of code:

boolean b1 = false;

boolean b2  = false;

if (b2 = b1 == false)

{

   System.out.println(“true”);

} else

{

   System.out.println(“false”);

}

The are 1 correct answers

Compile time error.
- [x] It will print true;
It will print false;
Runtime error.
It will print nothing.- 







___________________________________________________

19 / 45
What will the following code print?
The are 1 correct answers

public class BreakTest {

public static void main(String[] args) {

int i = 0, j = 5;

lab1:
for (; ; i++) {

for (; ; -- j) {
if (i> j) {
break lab1;

}

}

}

System.out.println(" i="+i+",j ="+ j);

}

}

i = 1, j = -1
i = 1, j = 4
i = 0, j = 4
x i = 0, j = -1
It will not compile.






___________________________________________________



20 / 45
You are writing a class that represents the equation of a straight line:
y = mx + c;

This class has only one method named calcY that takes the value of x and returns the value of y.

Which variable scopes will you use to store the values of m and c in an instance of this class?

The are 1 correct answers

global variables
static variables
x instance variables
local variables







___________________________________________________

21 / 45
Given:
int a = 5,  b = 2, c = 30;

System.out.println( a−− * c / b  );

What is the result?

The are 1 correct answers
50
60
x 75
0
Compilation failure
Exception at run time










___________________________________________________


22 / 45
Given the following declaration, select the correct way to get the size of the array, assuming that the array has been initialized.

int[] intArr;

The are 1 correct answers

intArr[ ].length( )
x intArr.length( )
intArr.length
intArr[ ].size( )
intArr.size( )







___________________________________________________

23 / 45
Java ME can be used to develop applications for:
The are 1 correct answers

Desktop applications that can handle human interaction.
x Embedded applications for Raspberry Pi.
Personalized applications for smart phones.
Back end/server side.




___________________________________________________


24 / 45
Which of the following is correct about Java byte code?
The are 1 correct answers

It can run on any OS and chip architecture.
- [x] It can run on any OS and chip architecture if there is a JRE available for that OS and chip architecture.
It can run on any OS and chip architecture if that platform has a JRE built for it and the Java code was compiled ON that platform.
It can run on any OS and chip architecture if that platform has a JRE built for it and the Java code was compiled FOR that platform.

___________________________________________________

25 / 45
What will be the result of attempting to compile and run the following class?

public class TestClass

{

    public static void main(String args[ ] )

    {

       int i = 1;

       int[] iArr = {1};

       incr(i) ;

       incr(iArr) ;

       System.out.println( “i = ” + i + ”  iArr[0] = ” + iArr [ 0 ] ) ;

    }

    public static void incr(int   n ) { n++ ; }

    public static void incr(int[ ] n ) { n [0]++ ; }

}

The are 1 correct answers

The code will print i = 1 iArr[0] = 1
- [x] The code will print i = 1 iArr[0] = 2
The code will print i = 2 iArr[0] = 1
The code will print i = 2 iArr[0] = 2
The code will not compile.



___________________________________________________
26 / 45
While compiling a java file you want the compiler to generate the class file in a particular directory. Which javac option will you use?
The are 1 correct answers

-dest
x -d
-target
-output



___________________________________________________

27 / 45
Which line will print the string “MUM”?
public class TestClass

{

   public static void main(String args [])

   {

        String s = “MINIMUM”;

        System.out.println(s.substring(4, 7)); //1

        System.out.println(s.substring(5)); //2

        System.out.println(s.substring(s.indexOf(‘I’, 3))); //3

        System.out.println(s.substring(s.indexOf(‘I’, 4))); //4

     }

}

The are 1 correct answers

- [x] 1 
2
3
4
None of these.


___________________________________________________

28 / 45
Consider the following program :

class Test

{

  public static void main(String[] args)

  {

    short s = 10; // 1

    char c = s; // 2

    s = c; // 3

  }

}

Identify the correct statements.

The are 2 correct answers

x Line 3 is not valid.
x Line 2 is not valid.
It will compile because both short and char can hold 10.
None of the lines 1, 2 and 3 is valid.



___________________________________________________

Which of these assignments are valid?
The are 3 correct answers

x short s = 12 ;
x long g = 012 ;
int i = (int) false;
x float f = -123 ;
float d = 0 * 1.5 ;


___________________________________________________
30 / 45
What will the following code print?

  int i = 0;

  int j = 1;

  if( (i++ == 0) && (j++ == 2) )

  {

     i = 12;

  }

  System.out.println(i+” “+j);

The are 1 correct answers

x 1 2
2 3
12 2
12 1
It will not compile.


___________________________________________________
31 / 45
Given the following line of code:
   List students = new ArrayList();

Identify the correct statement:

The are 1 correct answers

x The reference type is List and the object type is ArrayList.
The reference type is ArrayList and the object type is ArrayList.
The reference type is ArrayList and the object type is List.
The reference type is List and the object type is List.




___________________________________________________
32 / 45
Given the code fragment:

        int[] balances1 = new int[]{ 10, 20 };

        int[] balances2 = { 100 };

        balances2 = balances1;

        System.out.print(balances1.length+” “+balances2.length);

What is the result?

The are 1 correct answers

2 1
x 2 2
1 2
1 1
Exception at run time.


___________________________________________________

33 / 45
Consider the following method…

public int setVar(int a, int b, float c) {

//valid code not shown

}

Which of the following methods correctly overload the above method ?

The are 2 correct answers
- [x]  public int setVar(int a, float b, int c)
{
  return setVar(a, c, b);
}
public int setVar(int a, float b, int c)
{
  return this(a, c, b);
}
public int setVar(int x, int y, float z)
{
  return x+y;
}
public float setVar(int a, int b, float c)
{
  return c*a;
}
- [x] public float setVar(int a)
{
  return a;
}


___________________________________________________

34 / 45
What will be the output of the following lines ?

System.out.println(“” +5 + 6);   //1

System.out.println(5 + “” +6);   // 2

System.out.println(5 + 6 +””);   // 3

System.out.println(5 + 6);       // 4

The are 1 correct answers

x 56, 56, 11, 11
11, 56, 11, 11
56, 56, 56, 11
56, 56, 56, 56
56, 56, 11, 56


___________________________________________________

35 / 45
Which of these expressions will obtain the substring “456” from a string defined by String str = “01234567”?
The are 1 correct answers

x str.substring(4, 7)
str.substring(4)
str.substring(3, 6)
str.substring(4, 6)
str.substring(4, 3)

___________________________________________________
36 / 45
Which of the following are reserved words in Java?
The are 2 correct answers

- [x] goto
x package
export
array
hash


___________________________________________________
37 / 45
What will be the result of attempting to compile the following program?

public class TestClass

{

   long l1;

   public void TestClass(long pLong) { l1 = pLong ; }  //1

   public static void main(String args[])

   {

      TestClass a, b ;

      a = new TestClass();  //2

      b = new TestClass(5);  //3

   }

}

    

The are 1 correct answers

A compilation error will be encountered at //1, since constructors should not specify a return value.
A compilation error will be encountered at //2, since the class does not have a default constructor.
x A compilation error will be encountered at //3.
The program will compile correctly.
It will not compile because parameter type of the constructor is different than the type of value passed to it.


___________________________________________________

38 / 45
Given:

String s1 = “Hello”;

String s2 = “World”;

//1

Which of the following options are valid when inserted independently at the line marked //1?

The are 3 correct answers

x s1 += s2;
s1 -= s2;
x System.out.println( s1 = s2 );
x System.out.println( s1 == s2);






___________________________________________________

39 / 45
Consider the following method, which is called with an argument of 7:

public void method1(int i)

{

int j = (i*30 – 2)/100;

POINT1 : for(;j<10; j++)

{

boolean flag  = false;

while(!flag)

{

if(Math.random()>0.5) break POINT1;

}

}

while(j>0)

{

System.out.println(j−−);

if(j == 4) break POINT1;

}

}

What will it print?

The are 1 correct answers
It will print 1 and 2
It will print 1 to N where N is a random number.
x It will not compile.
It will throw an exception at runtime.

___________________________________________________


40 / 45
Given the code fragment:

        int[] balances1 = new int[]{ 10, 20 };

        int[] balances2 = balances1;

        balances1 = new int[]{ 100 };

        System.out.print(balances1 == balances2);

What is the result?

Note: You will see real exam questions written in the same format. The question, “what is the result” implies “what is the result of compilation and execution of the given code” assuming that it exists in a valid context such as a class. It does not mean that the code will compile as it is or that it does not have compilation issues.

The are 1 correct answers

true
x false
 compilation failure
exception at run time

___________________________________________________

41 / 45
What will the following code print when run without any arguments …

public class TestClass {

    public static int m1(int i)

    {

        return ++i;

    }

    

    public static void main(String[] args) {

        int k = m1(args.length);

        k += 3 + ++k;

        System.out.println(k);

    }

}

The are 1 correct answers

It will throw ArrayIndexOutOfBoundsException.
 It will throw  NullPointerException.
x 6
5
7
2
None of these.



___________________________________________________

42 / 45
What will be printed when the following code snippet is executed?

String str = “123456789”;

str.substring(2, 5);

System.out.println(str.charAt(2));

The are 1 correct answers

x 3
 4
5
This will not compile.



___________________________________________________

43 / 45
You have been given a library that contains the following class:

package com.cool;

public class Cooler {

  public void doCool(){

    System.out.println(“cooling…”);

  }

}

Now, you are writing another class that makes use of the above library as follows:


// 1 insert code here

public class Furnace

{

  public void cool(Cooler c) { // 2

    c.doCool();

  }

}

What should be inserted at //1 above?

The are 2 correct answers

package com.cool;
import package com.cool;
x import com.cool.*;
import com.cool;
import class com.cool.Cooler;
x import com.cool.Cooler;



___________________________________________________

44 / 45
Which of the following are correct about “encapsulation”?
The are 2 correct answers

Encapsulation is same as polymorphism.

- [x] It helps make sure that clients have no accidental dependence on the choice of representation

- [x] It helps avoiding name clashes as internal variables are not visible outside.

Encapsulation makes sure that messages are sent to the right object at run time.

Encapsulation helps you inherit the properties of another class.

___________________________________________________

45 / 45
Which of the following are features of Java?
The are 2 correct answers

x It is strongly typed
It offers direct memory management.
x It allows multithreaded programming.
It is a distributed lanaguage.