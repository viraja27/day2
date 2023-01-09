# day2
list=[]
for num in range(1,21):
    list.append(num)
    print(num)
print(sum(list))
list1=[]
for number in range(1,1000001):
    list1.append(number)
print(sum(list1))    
print(min(list1))
print(max(list1))
list2=[]
for i in range(1,21,2):
    list2.append(i)
print(list2)
list3=[]
for j in range(3,31,3):
    list3.append(j)
print(list3)    
list4=[]
for k in range(1,11):
    list4.append(k**3)
print(list4)    
list5=[l**3 for l in range(1,11)]
print(list5)
