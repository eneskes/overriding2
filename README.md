# overriding2
public class C02 extends C01{

    @Override
    public void method2() {
        System.out.println("Child method2");
    }

    public static void main(String[] args) {
        C02 obj = new C02();
        obj.method1();
        obj.method2();
    }
}
