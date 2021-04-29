#  this
<div dir=rtl>
عبارة عن مؤشر على القيم المتواجدة في class
</div>
<br>

```
public class Employee
{
    private string alias;
    private string name;

    public Employee(string name, string alias)
    {
        // Use this to qualify the members of the class
        // instead of the constructor parameters.
        this.name = name;
        this.alias = alias;
    }
}
```
