# ref
<div dir=rtl>
تستخدم لتمرير و استرجاع القيم من و الى الدالة . باختصار اي تغيير على القيمه سيحدث تغيير على المتغير

<div>
<br>

```
void Method(ref int refArgument)
{
    refArgument = refArgument + 44;
}

int number = 1;
Method(ref number);
Console.WriteLine(number);
// Output: 45
```
