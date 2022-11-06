# algorithmic_complexity
analiza złożoności obliczeniowej

## Funkcja iteracyjna ciągu Fibonacciego. Dla przeciętnego komputera możliwe przeliczenie do kilkudziesięciu pierwszych wartości ciągu.

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

## Obliczenie ciągu Fibonacciego za pomocą funkcji rekulencyjnej. Funkcja odwołuje się tylko do dwóch porzenich wartości ciągu co pozwala obliczyć znacznie większe wartosci ciągu.

![300px-Turing_Machine](https://user-images.githubusercontent.com/117569554/200188634-1ef07d4b-d138-43cd-b3cf-055c2d12dc1c.png)



```py
def fib1(n):
    if (n ==0 or n ==1):
        return 1
    if n > 1:
        return fib1(n - 1) + fib1(n - 2)
    else:
        return False

 
```

![FdThzTH](https://user-images.githubusercontent.com/117569554/200189037-2f351031-69e1-4c15-98ce-0ac605b0a563.png)


Wykres porównujący ob oliczenia.


![YhL2gcZ](https://user-images.githubusercontent.com/117569554/200169817-fcc32007-df10-4d43-8d1b-c4248cadf4e4.png)


