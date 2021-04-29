//classe importada Scanner
import java.util.Scanner;
 
//classe Main
class Main {
 
 public static void main(String[] args) {
 
//novo Scanner
   Scanner reader = new Scanner(System.in);
 
//informações do Scanner
   System.out.println("Cadastro de Agenda");
   System.out.println("Por favor, insira um traço depois de cada informação");
   System.out.println("Informe aqui seu cpf");
   String cpf = reader.nextLine();
 
   System.out.println("Informe aqui seu nome");
   String nome = reader.nextLine();
 
   System.out.println("Informe aqui sua data de nascimento");
   String data = reader.nextLine();
 
   System.out.println("Informe aqui sua rua");
   String rua = reader.nextLine();
 
   System.out.println("Informe aqui seu email");
   String email = reader.nextLine();
  
   System.out.println("Informe aqui seu telefone");
   String telefone = reader.nextLine();
 
//imprimir
 System.out.println("Aqui está o seu Cadastro");
 System.out.println(cpf + nome  + data  + rua + email + telefone);
 
 }
}
