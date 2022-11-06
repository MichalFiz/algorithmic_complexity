# algorithmic_complexity
analiza złożoności obliczeniowej

## Iteracyjny Fibonacci o złożoności liniowej.

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

## Rekulencyjny Fibonacci.

```py
def fib1(n):
    if (n ==0 or n ==1):
        return 1
    if n > 1:
        return fib1(n - 1) + fib1(n - 2)
    else:
        return False
        
```




![YhL2gcZ](https://user-images.githubusercontent.com/117569554/200169817-fcc32007-df10-4d43-8d1b-c4248cadf4e4.png)


