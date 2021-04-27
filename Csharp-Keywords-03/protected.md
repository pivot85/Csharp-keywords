#  protected
<div dir=rtl>
كل المتغيرات او الدوال التي تكون معها protected يمكن الوصول اليها من الـclass خاص بها او ابنائه

</div>
<br>

```
public class Company{
protected int value ;
}

public class Employee : Company{
    value=6;
}
```
