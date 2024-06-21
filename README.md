# Lecture-11-cipher-school
package abstraction;
interface Shape{
    double pi = 3.14;
    double getSquare(double r);
}
class Circle implents Shape{
      public double getSquare(double r){
              return r*r;
}
void fun(){
      System.out.println("Hry, I implemented an interface named Shape");
      }
}
public class InterfaceSrudy{
  public static void main(String[] args){
      Circle c = new Circle();
      System.out.println(c.getSquare(5));
      c.fun();
  }
}
