# -print-Range-
package qu6;



import java.util.Scanner;

public class QU6 {

   
    public static void main(String[] args) {
    Scanner console = new Scanner(System.in);

    System.out.println("This program prints the sequence of numbers between the two numbers that you give");

    //obtain values
    System.out.println("Enter two numbers (x,y)");
    System.out.print("Number x: ");
    int x = console.nextInt();
    System.out.print("Number y: ");
    int y = console.nextInt();     
        
    
        if(x == y) {
            System.out.print("sequence is :" +x);
        }
            
        if(x < y){
            for (int i = x; i <= y; i++){
           
            System.out.print(+i +" ");
            System.out.println();
        }
        
         if(x > y){
           for (int j = x; j>= y; j--) {
        int k = -1*y + (x -y +1) * 2  +1;
             System.out.print( +j + " ");
        }        
                  }
        }
    }
}

