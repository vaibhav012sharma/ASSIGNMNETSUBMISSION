Q1- EXPLAIN THE FEATURES OF PYTHON THAT MAKE IT A POPULAR CHOICE FOR PROGRAMMING
--------------------------------------------------------------------------------


SOLUTION 1


 * PYTHON IS SIMPLE AND EASY FOR  LEARNING TO BEGINEERS ,PYTHON SYNTAX IS EASY COMPARE TO OTHER DIFFERENT PROGRAMMMING LANGUAGES

* PYTHON HAVE A LOT OF(RICH) LIBRARIES WHICH UESD EASILY LIKE AS (NUMPY WE CAN USE  such as import numpy as np  ) and ALSO USE ALL BUILT -IN FUNCTION INSIDE LIBRARIES 
 
* PYTHON IS A PLATFORM INDEPNDENT LANGUAGE WHICH CAN BE USED ON ANY DIFFERENT SYSTEMS 

*  PYTHON IS VERSATIBLE PROGRAMMING LANGUAGE WHICH CAN WE USE MANY FIELS SUCH AS DATA INDUSTRY ,  WEB DEVELOPMENT , MACHINE LEARNING , DATA ANALYST etc

* PYTHON IS FREE AND OPEN SOURCE ,IT'S SOURCE CODE IS ALSO AVAILABLE 

* PYHTON HAS A LARGE AND ACTIVE COMMUNITY (PROGRAMMERS ARE CONTRIBUTING)

* PYTHON SUPPORT GUI(GRAPHICL USER AND INTERFACES )

Q2- ROLE OF PREDIFENED KEYWORDS AND PROVIDE EXAMPLES ,HOW THEY ARE USED IN THE PROGRAM
--------------------------------------------------------------------------------------

SOLUTION 2 


 PRDEFINED KEYWORDS - IN PYTHON PREDEFINED KEYWORDS WHICH MEANS RESERVED KEYWORDS .

* PREDEFIED KEYWORDS WHICH MEANS A KEYWORD THAT HOLD  SOME MEANING IN PYTHON LANGUAGE AND CAN NOT BE USED TO DEFINE A VARIABLE NAME/ CAN NOT BE USED TO WRITE A IDENTIFIER (variabe name ,fuction name etc)

* example  if , else, while, for, import , class, try, switch ,FALSE ,continue  , break , lambda  etc

* PREDEFINED KEYWORDS ROLE TO DEFINE THE SYNTAX AND STRUCTURE OF LANGUAGE 

*  WE CAN USED IN THE PROGRAM TO DEFINE THE NAME OF PREDEFINED KEYWORD like  if , else , class

.. code:: ipython3

    #program  write a program to print the even number  
     
    num =int(input("enter a number"))
    for i in range(num):
        if i % 2 !=0:
            continue
        print(i)
    

Q3 MUTUABLE AND IMMUTUABLE OBJECTS
----------------------------------

SOLUTION 3

*MUTUABLE OBJECTS -- 
		 *objects/container where  value can be changed after cretaed are know as mutuale objects 
		* in other simple words which means changeable 
		* example list , dictionary etc


.. code:: ipython3

      #write a program  check a list is mutubale 
    a = [1, 2, 3, "ram", True]       		   # modify  ram to shyam
    a[3] = "shyam"
    print(a)
    
                                            #o/p [1,2,3,"shyam",True]              		list is mutubale 

 *IMMUTUABLE OBJECTS --
			* objects/container where  value can not  be changed after cretaed are know as immutuale objects 
			* in other simple words which means unchangeable 
			* example string , tuple etc

.. code:: ipython3

    # write  a program  make  a  string and perform is this string is mutuable or immutuable 
    
    a = "pwskills"           # modify p to a 
    a[0] = 'a'
    print(a)             
                            #o/p error  str not support item assignment

::

   ## COMPARE  MUTUABLE AND IMMUTUABLE OBJECTS

 MUTUABLE                         		                  |                IMMMUTUABLE 

*mutuable which means changeable 		                  |  immutuable which means unchangeable 

*objects can be changed after creation 			         |  objects can not be changed after creation 

*slower to access compare to immutuable objects          |  quicker  to access compare to mutuable objects 

*generally provide a method to add or remove elements    | it does not provide the method to add or remove elements 

* eg - string , tuple					                  |eg - list , dictionary 

Q4 DIFFERENT TYPES OF OPERATOR
==============================

SOLUTION 4 


