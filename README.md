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
