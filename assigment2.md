# Q1   DATA STRUCTURE   & WHY THE IMP ?
 
Answer 
DATA STRUCTUE - are specialised format for organising , storing and accessing collections of data 
IMPORTANCE Of Data Structure
* optimize sorting and searching operations 
* simplify data manipulation
* choosing the right data structure significant impact the efficeny and performance of our program 
* conserve memory usuage

 # Q2   MUTUABLE AND IMMUTUABLE DATA TYPES 
Answer-
MUTUABLE			
* means changeable           
*Objects can  be changed after creation   	 
*slower access data compared to immutuable 
*eg - list,set,dictionary      

 IMMUTUABLE 
* means unchangeable
*Objects can not be changed after creation
* quick access data compare to mutuable
* eg -string,tuple

# Q3   DIFFERNCE B/W LIST AND TUPLES
Answer-
LIST
*list defined by [].				
*list is mutubale which means we can add, remove and modify data easily 
*USECASE- list are VERSATILE for sorting and managing collections							
*we can altered in data using variety of techniques like( insert(),remove(),del,pop(),append() )
*we can use list comprehension  		
* In flipkart we can add new items,remove items and change quantities		


Tuple 
*tuple is defined by ()
*tuple is immutuable which means we can not add add,removeand modify data 
*USECASE- tuples are use for representing the fixed	datasets(once data is stored in tuple so data is fixed in tuple,we can not modify the data)
*we can not altered data 
*In tuple does not has comprehension 



# Q4  HOW DICTIONARY STORED DATA ?
Answer-
*dictionary store data in key value pairs ,dictionary is defined by {} 
eg a={1:"hii"}
* In dictionary not access items by using indexing or slicing.
*we can access values in dictionary  by using keys not vice versa (we can nit access keys by using values).
*syntax of dictionary   --    {keys:values}  

*here keys can be defined as string ,numbers(int,float),boalean value and tuple data structure
and values can be defined as as string ,numbers(int,float),boalean value and list,tuple,sets and also dictionary data structure

when we create and store items in dictionary ,In memory block create a memory space for specific dictionary and values of dictionary stored in memory in ordered way
each keys is point to the our values 

# program access a value in dictionary 

eg a={1:"hii",2:{"companyname":"pwskills","faculty":"i get best faculty "} }
   a[2]["faculty"]

 # Q5  using set instead of list in python?

Answer
* if i want to get uniques items(no duplicate items) and does not matter order so we can use set data structure  ,while list data structure is useful to add new data and remove data  also modify the data 
* set are useful for check membersip (if items in set) and finding the intersection/union  b/w the two set operation 
* list are versatile for sorting and managing collections .
*set is mutubale and make immutubale use frozen set while list is  only mutuable 
* if we want to fixed unique item in set  so we use frozenset.
* frozen set is immutubale version of set where can not be add, remove and modify data ,while list does not fixed data as like frozn set 
eg 
a={1,2,3,4,1}
a.update([1,2,5])
a.add("hi")
print(a)


#using frozenset
b=frozenset({1,2,3})
print(b)


# Q6 STRING IN PYTHON AND HOW IT IS DIFFERENT FROM LIST 

