# Algorithm Snippets

## Math

### 최대공약수, 최소공배수
~~~ python
from math import gcd

def lcm (first,second):
    return first*second//gcd(first,second)
    
print(gcd(8,12)) # 4
print(lcm(8,12)) # 48
"""
if python version is 3.9 or above, you can use math.lcm()
"""
~~~

