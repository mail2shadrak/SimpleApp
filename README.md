class SimpleApp
{
public static void show()
{
System.out.println("Hello World");
}
}
class MainClass extends SimpleApp
{
public static void main(String args[])
{
MainClass mc = new MainClass();
mc.show();
}
}

