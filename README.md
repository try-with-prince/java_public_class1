// javac News.java
//java New



//It will suscessfully compiled but  when we run .class file , it will not find the main method 
// runtime error 
//java.lang.NoClassDefFoundError: news (wrong name: News)



public class News {
 public void display(){
  System.out.println("in Test1 class");
 }
}
 class news{
 public static void main(String[] args) {
  System.out.println("in Test class");
  //Test1 t = new Test1();
  //t.display();
 }
}
