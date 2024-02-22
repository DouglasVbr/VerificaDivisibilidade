# VerificaDivisibilidade


package verificadivisibilidade;

import java.util.Scanner;
public class VerificaDivisibilidade {

    
    public static void main(String[] args) {
        
        Scanner Scanner = new Scanner(System.in);
        
        // solicita ao usuario que insira dois numeros
        
        System.out.println("Digite o numerador:");
        int numerador = Scanner.nextInt();
        
        System.out.println("Digite o denominador:");
        int denominador = Scanner.nextInt();
       
        
        // verifica se o número é divisivel pelo denominador
        
        if(denominador != 0 && numerador % denominador == 0){
            System.out.println(numerador + " é divisivel por " + denominador + ".");
        }else{
            System.out.println("não é possivel dividir por zero");
            }
        // fecha o Scanner 
        
        Scanner.close();
    }
    
}
