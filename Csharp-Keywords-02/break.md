# break
<div dir=rtl>
تستخدم للخروج من الـ Loops او الـ Switch

</div>
<br>

```
class BreakTest
{
    static void Main()
    {
        for (int i = 1; i <= 100; i++)
        {
            if (i == 5)
            {
                break;
            }
            Console.WriteLine(i);
        }

/*
 Output:
    1
    2
    3
    4
*/
```
