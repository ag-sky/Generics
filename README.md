# Generics


for type safety, not explicityly type casting while accessing objects data, can work with different types ( code reusability), ensure that specific type would be used for collection like arraylist, hashmap

Generic Class 

class Box<T> {
private T item;

public void setItem(T item){
this.item = item;
}
public T getItem(){
   return item;
   }

public class Main{

 Box<String> box = new Box<String>();
 box.setItem("hello")
 system.out.println(box.getItem)) // no ex;icity type casting required.

 Generic Method 


 public static <T> void printArray(T[] array){
 for(T element : array){
  system.out.println(element)
  }
  }

  public static void main (String[] args){
      String[] stringArray = {"akash","ravi"}
      printArray(stringArray)
  }


 

 
