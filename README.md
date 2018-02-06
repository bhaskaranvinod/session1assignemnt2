# session1assignemnt2
Write a Python program to find which are divisible by 7 bt not 5 between 2000 and 3200 (both included).Then print it with a comma separates sequence on a single line.
# define a string
a = [] 
for x in range (2000, 3200):
   if (x%7==0) and (x%5!=0):
      a.append(str(x)) # the value of x is appended to the string
print (','.join(a)) #join all the values separated by comma
