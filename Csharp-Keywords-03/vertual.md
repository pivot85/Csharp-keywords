#  vertual
<div dir=rtl>
تقوم بالتعديل على الداله و السماح لها بــoverride من داله الابن

</div>

<br>

```
class MyBaseClass
{
    public virtual string Name { get; set; }
   }
   class MyDerivedClass : MyBaseClass
{
    private string name;
    
    public override string Name
    {
        get
        {
            return name;
        }
        set
        {
            if (!string.IsNullOrEmpty(value))
            {
                name = value;
            }
            else
            {
                name = "Unknown";
            }
        }
    }
}
    
```
