#  Continue
<div dir=rtl>
تستخدم للرجوع الى بداية الـ Loop وتكرارها

</div>
<br>

```
class ContinueTest
{
    static void Main()
    {
        for (int i = 1; i <= 10; i++)
        {
            if (i < 9)
            {
                continue;
            }
            Console.WriteLine(i);
        }

/*
Output:
9
10
*/
```
