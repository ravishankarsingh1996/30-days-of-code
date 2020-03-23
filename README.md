# 30-days-of-code


#Day 1
#TODO Get all keywords in Python

import keyword
print("1. Python Keyword")
print(keyword.kwlist, "\n")

print("Total keyword count in python is: ", len(keyword.kwlist))


####################################################################################################################

#Yield keyword
print("\n\n2. Yield keyword")
## generator function
def yieldFunction():
    for i in range(10):
        yield(i)
    

#print 
print("Yeild generator function output:")
for x in yieldFunction():
    
    print(x)

####################################################################################################################

#Python Statement
print("\n\n3. Python Statement")

print("\nNew Line Character")
a = 1 + 23 + \
    21 + 2 + \
    9

print("Output:",a,"")


print("\nLine Continuation Character")
a = (1 + 23 + 
    21 + 2 + 
    9)

print("Output:",a,"")

print("\nMultiple statement in single line using ';'")
a = 20; b = 21; c = 12; print(a,""); print(b+c,"")
