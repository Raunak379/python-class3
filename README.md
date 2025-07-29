# python-class3
#conversion
#condition 1
num1 = 6
print(num1, 'is of type', type(num1))
num2 = 9.42
print(num2, 'is of type', type(num2))
num3 = 4+2j
print(num3, 'is of type', type(num3))



#condition 2
#int to float
"""number1 = 6
number2 = 4.2
print(number1 + number2)"""



#condition 3
"""number1 = float(input("entred the number1 "))
number2 = float(input("entered the number2 "))
sum = number1 + number2
print(sum)"""



#condition 4
"""number1 = int(4.6)
print(number1)  
number2 = int(-4.2)
print(number2) 
number3 = float(19)
print(number3) 
number4 = complex('6+3j')
print(number4)  """



# list

#condition 1
#int list
"""number = [1, 2, 3, -6]
print(number)"""


#mixed list
"""number = [2.3, 'hello', -5]"""


#empty list
"""list = []"""


#len = how many base index
'''number = [1,2,3,-4]
print(len(number))'''
#check base 
"""language = ["hindi","english","bhojpuri"]
print(language [2])"""
#change the items of the list
"""language = ["python", "c++", "c"]
language[1:2 ]=["java", "html"]
print(language)"""
#how to check any query perfom present or not
"""language = ["html", "java", "c++", "python", "c"]
print("python" in language )
print("x" in language)"""
#how to print list of element one by one
"""subject = ["hindi","english","science","maths","computer","sanskrit"]
for subject in subject:
    print(subject)"""
#how to add in list
"""subject =["hindi", "english", "math"]
subject.append("science")
print(subject)"""
#how insert at given position in list
"""subject =["hindi", "english", "math"]
subject.insert(1,"science")
print(subject)"""
#how to remove in list
"""subject =["hindi", "english", "math"]
subject.remove("math")
print(subject)"""
#tupels
#how to print tupels
"""number = [4,3,5,-6]
print(number[1])"""
#condition 2
"""number = [4,3,5,-6]
print(number[1:3])"""
#how to print line by line
"""number = [4,3,5,-6]
for number in number:
    print(number)"""
#diffence between list and tupels
"""list can be change and tuples can not be change"""
#sets
# sets = repeat value print ones time
"""numbers = {2, 4, 6, 6, 2, 8}
print(numbers) """ 
#add iteam in sets
"""numbers = {21, 34, 54, 12}
print('Initial Set:',numbers)
numbers.add(32)
print('Updated Set:', numbers)  """
#union of the sets
"""A = {1, 3, 5}
B = {0, 2, 4}
print('Union using |:', A | B)"""
#sets intersection
"""A = {1, 3, 5}
B = {1, 2, 3}
print('Intersection using &:', A & B)#type1
print('intersection using intersection():', A.intersection(B))#type2"""
#difference between two sets(a-b)
"""A = {2, 3, 5}
B = {1, 2, 6}
print('Difference using &:', A - B)
print('Difference using difference():', A.difference(B))"""
#symmetric sets
"""A = {2, 3, 5}
B = {1, 2, 6}
print('using ^:', A ^ B)
print('using symmetric_difference():', A.symmetric_difference(B)) """
#Dictionary
#create dictionary
"""country_capitals = {
  "Germany": "Berlin", 
  "Canada": "Ottawa", 
  "England": "London"
}
print(country_capitals)
print(country_capitals["England"])"""
#condition 2
"""person = {"name": "raunak", "age": 21}
print(person.get("course",["BCA", "section A"]))"""
#how to change the any query
"""person = {"name": "raunak", "age": 21}
person["name"] = "sher"
print(person)"""
#how to add any quers
"""person = {"name": "raunak", "age": 21}
person["course"] = ["bca" , "section A"]
print(person)"""
#how to remove any query
"""person = {"name": "raunak", "age": 21}
print(person.pop("name"))"""
#how to check key
"""person = {"name": "raunak", "age": 21}
for key in person:
    print(key)"""
