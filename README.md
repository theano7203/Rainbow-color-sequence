# Rainbow-color-sequence
Statement-Python 3 code that creates a list of items using a for loop to loop"X" times where x is the number of items on the list making a python rainbow along with variations of that code
rainbow = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']
for x in rainbow:
    print(x)
for x in range(len(rainbow)):
    print('Color Sequence of Rainbow:', rainbow[x])
my_iterator = iter(rainbow)
print(my_iterator)
print(next(my_iterator))
print(next(my_iterator))
print(next(my_iterator))
print(next(my_iterator))
print(next(my_iterator))
print(next(my_iterator))
print(next(my_iterator))


#Puts in a space for easier read
rainbow = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']
for char in rainbow:
    print(char, end=' ')
    print("\n")


#has brackets for dropping into another piece of code
rainbow = ['red', 'orange', 'yellow', 'green', 'blue', 'indigo', 'violet']
# for char in rainbow:
#     print(char, end=' ')
#     print("\n")
#
number = 1
for colors in rainbow:
    print(number, rainbow)
    number = number + 1
    print("\n")
#
# vertical rainbow text
string = "red orange yellow green blue indigo violet"
for char in string:
    print(char)

#Using string and for and then value with an end to turn it horizontal
string = "red orange yellow green blue indigo violet"
for char in string:
    print(char)

for value in string:
    print(value, end='')


