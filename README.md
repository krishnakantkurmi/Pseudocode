# Pseudocode
// add two numbers 
START
   INPUT a
   INPUT b
   sum = a + b
   PRINT sum
END

// even odd check 
START
   INPUT number
   IF number % 2 == 0 THEN
       PRINT "Even"
   ELSE
       PRINT "Odd"
END

// loop 1 to 5 print 

START
   FOR i = 1 TO 5
       PRINT i
   END FOR
END

// maximum of two number

START
   INPUT a
   INPUT b

   IF a > b THEN
       PRINT a
   ELSE
       PRINT b
END
// array basic pseducode 

START
   INPUT n
   INPUT array[0 to n-1]

   FOR i = 0 TO n-1
       PRINT array[i]
   END FOR
END

// palindrome string 

START
   INPUT string
   reversed = ""

   FOR i = length(string)-1 TO 0
       reversed = reversed + string[i]

   IF string == reversed THEN
       PRINT "Palindrome"
   ELSE
       PRINT "Not Palindrome"
END



Conditional Statements (if-else)

Pseudocode
IF number > 0
    PRINT "Positive"
END IF

code == 
public class IfExample {
    public static void main(String[] args) {
        int number = 5;

        if (number > 0) {
            System.out.println("Positive");
        }
    }
}

IF - ELSE

 Pseudocode== 
IF number > 0
    PRINT "Positive"
ELSE
    PRINT "Negative"
END IF
code ==
public class IfElseExample {
    public static void main(String[] args) {
        int number = -3;

        if (number > 0) {
            System.out.println("Positive");
        } else {
            System.out.println("Negative");
        }
    }
}

Pseudocode
IF number > 0
    PRINT "Positive"
ELSE IF number == 0
    PRINT "Zero"
ELSE
    PRINT "Negative"
END IF

code == 
public class IfElseIfExample {
    public static void main(String[] args) {
        int number = 0;

        if (number > 0) {
            System.out.println("Positive");
        } else if (number == 0) {
            System.out.println("Zero");
        } else {
            System.out.println("Negative");
        }
    }
}

