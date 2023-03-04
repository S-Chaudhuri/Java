import java.util.*;
class ArrayExample <T>{
  T[] a;
  
  public ArrayExample(T[] arr){
        a = arr;
      }
      public void display(){
        for(int i = 0; i < a.length; i++){
          System.out.print(a[i] + " ");
        }
        System.out.println();
      }
      public int elementCount(T x){
        int count = 0;
        for(int i = 0; i < a.length; i++){
          if(a[i].equals(x)){
            count = count + 1;
          }
        }
        return count; 
      } 

}
public class ArrayObject{
  public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
    int len = sc.nextInt(); //Taking input for length of the array
    Integer[] x = new Integer[len];
    for(int i = 0; i < len; i++){
          x[i] = sc.nextInt(); //Taking input for Integer array
    }
    
    ArrayExample<Integer> obj = new ArrayExample<Integer>(x);
    int s1 = sc.nextInt(); //Taking input for the value to be counted
    String[] y = new String[len];
    for(int i = 0; i < len; i++){
          y[i] = sc.next(); //Taking input for String array
    }
    
   
    ArrayExample<Integer> obj1 = new ArrayExample<Integer>(y);

    String s2 = sc.next(); //Taking input for the value to be counted
    obj.display();
    System.out.println(obj.elementCount(s1));
    obj1.display();
    System.out.println(obj1.elementCount(s2));
  }
}