A  OPERATOR - A OPERATOR IS A SPECIAL SYMBOL WHICH IS USED TO PERFORM THE OPERATION B/W THE OPERANDS or to perform the operation on the values.

PYTHON ALLOW MULTIPLE TYPE OF OPERATORS: 

	1) ARITHMETIC OPERATOR
	2) ASSIGNMENT OPERATOR
	3) LOGIC OPERATOR
	4) COMPARIOSN OPERATOR
	5) BITWISE OPERATOR
	6) MEMBERSHIP OPERATOR
	7) IDENTITY OPERATOR


 * ARITHMETIC OPERATOR    			 
			 Operator name         			 Symbol name 
			
			ADDITION 				            +
			SUBTRACTION 				        -
			DIVISION 				            /
			MULTIPLICATION  			        *
			MODULOS		       			        %
			FLOOR DIVISION  			       //
			EXPONENTIATION 	       			   **
			
*ASSIGNMENT OPERATOR 

			ADDITION OR EQUAL TO   			   +=
			SUBTRACTION OR EQUAL TO			   -=
			DIVISION OR EQUAL TO			   /=
			MULTIPLICATION OR EQUAL TO  	   *=
			MODULOS	OR EQUAL TO	       		   %=


*LOGICAL  OPERATOR 
			LOGICAL AND 				      and
			LOGICAL OR 				           or
			LOGICAL NOT 				       not


*COMPARIOSN OPERATOR 
			lesser than 				       <
			greater than				       >
			less than or equal to			   <=
			greater than or eual to 		   >=
			assignment operator 			   ==
			not equal to 				       !=


*Membership operaotor
			in  -- it is used some members you are looking available in memory data container like string or list 

*BITWISE OPERATOR
			BITWISWE AND 				      &
			BITWISE OR				          |
			BITWISE XOR  				      ^
			BITWISE NEGATION/TILT			  ~
			LEFT SHIFT 				          <<
			RIGHT SHIFT				          >>

* IDENTITY OPERATOR 

			is -- it is used to compare the memory adress of two varibles 


.. code:: ipython3

    # WRITE A PROGRAM  USED MEMBERSHIP OPERATOR in string help of membership operator 
    				
    a = "pwskills"
    if 'p' in a :
        print("yes")
    else:
    	print("no")
    
    
    #WRITE A PROGRAM  USE IDENTITY OPERATOR 
    
    a = 2
    b = 20
    if a is b:
        print("yes")
    else:
    	print("no")
    
    
    # WAP USE ARITHMEETIC OPERATOR 
    p = 10
    l= 1.3
    print(p+l)   
    
    
    #wap use  Bitwise AND  operator 
    
    s=25
    o=3
    x=s&o
    f=s|o
    j=s^o
    print(x)
    print(f)
    print(j)
    print(~o)
                    
                #o/p 1
                #o/p  27 
                #o /p 26
                #o /p -4
    

QUESTION 5 TYPE CASTING
=======================

SOLUTION 

*Type casting is also known as type conversion .

*When we convert one data type to another data type  is known as type casting 
 
*WHY we use type casting ?
      --we use typecasting for data mismatch 


* Types of  type casting -
 				There are two types of type casting 
				1) IMPLICIT CONVERSION ---	automtically done by the compiler 
				2) EXPLICIT CONVERSION ---	manually done by the compiler using built in function known as explicit conversion 


.. code:: ipython3

    # WRITE A PROGRAM  USED MEMBERSHIP OPERATOR in string help of membership operator 
    				
    a = "pwskills"
    if 'p' in a :
        print("yes")
    else:
    	print("no")
    
    
    #WRITE A PROGRAM  USE IDENTITY OPERATOR 
    
    a = 2
    b = 20
    if a is b:
        print("yes")
    else:
    	print("no")
    
    
    # WAP USE ARITHMEETIC OPERATOR 
    p = 10
    l= 1.3
    print(p+l)   
    
    
    #wap use  Bitwise AND  operator 
    
    s=25
    o=3
    x=s&o
    f=s|o
    j=s^o
    print(x)
    print(f)
    print(j)
    print(~o)
                    
                #o/p 1
                #o/p 27
                #o/p 26
                #o /p -4

QUESTION 5 TYPE CASTING
=======================

SOLUTION 

*Type casting is also known as type conversion .

*When we convert one data type to another data type  is known as type casting 
 
*WHY we use type casting ?
      --we use typecasting for data mismatch 


* Types of  type casting -
 				There are two types of type casting 
				1) IMPLICIT CONVERSION ---	automtically done by the compiler 
				2) EXPLICIT CONVERSION ---	manually done by the compiler using built in function known as explicit conversion 


