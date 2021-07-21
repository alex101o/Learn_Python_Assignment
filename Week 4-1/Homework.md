Question 1
Question:
Given a string of Integer as input, please write a function return the int value of the input string;

a = "123"
string_to_int(a) = 123
a = "0123" 
string_to_int(a) = 123
a = "+123"
string_to_int(a) = 123
a = "-123"
string_to_int(a) = -123

Solution:

def string_to_int(a):
    b = int(a)
    print(b)
    print(type(b))

a = "-0111"
string_to_int(a)

Question 2
Question:
Write a Python function that takes a list and returns a new list with unique elements of the first list.

Sample List : [1,2,3,3,3,3,4,5]
Unique List : [1, 2, 3, 4, 5]

Solution:

Sample = [1,2,3,3,3,3,4,5]
def thing(a):
    s = []
    y = 0
    z = 1
    while y < len(a):
        
        while z < len(a):
            k = 0
            if a[y] == a[z]:
                k = k + 1
            else:
                print("test")
            z = z + 1
            
        if k >= 1:
            y = y + 1
        else:
            s.append(a[y])
    print(s)

thing(Sample)




Question 3:
Question:
Write a Python function that checks whether a passed string is palindrome or not(a palindrome is a string which equals to its reversed string).

a = "a"
chech_palindrome(a) = True
a = "abc"
chech_palindrome(a) = False
a = "cabac"
chech_palindrome(a) = True

Solution:
def chech_palindrome(a):
    z = len(a) - 1
    b = ""
    while z >=  0:
        b = b  +  a[z]
        z = z - 1
    if b == a:
        return True
    else:
        return False

a = "tacocat"

print(chech_palindrome(a))

Question 4
Question:
Write a Python function to find the majority number of a list.

Given an array nums of size n, return the majority element.

The majority element is the element that appears more than [n / 2] times. You may assume that the majority element always exists in the array.

l = [3,2,3]
majority(a) = 3
nums = [2,2,1,1,1,2,2]
majority(a) = 2


Solution:
def majority(a):
    y = 0
    z = 1
    test = 0
    while y < len(a):
        
        while z < len(a):
            k = 0
            if a[y] == a[z]:
                k = k + 1
            z = z + 1
        
            if k > len(a) / 2:
                print(a[y])
            

l = [3,2,3]
print(majority(l))
nums = [2,2,1,1,1,2,2]
print(majority(nums))
