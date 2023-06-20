# Hi there 👋
## A little about me 

public class Developer {
    private final String name;
    private final int age;
    private final String proffesion;

    public Developer() {
        this.name = "Amador";
        LocalDate birth = LocalDate.parse("1995-10-07");
        this.age = Period.between(birth,LocalDate.now()).getYears();
        this.proffesion = "Software Engineer";
    }
}
