# def isprime(n):
    for i in range(2,n):
        if n%i==0:
            return False
        else:
            return True
n=int(input('enter n'))
l=[]
for i in range (n):
    x=int(input('enter e'))
    l.append(x)
c=0
for i in l:
    if isprime(i):
        c+=1
print(c)
