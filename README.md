# Rezolvatea-problemelor-IF-WHILE-FOR
Problema 1.
n=int(input("introduceți nr de zile:"))
if(n>=28) and (n<=31)
if(n==30):
print("aprilie,iulie,septembrie,noiembrie")
if(n==28)or(n==29)
print("februarie")
else:
print("decembrie, octombrie,iunie,august,martie,mai,ianuarie")
else:
print("nu există lună cu asa nr de zile")

Problema 2.
n=int(input())
total=0
factorial=1
for x in range (1,n):
factorial*=x
total+=factorial 
print(total)

Problema 4.
n=int(input("numaratorul pr. fr. :"))
m=int(input("numitorul pr. fr:"))
p=int(input("numărătorul fr.doua"))
x=int(input("numitorul fr. doua"))
print("suma", Fraction(n,m)+Fraction(p,x))
print("produs",Fraction(n,m)*Fraction(p,x))

Problema 5.
an = int (input ("Introduceți anul nașterii:"))
if (an - 2000)% 12 == 0:
sign = 'Dragon'
elif (an - 2000)% 12 == 1: 
sign =' Șarpe  '
elif (an - 2000)% 12 == 2: 
sign =' Cal '
elif (an - 2000)% 12 == 3: 
sign =' oaie'
elif (an - 2000)% 12 == 4:
sign = 'Maimuta'
elif (an - 2000)% 12 == 5:
sign =' Cocos'
elif (an - 2000)% 12 == 6:
sign = 'caine'
elif (an - 2000)% 12 =  = 7:
sign = 'Porc'
elif (an - 2000)% 12 == 8:
sign =' Șobolan'
elif (an - 2000)% 12 == 9:
sign = 'Boi'
elif (an - 2000  )% 12 == 10:
sign = 'Tigru'
else:
sign =' iepure'
print ("Semnul tău zodiacal:", semn)

Problema 8.
n=int(input("pr.nr:"))
m=int(input("doi nr:"))
p=int(input("trei nr:"))
if (n<m+p)and(m<n+p)and(p<n+m)and(n>0)and(m>0)and(p>0):
if (n==m)and(m==p)and(n==p)
print("tr. echilateral")
elif (n==m)and(n!=p)and(m!=p)or(m==p)and(m!=n)and(p!=n)or(n==p)and(n!=m)and(p!=m):
print("tr. isoscel")
elif (n!=m)and(m!=p)and(n!=p)
print("tr. scalen")
else:print("nu există astfel de tr.")


