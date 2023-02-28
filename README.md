# program-to-count-no.-of-zeros-and-ones-in-python

Date 17/09/2022  (BIrth day kalyan ;❤️❤️❤️❤️❤️)Have Sln Blessings

1.)
program to count no of Consecutive zeros in a binaray Number


n = 5
n = 13
s1 = bin(5)
s2 = bin(13)
s1 = s1[2:]
s2 = s2[2:]
print(s1,s2)
current_count= 0
result = 0
for i in s2:
    if int(i) == 1:
        current_count +=1
    else:
        result = max(result,current_count)    
        current_count = 0

print(result)    

o/p:
101 1101
2

******************100% error free code must satisfy all test cases*************

s2 = bin(439)
print(s2)
#s1 = s1[2:]
s2 = s2[2:]
print(s2)
current_count= 0
result = 0
 #length of string is a result
for i in s2:
    if int(i) == 1:
        current_count +=1
    else:
        result = max(result,current_count)    
        current_count = 0
        
result = max(result,current_count)
if '0' not in s2:
    print(len(s2))
    exit()
print(result)    


o/p:
oDe\K@ly@N\py2.py"
0b110110111
110110111
3

