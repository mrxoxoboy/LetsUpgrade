# Assignment 1

# 1) Five List in built functions

lst = [1,2,"a","Ayush","200",33.6,-13,"23.78","Hello",["Hey","Man"],98]
lst

#Appending an element to the end of the list
lst.append(46)
lst

#Count the number of element occurs in the list
list1 = ('a',1,45,"e",1,7,5)
list1.count(1)

lst

#Find the index value from the list
lst.index("Ayush")

lst

#Remove the item at the given index from the list
lst.pop(4)

lst

#reverse the list
lst.reverse()
print(lst)

# 2) Five built-in Dictionary Element

dict1 = {"name":"robert","age":"26","job":"Engineer","Location":"London"}
dict1

#print the all keys from the Dictionary
print(dict1.keys())

#returns copy of a dictionary
dict2 = dict1.copy()
dict2

#Print all the values of Keys
dict1.values()

#Update the dictionary with some element
d = {1:"One",2:"TOO"}
d1 = {2:"Two"}
d.update(d1)
d

dict2

#Popitem remove the last element
pop = dict2.popitem()
print("Popped item :",pop)
print("Dictionary :",dict2)

