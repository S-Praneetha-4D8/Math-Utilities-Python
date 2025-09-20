[10:41 am, 20/9/2025] Amour💗: n=int(input())
for i in range(1,11):
    print(n,'*',i,'=',(i*n))
[10:42 am, 20/9/2025] Amour💗: num=int(input('enter a number'))
result=1
i=1
while i<=num:
    fact=1
    j=1
    while j<=i:
        fact*=j
        j+=1
    result*=fact
    i+=1
print(result)
