#tuples and sets
#tuples ()  = not able to change it's immutable non flexible
things=("fan","cooler","Ac","switch","cupboard","clothes","fan","fan",)
print(things)
print(len(things))
print(type(things))
print(things[0])
print(things.count("fan"))
print(things[::2])
print(things[1:4])
print((things) *2 )
print("fan" in things)
print("eye"not in things)
print("giraffe" in things)

#concatenation
num1=(1,34,87,67)
num2=(23,45,56)
num=(num1+num2)
print(num)
sorted_num=sorted(num1)
print(sorted_num)
#nested tuple,
s=((1,2,3),(23,45,65),(54,49,21,34),(90,80,62))
print(s[0][1])
print(s[2][3])

#sets  {} =  unindexing, unordered, unique
s={}     #dict
print(type(s))
s=(())   #tuple
print(type(s))
s=set()  #set
print(type(s))
s=[""]  #list
print(type(s)) 

#union=| 
#intersection =  &
#difference = -
s1= {"mom", "dad","brother","sister","aunty","uncle","wifeyy"}
s2 ={"grandmaa","grandpaa","grandson","mom","dad","husband","wifeyy"}

print(s1)
print(s1|s2)
print(s1&s2)
print(s1-s2)
s1.pop()
print(s1)
s2.discard("husband")
print(s2)
s1,s2. clear()
print(s1,s2)

i=set()
print(type(i))
i=(())
print(type(i))
i={}
print(type(i))
