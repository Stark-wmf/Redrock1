# Redrock1
homework
public class Legend {
    //level 0
    private String name;
    private int damage;
    private char gender;
    private String homeland;
    private int magic;

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getDamage() {
        return damage;
    }

    public void setDamage(int damage) {
        this.damage = damage;
    }

    public char getGender() {
        return gender;
    }

    public void setGender(char gender) {
        this.gender = gender;
    }

    public int getMagic() {
        return magic;
    }

    public void setMagic(int magic) {
        this.magic = magic;
    }

    public String getHomeland() {
        return homeland;
    }

    public void setHomeland(String homeland) {
        this.homeland = homeland;
    }
    public Legend(String name,int damage, char gender, String homeland, int magic) {
        this.name = name;
        this.damage = damage;
        this.gender = gender;
        this.homeland = homeland;
        this.magic = magic;

    }


}