Answer-
* string is  a data structure in python , string is a ordered colllection of characters encosed by single quotes'',double quotes"",triple quotes """ .
* string is immutubale we can not add data  ,remove data and modify one by one data but we can use replace function to replace the substring of the strings 
* string is ordered collection of elements we can access elements by using indexing number and also use slicing to iterate the elements 
*string are use to represent and manipulates the textual data 
eg
a="pwskills"
print(a[0])
print(a.replace('p','s'))
print(a.upper())
print(a.capitalize)


*list is also data structure ,store hetrogenous data in list (any data types stored in list )
* list  is ordered collections of data each data separed by , containing in [] ( list defined by [] )
*list is mutuable we can add , remove and modify data by using variety of techniques like ( insert,append,extend,remove,pop,del,sort)
*eg  bag contain any type of books 
* also list elements access by using indexing and slicing to iterate the elements similar to the string 
eg 
a=[1,2,3]
b=["hii"]
a.append(True)
a.insert(4,{1,2,3})
a.extend(b)
print(a)


# Q7 How tuple  ensure  data integrity in python ?


Answer
 * data integity ensure the data is accurate and consistent 
* only tuple data structure ensure the data integrity in python ---
* tuple are useful for  represent the fixed data .
* Once data is stored in tuple so we can not change/modified  the data (bcz tuple is immutable we can not add , remove and modify data ) 
* tuple is ordered collection of items and data is accessed by using indexing and slicing 
* tuple also allow duplicates data 

  # Q9 CAN list contain different data types in python ?

ANS YES list store hetrogenous data .Q10  Explain why strings are immutable in Python

Ans bcz in string we can not add data , remove data and not modify data one by one that's why string is immutuable Ans 
*dictionary faster access data compare to  list 
 * dictionary is used to store complex data  and heirachial data where information organised into multiple values 

 # Q12 Describe a scenario where using a tuple would be preferable over a list?

Answer
* if you want  to  create  a data  and after create ,you will want a data can not be change   so preferable tuple data structure 
* but list data structure can not represent the fixed datasets list are useful for sorting and managing collections 

# Q13  How do sets handle duplicate values in Python?
Answer 
 * Sets can not allow  dupicate values bcz set is unordered collections of unique items
* sets is mutuable we can add ,remove data by using variety of techniques like(add, update,pop,remove,discard) but can not be modified value in sets  
* if i give duplicate value in sets  , sets does not give duplicate values
eg a={1,2,True,1}
print(a)

 # Q14 How does the “in” keyword work differently for lists and dictionaries?

A14   in keyword is membership operator ,which used to find some member you are looking available in data structure .

use in operator  list data structure 
* in operator one by one iterate  elements in list  and together  check specified element present in list if present give  true otherwise return false
eg 
a=[1,2,3,4,5,"hhiiii",True,(1,2,3)]
print("hlw" in a)

use in operator dictionary data structure 
* in operator one by one iterate only keys in dictionary  and check together specified element is  key or not if present give true otherwise return false
* why keys check bcz keys is unique but values is repetale(duplicate) that's why we can not check values in dictionary  
eg
a={1:"hiii", True:"hlw" , (1,2,3):{"name":"abhay","age":"12"}}
# i want to check 4 is present as key names in dictionary or not  
print(4 in a)

# Q15  Can you modify the elements of a tuple? Explain why or why not?
Answer
 NO bcz tuple is immutuable so we can not add, remove and modify data in tuple (only read and access data by using index and slicing)
 
 # Q16 NESTED DICTIONARY , GIVE EXAMPLE AND USE CASES

Answer-
 Nested Dictionary - when we create dictionary inside dictionary this approach known as nested dictionary.
ex 
a={"EMP1":{"name":"abhay","companyname":"pwskill","salary":"50,000"},
   "EMP2":{"name":"aditya","companyname":"pwskill","salary":"60,000"},
   "EMP3":{"name":"aryan","companyname":"pwskill","salary":"90,000"}
}
print(a["EMP2"]["salary"])
			#o/p 60,000

use cases of nested dictionary  - 
*nested dictionary is used for reperesent complex and heirarchial data (data organising in way of tree like -structure)where information is organised into multiple levels 
eg  store employees data by department  so we can use nested dictionary  

# Q17 TIME COMPLEXITY OF ACCESSING ELEMNTS IN DICTIONARY ?

Answer O(1)

# Q18 In what situations are lists preferred over dictionaries?
Answer
* for ordered collections of items  and sequencing operations like( append, insert,extend,pop,remove,del)
* list act as stack and queue

 # Q20 differnce b/w list and dictionary in data retrieval 
Answer
data retrieval  it is a process to finding ,copying or moving the information from the system
DIFF B/W LIST AND DICTIONARY 
LIST 							
*list access data using index and slicing 	  	
*list find specified  data by using find() also we	
can use in operator 
*in list store hetrogenous data  			
*in list we can use shell copy and deep copy concept	


DICTIONARY 
* dictionary access data using keys 
* dictionary find keys by using keys() or find specified key use in operator. 
* dictionary data store in key value pairs ( where key is unique and we can create duplicate values)
* dictionary we can not use shell concept but use deep concept 

                           #  Practical Questions   
                           



```python
#Q1 Write a code to create a string with your name and print it
a="vaibhav"
print(a)                                         
```

    vaibhav
    


```python
#Q2 Write a code to find the length of the string "Hello World"
print(len("Hello World"))
```


```python
#Q3 Write a code to slice the first 3 characters from the string "Python Programming
print("Python Programming"[:3])
```


```python
#Q4 P Write a code to convert the string "hello" to uppercase
print("hello".upper())
```


```python
#Q5  Write a code to replace the word "apple" with "orange" in the string "I like apple
 print("I like apple".replace("apple","orange"))
```


```python
#Q6 Write a code to create a list with numbers 1 to 5 and print it
 a=[ i for i in range(1,6)]
print(a
```


```python
#Q7 Write a code to append the number 10 to the list [1, 2, 3, 4]
a=[1,2,3,4]
a.append(10)
print(a)
```


```python
#Q8 Write a code to remove the number 3 from the list [1, 2, 3, 4, 5]
a=[1,2,3,4,5]
a.remove(3)
print(a)
```


```python
#Q9 Write a code to access the second element in the list ['a', 'b', 'c', 'd']
a= ['a', 'b', 'c', 'd']
print(a[1])
```


```python
#Q10 Write a code to reverse the list [10, 20, 30, 40, 50]
a=[10,20,30,40,50]
print(a[:-1])

```


```python
#Q11 Write a code to create a tuple with the elements 100, 200, 300 and print it
a=(100,200,300)
print(a)

```


```python
#Q12. Write a code to access the second-to-last element of the tuple ('red', 'green', 'blue', 'yellow')
a=('red', 'green', 'blue', 'yellow')
print(a[1:4]
```


```python
#Q13. Write a code to find the minimum number in the tuple (10, 20, 5, 15)
a=(10, 20, 5, 15)
print(min(a))
```


```python
#Q14. Write a code to find the index of the element "cat" in the tuple ('dog', 'cat', 'rabbit')
a=('dog', 'cat', 'rabbit')
print(a.index('cat'))
```


```python
#Q15. Write a code to create a tuple containing three different fruits and check if "kiwi" is in it
a=("pineapple","kiwi","orange")
print("kiwi" in a )
```


```python

#Q16. Write a code to create a set with the elements 'a', 'b', 'c' and print it
a={'a', 'b', 'c'}
```


```python
#Q17. Write a code to clear all elements from the set {1, 2, 3, 4, 5}.
a={1, 2, 3, 4, 5}
a.clear()
print(a)
```


```python
# Q18. Write a code to remove the element 4 from the set {1, 2, 3, 4}
a={1, 2, 3, 4}
a.discard(4)
print(a)
```


```python
#Q19. Write a code to find the union of two sets {1, 2, 3} and {3, 4, 5}
a= {1, 2, 3}
b={3, 4, 5}
print(a | b )
```


```python
#Q20. Write a code to find the intersection of two sets {1, 2, 3} and {2, 3, 4}
a={1, 2, 3}
b={2, 3, 4}
print(a & b )
```


```python
#21. Write a code to create a dictionary with the keys "name", "age", and "city", and print it
a={"name":"aswinisir","age":27,"city":"Bengaluru"}
print(a)
```


```python
#22. Write a code to add a new key-value pair "country": "USA" to the dictionary {'name': 'John', 'age': 25}
a={'name': 'John', 'age': 25}
a.update({"country": "USA"})
print(a)
```


```python
#23. Write a code to access the value associated with the key "name" in the dictionary {'name': 'Alice', 'age': 30}
a={'name': 'Alice', 'age': 30}
print(a.get('name'))
```


```python
#24. Write a code to remove the key "age" from the dictionary {'name': 'Bob', 'age': 22, 'city': 'New York'}
a={'name': 'Bob', 'age': 22, 'city': 'New York'}
a.pop('age')
print(a)
```


```python
#25. Write a code to check if the key "city" exists in the dictionary {'name': 'Alice', 'city': 'Paris'}
a={'name':'Alice','city':'Paris'}
print("city" in a )
```


```python
# 26. Write a code to create a list, a tuple, and a dictionary, and print them all
a=[]
b=()
c={}
print(a)
print(b)
print(c)

```


```python
# 27. Write a code to create a list of 5 random numbers between 1 and 100, sort it in ascending order, and print the
result (replaced)
a=[10,23,20,45,67]
a.sort()
print(a)
```


```python
#28. Write a code to create a list with strings and print the element at the third index
a=["kismat k","bare m sochunga","to manjil","bura manjayengi"]
print(a[3])
```


```python
# 29. Write a code to combine two dictionaries into one and print the result
a={1:"hi"}
b={2:"hlw"}
a.update(b)
print(a)

```


```python
# 30. Write a code to convert a list of strings into a set
a=["hi","hlw"]
b=set(a)
print(b)
```