.. code:: ipython3

                #   WRITE A PROGRAM OF IMPLICIT TYPE CASTING 
    
    a = 10
    b= 1.3
    print(a+b)                             #convert one data type to another data type without help of inbuit function 
    
    
    
    
    
    
            #WRITE A PROGRAM OF EXPLICIT TYPE CASTING 
    
    c = int(input("enter a no "))                      #use buit -in funtion 
    if c ==2:
        print("yes")
    else:
    	print("no")

QUESTION 6 CONDITIONAL STATEMENTS
=================================

SOLUTION 6 

* STATEMENT -- FUNDAMENTAL BLOCK OF CODE 

* There are lot of statements in python like expression statement, assignment statement, conditional statement ,loop statement

*CONDITIONAL STATMENT --- it is used when we decide a work do or not (eg if i complete work then go , else not go )

* There a 4 types of conditional statement -
 					1) if condition 
					2) if -else condiion
					3) if -elif -else condition
					4) nested if -else conition 

.. code:: ipython3

    #WAP  print even no USE IF STATEMENT 
    a =int(input("enter no"))
    for i in range(0,a):
        if i % 2 !=0:
            continue
        print("even no is ",i)
    
    
    		
                		 #WAP CHECK day IS RAINY OR NOT USE IF ELSE CONDITION STATEMENT 
    day = input("enter the day ")
    if day == "rainy":
        print("DAY IS RAINY")
    else:
        print("DAY IS NOT RAINY ")
    
    
    
    
    
    
                    #WAP TO MAKE A CALCULATOR USING If ELIF ELSE
    b =int(input("enter no"))
    c =int(input("enter no"))
    char = input("enter a symbol")
    if char=="+":
        print("add is :",b+c)
    elif char=="-":
    	print("sub is :",b-c)
    elif char=="*":
    	print("mul is :",b*c)
    elif char=="/":
    	print("div is :",b/c)
    else:
    	print("INVALID CHARACTER")   
    
    
    
    
    
                            #WAP MAKE A WEB PAGE LOGIC USE NESTED if -else
    	
    name=input("enter a name ")
    email=input("enter a email")
    password=input("enter a pass")
    if name =="":
        print(" AGAIN FILLED NAME")
    else:
    	if "@" not in email:
            print(" NOT ENTERED EMAIL:")
    	else:
    		if len(password)<=0:
                print("ENTER AGAIN PASSWORD")
    		else:
    			print("REGISTRATION IS SUCCESSFULLY ")
        

QUESTION 7 LOOPS
================

SOLUTION 7

* LOOP which is used to print the statement repeatedly /again - again .
* There are two types of statemet --
				1) for loop 
				2) while loop

1) for loop -- it is used to  iterate over a sequence of element 
	* it is also used when dev eloper  know the stop  condition
	* its syntax is very easy 
	* syntax     for variable_name  in string/list:




 range()- it is used when we generate a sequence of elements , we can use range() in for loop 
		
SYNTAX 			for variable_name in range (start, stop, step):




 for else 
   * it is same behave as for loop but include else 
    * else part only execute when loop terminate automatically without use break statement 





2) while loop ---- it is used when  developer not know the stop condition 
* syntax ---   while condition:
						#statement
						#increment/decrement


while else 
 * it is same behave as while loop  but include else 
* else part only execute when loop terminate automatically without use break statement 

.. code:: ipython3

    # WAP ITERATE ALL ELEMENTS IN STRING  use for loop 
    
    e = "pwskills"
    for i in e:
        print(i,end=" ")
        
                						     #o/p   p w s k i l l s
    
    #WAP generate 2 table help of for loop 
    			
    for i in range(1,11):
        print(f"{2} *{i} = {i}")     # use also format strings ( f strings is used to place the variable in b/w the strings ,  f string  is introduced in 3.6  version python 
    
    
    
    #WAP USE FOR ELSE  PRINT 2 TABLE 
    for i in range(1,11):
        print(f"{2}*{i} ={i}")
    else:
        print("done")

.. code:: ipython3

    #WAP  PRINT A * RIGHT TRIANGLE    use while loop 
    			
    i=1
    while i<=4:
        j=1
    	while j<=i:
            print("*",end="")
    		j=j+1
    	print()
    	i=i+1
    
    
    
    # WAP USE WHILE ELSE 
    h=1
    while h<=11:
        print(f"{1}*{h} = {h}")
        h=h+1
    else:
        print("done")

