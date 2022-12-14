## Tasks:

#### 1) Basic variable initialization.

Create 3 int variables with names: first, second, third. Initialize them with
values: 1, 10, 100. Make console outputs for all of them, each on new line. Implement the program inside of given code
snippet:

    public class BasicVariablesInitialization {
        public static void main(String[] args) {
             int first, second, third;
             first = 1;
             second = 10;
             third = 100;
             System.out.println(first);
             System.out.println(second);
             System.out.println(third);
        }
    }

#### 2) One-line variable declaration and initialization.

Declare 3 int variables within one statement and call them a, b, c (order must be followed). Initialize them in one
statement with value "10". Print to console "c". Implement the program inside of given code snippet:

    public class DeclaringVars {
       public static void main(String[] args) {
            int a, b, c;
            a=b=c=1;
            System.out.println(c);
       }
    }

#### 3) Reassigning references.

Declare another 3 variables: first, second, third (1,10,100). Make console output of 3
initial vars (first, second, third) each on new line. Initialize vars linkToFirst, linkToSecond, linkToThird with the
variables first, second, third. Reassign (first, second, third) with the : 15, 6, 4. And write to console all the
variables (in the order they were declared), each on a new line. Pay attention to results.
Implement the program inside of given code snippet:

    public class ReassigningValues {
       public static void main(String[] args) {
            int first=1;
            int second = 10;
            int third = 100;
            System.out.println(first);
            System.out.println(second);
            System.out.println(third);
            int linkToFirst = 15;
            int linkToSecond = 6;
            int linkToThird = 4;
            first = linkToFirst;
            second = linkToSecond;
            third = linkToThird;
            System.out.println(first);
            System.out.println(second);
            System.out.println(third);
            System.out.println(linkToFirst);
            System.out.println(linkToSecond);
            System.out.println(linkToThird);
       }
    }
