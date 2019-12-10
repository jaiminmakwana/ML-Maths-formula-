
# 1. Quadratic Equations of degree 2

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkKMg7UDJzTfCvXIHV_gZRIDfqLvqBFEAZ7ACafrDKqFgJx3NY&s)


```python
from math import sqrt
a=int(input("a?"))
b=int(input("b?"))
c=int(input("c?"))

x1 = ((-b) + (sqrt((b**2)-(4*a*c))))/(2*a)
x2 = ((-b) - (sqrt((b**2)-(4*a*c))))/(2*a)
print("X1 =",x1,"and X2 =",x2)
```

    a?1
    b?-1
    c?-6
    X1 = 3.0 and X2 = -2.0


# 2. Integration of x^n

![](data:image/png;base64,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)

x1 = int(input("Start limit:"))
x2 = int(input("End limit:"))
n = int(input("Enter n:"))
def fun(x1,x2):
    return ((x2**(n+1))/(n+1)) - ((x1**(n+1))/(n+1))

fun(x1,x2)

# 3. Mean

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZxnscQUu1x34wGfjUn0D9CrYFAWTBACkcF2akIixJHI8I1N66&s)


```python
sum = 0
lst = [] 
n = int(input("Enter number of elements : "))  
for i in range(0, n): 
    ele = int(input()) 
    lst.append(ele)
    
#mean
for i in range(n):
    sum=sum+lst[i]
print("mean:",(sum/n))
```

    Enter number of elements : 5
    1
    2
    3
    3
    5
    mean: 2.8



```python
lst=[]
lst.append(10)
print(lst)
```

    [10]
​    

# 4.Median

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZxnscQUu1x34wGfjUn0D9CrYFAWTBACkcF2akIixJHI8I1N66&s)


```python
#median
lst.sort()
if len(lst) % 2 == 0:
   first_median = lst[len(lst) // 2]
   second_median = lst[len(lst) // 2 - 1]
   median = (first_median + second_median) / 2
else:
   median = lst[len(lst) // 2]
print("Median:",median)
```

    Median: 2.5
​    

# 5.Mode

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZxnscQUu1x34wGfjUn0D9CrYFAWTBACkcF2akIixJHI8I1N66&s)


```python
#mode
flag=[]
lst = [] 
n = int(input("Enter number of elements : "))  
for i in range(0, n): 
    ele = int(input()) 
    lst.append(ele)

n = max(lst)
for i in range(n):
    flag.append(lst.count(i))

if(max(flag)==1):
    print("NO mode exists")
else:
    print("mode:",flag.index(max(flag)))
```

    Enter number of elements : 5
    1
    2
    3
    4
    5
    NO mode exists


# 6. Rule Induction


```python
#𝐺𝑎𝑖𝑛 = 𝑃.[(−𝑃t-1. log (𝑃)) − (−𝑃t. log (𝑃))]
import math
P = float(input("P? "))
p1 = float(input("pt-1?"))
p0 = float(input("pt?"))
def gain(P,p1,p0):
    return P*(((-p1)*math.log(P))-((-p0)*math.log(P)))

gain(P,p1,p0)
```

    P? 0.9877
    pt-1?0.3211
    pt?0.1322





    0.0023091217102171706



# 7. Find Determinant 3x3 2x2

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQjsKLKrXwcwWzIqJfn4On1hr3xYrfq8puANAn1cE2sfUwYhGCW&s)


```python
n = int(input("Enter number of rows or columns: "))

if(n==3):
    det = []
    for i in range(9):
        det.append(int(input()))
    print("det =",(det[0]*(det[4]*det[8]-det[5]*det[7]))-(det[1]*(det[3]*det[8]-det[5]*det[6]))+(det[2]*(det[3]*det[7]-det[4]*det[6])))

elif(n==2):
    det = []
    for i in range(4):
        det.append(int(input()))
    print("det =",det[0]*det[3]-det[1]*det[2])

else:
    print("Wrong Input...")
    

    

```

    Enter number of rows or columns: 3
    1
    2
    3
    4
    5
    56
    6
    7
    77
    det = 43


