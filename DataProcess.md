
Great notest to adopt:
https://github.com/khakhalin/notes/blob/85f45fe8d6fe53ddd2e0e631e5ea76b09b44256a/00_queue_to_do.md

-Send to Refael and Lior goldman and from my phone

***************

Data Engineering wiki(ALL you can imagine and more): https://dataengineering.wiki/Guides/Guides

Formal Great document for every db or data storage there is:https://dataengineering.wiki/Tools/Programming+Languages/Python


Great great get started:https://dataengineering.wiki/Guides/Getting+Started+With+Data+Engineering
************************

All Python (let's start) :
-------------


Python Basics:

1.Explain the “is” operator in Python. How does “is” differ from “==”?
The is operator in Python checks whether two variables point to the same object, while == checks if the values of two variables are the same.

We can apply this to sample data. Consider the following:

= [2,4,6] = [2,4,6] = b

Here is how this data would evaluate under the “is” and “==” operators:

a == b

This would evaluate true since the listed values in a and b are the same.

a is b

This would evaluate false since a and b are different objects.

2. How would you remove duplicates within a list in Python?
One technique would be to convert a list into a set because sets do not contain duplicate data. Then you would convert the set back into a list.

Here is an example with data:

list1 = [3,6,7,9,2,3,7,1]
list2 = list(set(list1))
The resulting list2 would contain [3,6,7,9,2,1]. However, it is also important to remember that sets may not maintain the order of the list.


3.
9. How do you rename columns using Pandas?
In order to rename columns, you can use the rename() function. This can be used to rename any column in a dataframe. For example, if in the customers table, you wanted to rename the column “user_id_number” to “user_id” and the “customer_phone” to “phone,” you would write:

customers.rename(columns=dict(user_id_number="user_id", customer_phone="phone"


4.What is faster for lookups in Python: dictionaries or lists?



** Very imporatn go over all this!
**How Python works inside:
GIL
Asyncio
Multithreading
Subinterpreters

********

All Data engineering (let's start):
---------------
 




