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
