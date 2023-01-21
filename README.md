# Desafio-de-Codigo
Desafio: Qual é o seu turno?
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
      Scanner scan = new Scanner(System.in);
      String turno = scan.next();
      
      switch (turno){
        case "m" :
          case "M" :  System.out.println("Bom Dia!");break;
          case "v" :
            case "V" :  System.out.println("Boa Tarde!");break;
            case "n" : 
              case "N" :  System.out.println("Boa Noite!");break;
             default: System.out.println("Valor Inválido!");
      }
    }
}
