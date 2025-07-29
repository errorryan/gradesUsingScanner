# gradesUsingScanner
import java.util.Scanner;

public class grades {
    public static void main(String[] args){
        Scanner subject = new Scanner(System.in);
      

            System.out.println("input grades:");
             int  grades   = subject.nextInt();
        
         if (grades >= 91 && grades  <= 95){
            System.out.println('A');
        }else if  (grades >= 86 && grades <= 90){
            System.out.println('B');
        }else  if ( grades >= 81 && grades <= 85){
            System.out.println('C');
        }else if (grades >= 75 &&  grades<= 80 ){
            System.out.println('D');
        }else if (grades >= 65 && grades <= 74){
            System.out.println('F');
        
        } else {
        System.out.println("NOT VALID");
    }
    






        subject.close();

        }   
}
