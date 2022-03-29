package Leasson_1;

public class main {
    public static void main(String[] args) {
        human human = new human();
        robot robot = new robot();
        cat cat = new cat();
        treadmill treadmill = new treadmill();
        treadmill.treadmill = 10;
        wall.wal = 20;
        robot.name = "Bob";
        cat.name = "Barsik";
        cat.run = false;
        human.run = true;
        System.out.println("Кот " + cat.name + " пробежал " +
                cat.run + " метров");
        System.out.println("Робот " + robot.name + " смог пробежать " +
                treadmill.treadmill + " метров");
                
                
                public class cat {
    String name;
    boolean run;
    boolean jump;
}

public class treadmill {
    int treadmill;
}

public class robot {
    String name;
    boolean run;
    boolean jump;
}


public class wall {
    static int wal;
}

public class human {
    String name;
    boolean run;
    boolean jump;
}
