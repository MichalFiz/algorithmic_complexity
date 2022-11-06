# algorithmic_complexity
analiza złożoności obliczeniowej
```py
def fib2(n):
    i = 0
    a = 1
    b = 1
    lst = []
    while i <= n // 2:
        lst.append(a)
        lst.append(b)
        i = i + 1
        c = a + b
        a = b
        b = c
    return lst
```

![3GFcnBk](https://user-images.githubusercontent.com/117569554/200165169-a9db44ae-5cc6-4789-a79e-4f8375791e84.png)

