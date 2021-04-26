# out
<div dir=rtl>
شبيهه لـ ref ولكن تختلف عنها في انه بالامكان استخدامها مع المتغيرات من دون اعطائها قيمه

</div>
<br>

```
int initializeInMethod;
OutArgExample(out initializeInMethod);
Console.WriteLine(initializeInMethod);     // value is now 44

void OutArgExample(out int number)
{
    number = 44;
}
```
