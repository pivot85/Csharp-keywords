#  private
<div dir=rtl>
كل المتغيرات او الدوال التي تكون معها private يمكن الوصول اليها من الـclass خاص بها فقط
</div>
<br>

```
public class Company{
private int value ;
}

public class Employee : Company{
    // cannot use the variable here
}
```
