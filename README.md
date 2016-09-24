# Core-Java
Core java Notes

#Language Fundamentals

1. identifier
2. reserved words
3. datatypes
4. literals
5. arrays
6. types of variables
7. var args methods
8. main method
9. commandline arguments
10.   java coding standards

class Test{
public static void main(String[] args){
int x =10;
}
}

#Rules for Java identifiers
#1.The only allowed characters in Java idendifiers
   are A-Z, a-z, 0-9, $,and _. if we're using any
   other character we'll get compile time error.
   Example:
   total_number
   total# //invalid
#2 identifier can't starts with digit.
   Example:
   total123
   123total //invalid
#3 Java identifiers are case sentive. Of course Java
   language itself treated as case senstive programming
   language.
   Example
    class Test{
     }
#4 There is no length limit for java identifiers.But it is
   not recommended to take too lengthy identifiers.

#5 We can't use reserved words as identifiers
   int x=10;
   int if=10;// invalid
#6 All predefined java class name and interfaces names we
   can use as identifiers
   Example
  class Test{
    public static void manin(String[] args){
    }
   
  }

   Even though it is valid but it is not a good programming
   practice because it reduces readability and create confusion.


#Q which of the following are valid java identifiers?
   toatl_number
   total#
   123total
   total123



# Reserved words

* in java some words are reserved to represent some meaning or
  functionality. Such types of words are called Reserved words.
