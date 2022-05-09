4_variables<br>
about variables<br>
'''variables is like storage containers of values'''<br>
'''variables are reusable in python '''<br>
p=1<br>
q=2<br>
r=3<br>
s=4<br>
print(p)<br>
print(q)<br>
print(r)<br>
print(s)<br>
#1 2 3 4 in vartical<br>
''' ; is called terminator which means totally ending of the line'''<br>
''' , is a used for seperation which takes sigle/one space'''<br> 
print(p);print(q);print(r);print(s) #1 2 3 4 in vartical<br>
print(p),print(q),print(r),print(s) #1 2 3 4 in vartical<br>
print(p,q,r,s)  # in horizontal direction 1 2 3 4 <br>
'''ERRORS OCCURED WHILE ASSIGNING VARIABLES AND VALUES'''<br>
'''VALUE ERROR'''<br>
p,q,r,s=1,2,3<br>
print(p,q,r,s)   #ValueError: not enough values to unpack (expected 4, got 3) <br>
not enough values are given to the variables<br>
p,q,r,s=1,2,3,4,5<br>
print(p,q,r,s) #too many values to unpack (expected 4)<br>
more no of values are there compare to variables<br>

 '''NAME ERROR'''<br>
a=6<br>
b=5<br>
c=a+b<br>
print(d)#NameError: name 'd' is not defined<br>
variable d is not defined<br>
