Question: 1
Question: 
Consider the Question 7 in last homework, your algorithm may cost O(n^2) time complexity. Now you have the knowledge of dictionary(a datastructure that you can find
an element in O(1) time), please improve you algorithm with only O(n) time complexity.

Solution:
?

Question: 2
Question:
Since dictionary can store data and search elements in O(1) time, why do we need list? What is the disadvantages of dictionary?(hint: search the hashtable 
disadvantages or hashtable conflict in google )

Solution: 
due to the possibility that collitions might occur in hash tables, it is better to store data that has values that reoccur in lists than in the hash table

Question: 3
Question:
Write a Python script to concatenate following dictionaries to create a new one. If two dictionaries have the same key, sum the value of them in the new dictionary.

Sample Dictionary :
dic1={1:10, 2:20}
dic2={3:30, 4:40}
dic3={5:50,6:60}

Solution:

dic1[3] = 30
dic1[4] = 40
dic1[5] = 50
dic1[6] = 60

Question 4:
Question:
Write a Python script to generate and print a dictionary that contains a number (between 1 and 10) in the form (key=x, value=x*x)

x = 1
while x > 1
    y = x ** 2
    Squares[x] = y
    x = x + 1
    
Question: 5
Question:
Given a signed 32-bit integer x, return x with its digits reversed.(assume x = 124314141578)

#example
a = 390
reverse(a) = 93
b = 123
reverse(b) = 321

Solution:



Question: 6
Question:
Question 6
Write a function to invert a dictionary. It should accept a dictionary as a parameter and return a dictionary where the keys are values from the input dictionary 
and the values are lists of keys from the input dictionary. For example, this input:

{ "key1" : "value1", "key2" : "value2", "key3" : "value1" }
should return

{ "value1" : ["key1", "key3"], "value2" : ["key2"] }