# 8. Plot Sigmoid

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTtTw15SDJGnftUix9gEl_DOjW45ulN_sYsiHixO6iC54z32dyr&s)


```python
# formula: 1/(1+e^-(wx+b))

def sigmoid(x):
    a = []
    for item in x:
        a.append(1/(1+math.exp(-item)))
    return a

import matplotlib.pyplot as plt
import numpy as np

x = np.arange(1,20,0.5)
sig = sigmoid(x)
plt.plot(x,sig)
plt.xlabel('x')
plt.ylabel('sigmoid')
plt.show()
```


![png](image/output_23_0.png)


# 9. plot tanx


```python

import matplotlib.pyplot as plt
import numpy as np
x = np.linspace(-2 * (np.pi/2), 2 * (np.pi/2), 1000)
plt.plot(x, np.tan(x))
plt.show()
```


![png](image/output_25_0.png)


# 10. Variance & Standard Deviation

![](data:image/png;base64,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)


```python
#var = E(x - mean(x))^2/n-1
from math import sqrt
def var(x):
    sum = 0
    m = mean(x)
    for i in range(len(x)):
        sum += ((x[i]-m)**2)
    return sum/(n-1)

def mean(x):
    return sum(x)/len(x)

n = int(input("Enter total number of x:"))
x=[]
for i in range(n):
    x.append(int(input()))
    
v = var(x)
print("Variance:",v, "& Standard Deviation: %.2f" % sqrt(v))

```

    Enter total number of x:5
    1
    2
    3
    4
    5
    Variance: 2.5 & Standard Deviation: 1.58


# 11. Manhattan Distance

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQH6TTO4l-mAU5fan2hPCxfpPNeqM7QQSsGk5BMIETdbLxmnfbG&s)


```python
# dis= |x1-x2| + |y1-y2|

def manhattan(x1,y1,x2,y2):
    return abs(x1-x2)+abs(y1-y2)

x1,y1 = map(int,input("1st data point:").split())
x2,y2 = map(int,input("2nd data point:").split())
manhattan(x1,y1,x2,y2)
```

    1st data point:1 2
    2nd data point:3 4





    4



# 12. MAHALANOBIS DISTANCE

![](data:image/png;base64,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)


```python
print("Enter observation")
lst = []

def mahdis(lst,n):
    num = ((lst[n+1]-(sum(lst)/len(lst)))**2)
    v = var(lst)
    print("%.3f" % (num/v)**0.5)

def var(x):
    s = 0
    for i in range(len(x)):
        s += ((x[i]-(sum(x)/len(x)))**2)
    return s/(len(x)-1)

try:
    while(1):
        lst.append(int(input()))
except:
    print(lst)
    index = int(input("Enter index of number to calculate distance:"))
    mahdis(lst,index)
```

    Enter observation
    1
    2
    3
    4
    
    [1, 2, 3, 4]
    Enter index of number to calculate distance:1
    0.387


# 13. Differentiation of x^n

![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR1VXmSbzNVsbKaCDDU2DpsZSgX0Wzb-NkJlTeqXZToIA8Femtn&s)


```python
x,n = map(int,input("Ask: eg:2^3 ").split())
print(n*x**(n-1))
```

    Ask: eg:2^3 6 2
    12


# 14. Simple Interest

![](data:image/png;base64,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)


```python
pa = float(input("Enter principle amount:"))
rate = float(input("Enter interest rate:"))
time = int(input("And last enter time:"))
print("Simple Interest:",(pa*rate*time)/100)
```

    Enter principle amount:3000
    Enter interest rate:4
    And last enter time:1
    Simple Interest: 120.0


# 15. Compound Interest

![](data:image/png;base64,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)


```python
def compound_interest(pa, rate, time):   
    ci = pa * (pow((1 + rate / 100), time)) 
    print("Compound interest is %.2f" % ci) 

pa = float(input("Principle amount:"))
rate = float(input("Enter interest rate:"))
time = int(input("And time:"))

compound_interest(pa,rate,time)
```

    Principle amount:10000
    Enter interest rate:3
    And time:5
    Compound interest is 11592.74

##### This notebook update **continuesly...!!!**



***Design by Jaimin Makwana***