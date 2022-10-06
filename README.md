
package kelvin;

import java.util.Scanner;
public class Kelvin {

 
    public static void main(String[] args) {
      
        
        Scanner dig = new Scanner(System.in);
        int A;
        int B;
        System.out.print("Escreva Numero1");
        A = dig.nextInt();
     System.out.print("Escreva Numero2");
        B = dig.nextInt();
     
       
         dig.close();
    }
    
    
    
    
    
    public void Contagem (){
        
  Scanner dig = new Scanner(System.in);
  
int cont;

 System.out.print("Escreva o Numero");
   cont = dig.nextInt();
    
   for(int i = cont; i <= 500; i ++){
        
        System.out.print("Contagem " + cont);
        
        if (cont > 100 )
            System.out.print("Numero maior que 100");
           
        else if(cont > 500)
             System.out.print("Numero maior que 500");
            dig.close();
            }
      }
}
