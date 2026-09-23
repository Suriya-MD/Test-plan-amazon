# Test-plan-amazon

https://1drv.ms/x/c/b6234086d81fef4b/IQDHIx2Tq2SnRrOvTMrFDLqxAS98ewEL5p1vggDhy0m9Npk?e=5yQABf

# Task (22-09-2026)  - Test cases for valid and invalid inputs

https://1drv.ms/x/c/b6234086d81fef4b/IQCZkFx3JRIsQ7ZA7UlxSfdXAcC83_kxZyOanH3FFoHbziY?e=6hOg4w

# Task (23-09-2026)

## 1.Binary
```
bin=input().split(",")
res=[]
for x in bin:
  if int(x,2)%5==0:
    res.append(x)
print(",".join(res))
```
## 2. Letters and Digits count
```
n=input()
letter=0
digit=0
for x in n:
  if x.isalpha():
    letter+=1
  elif x.isdigit():
    digit+=1

print("Letter:",letter)
print("Digit:",digit)
```
## 3. Factorial
```
n=int(input())
fact=1
for i in range(1,n+1):
    fact*=i
print(fact)
```


