Question: 1
Question: Given a list l = [12, 35, 9, 54, 24], write a Python program to swap the first and last element of the list

l = [12, 35, 9, 56, 24]

a = l[0]

b = l[4]

a
12

b
24

l[0] = b

l[4] = a

l
[24, 35, 9, 56, 12]



Question: 2
Question: Given a list l = [12, 35, 9, 56, 24,79,62,32,31,100]
Part 1: Find the smallest and the largest elements of the list.

min(l)
9

max(l)
100


Part 2: Find the largest 2 elements of the list.


max(l)
100

l.remove(max(l))

max(l)
79


Part 3: Sort the list in-place and not in-place respectively.





Sort the list from 9(index 2) to 62 (index 6) and remian unchanged for other part of the list.

l[2:6] = sorted(l[2;6])


Question: 3
Question:
Since father's day is coming, I will give you a list of gift candidates.
gift_list=['socks', '4K drone', 'wine', 'jam']

Part 1: Please add your gift candidates to this gift_list using append() or extend().


gift_list.append("cup")


Part 2: Please remove the gifts that you dislike in the gift_list using pop() or remove().

gift_list.pop()


Question: 4
Part 1:
Question: Assume l = [1,8,90,70,1000,10,300,82,90], write a python program to sum up this list.

sum(l)

Part 2:
Question: Write a python program to multiply all the elements in previous list l.

l = [1,8,90,70,1000,10,300,82,90]

x = [0,1,2,3,4,5,6,7,8]

y = 1

for z in x[1:9]:
    y = l[z] * y

y
1115856000000000

Part 3: 
Question: Write a python program to sum up all the even number between 0-1000

x = 0

y = 0

while x < 1000:
    x = x + 2
    y = y + x
    
y
250500

Question: 4
l = ["a","c","d","a","kk","k","c","stu","ta","she","kk","kk","d","g"]

Part 1: Count unique value of the list


Part 2: Write a Python program to remove duplicates(retain only one) from list


l = ["a","c","d","a","kk","k","c","stu","ta","she","kk","kk","d","g"]

x = [0,1,2,3,4,5,6,7,8,9,10,11,12,13]

y = 1

a = 0

for z in x[0:14-a]:
     y = z + 1
     while y <= 13-a:
         if l[z] == l[y]:
              l.remove(l[y])
              a = a + 1
         else:
              y = y + 1
              
Question: 5
Question: Given a List, extract all elements whose frequency is greater than K.

l = [4, 6, 4, 3, 3, 4, 3, 4, 3, 8]
a = 0
x = 0
while x <= 9-a:
    if K < l[x]:
        l.remove(l[x])
        a = a + 1
    else:
        x = x + 1
 
 Question: 6
 Question:
 Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.

You may assume that each input would have exactly one solution, and you may not use the same element twice.

a = [2,3,11,15,20,18,7,12]
x = []
b = 9
y = 0
z = 0
while z < 7:
    while y < 7:
        if a[y] + a[z] == b:
            x.append(a[y])
            x.append(a[z])
            y = y + 1
        elif a[y] - a[z] == b:
            x.append(a[y])
            x.append(a[z])
            y = y + 1
        elif a[y] * a[z] == b:
            x.append(a[y])
            x.append(a[z])
            y = y + 1
        elif a[y] / a[z] == b:
            x.append(a[y])
            x.append(a[z])
            y = y + 1
    z = z + 1
 

