# Inheritance-Ex1
class A{
    int x;
}
class B extends A {
    int y;
}

public class ABTest {
    public static void main(String args[]) {
    B b1=new B();
    b1.x=5;
    b1.y=10;
      System.out.println(b1.x+ " "+ b1.y); //5 10 
    }
}
