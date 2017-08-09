

```python
global number
global Number
number = input('Enter a positive integer: ')

def isInt(number):
    try:
        int(number)
        return False
    except ValueError:
        return True
while isInt(number)==True:
    number = input('That\'s not an integer, try again: ')
else: Number = int(number)

def collatz(Number):
    #global number
    counter = 0  
    while Number > 1:
        if Number % 2 == 0:
            Number = Number//2
            print(Number)
        else:
            Number = 3 * Number + 1
            print(Number)
        counter +=1
    print (number + ' resolved to 1 in ' + str(counter) + ' steps.')
    return 1
    
   
isInt(number)
collatz(Number)
```

    Enter a positive integer: 1028
    514
    257
    772
    386
    193
    580
    290
    145
    436
    218
    109
    328
    164
    82
    41
    124
    62
    31
    94
    47
    142
    71
    214
    107
    322
    161
    484
    242
    121
    364
    182
    91
    274
    137
    412
    206
    103
    310
    155
    466
    233
    700
    350
    175
    526
    263
    790
    395
    1186
    593
    1780
    890
    445
    1336
    668
    334
    167
    502
    251
    754
    377
    1132
    566
    283
    850
    425
    1276
    638
    319
    958
    479
    1438
    719
    2158
    1079
    3238
    1619
    4858
    2429
    7288
    3644
    1822
    911
    2734
    1367
    4102
    2051
    6154
    3077
    9232
    4616
    2308
    1154
    577
    1732
    866
    433
    1300
    650
    325
    976
    488
    244
    122
    61
    184
    92
    46
    23
    70
    35
    106
    53
    160
    80
    40
    20
    10
    5
    16
    8
    4
    2
    1
    1028 resolved to 1 in 124 steps.
    




    1

