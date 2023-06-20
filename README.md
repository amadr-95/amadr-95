# Hi there 👋
## A little about me 

```
public class Developer {
    private String name;
    private int age;
    private String profession;

    public Developer() {
        this.name = "Amador";
        LocalDate birth = LocalDate.parse("1995-10-07");
        this.age = Period.between(birth, LocalDate.now()).getYears();
        this.profession = "Software Engineer";
    }
}
```
