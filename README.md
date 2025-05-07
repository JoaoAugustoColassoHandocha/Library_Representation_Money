# Decimal Library

The decimal library provides floating point numbers with arbitrary precision. This means that you can specify the desired precision and perform calculations with a specific number of decimal places, and you can also have complete control over the number of decimal places to be maintained. This is useful in scenarios where precision needs to be strictly controlled, as it does not introduce rounding errors as long as you set the appropriate precision.

##

The result passed on by the system is:

![Result](https://github.com/JoaoAugustoColassoHandocha/Library_Representation_Money/blob/main/Screenshot_2.png)

##

For the library to work, it is first necessary to import it using the following command:

```
from decimal import Decimal

```

##

Another example for using the library would be the following code:

```
earnings_of_month = Decimal('90.90') * 5

print(f'\nEarnings of month: {earnings_of_month}\n')

expenses_of_month = Decimal('100.1') * 3

print(f'Expenses of month: {expenses_of_month}\n')

```