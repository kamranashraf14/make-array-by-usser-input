# make-array-by-usser-input

import java.util.*;

public class Main {
    public static void main(String[] args) {
    
    Scanner sc = new Scanner(System.in);
    int size = sc.nextInt();
    
    int numberArray[] = new int[size]; 
    
     for (int i=0; i<size; i++){
       numberArray[i] = sc.nextInt();
       }
       
      for (int i=0; i<size; i++){
     
      System.out.println(numberArray[i]);
        
      }
      
  }
}

by user input search for x through the index number :
import java.util.*;

public class Array {
    public static void main(String[] args) {
    
    Scanner sc = new Scanner(System.in);
    int size = sc.nextInt();
    
    int numberArray[] = new int[size]; 
    
     for (int i=0; i<size; i++){
       numberArray[i] = sc.nextInt();
       }
       
       int x = sc.nextInt();
       
      for (int i=0; i<numberArray.length; i++){
        if(numberArray[i] == x){
     
      System.out.println("x found in index :" + i );
          
        }
        
      }
      
  }
}
