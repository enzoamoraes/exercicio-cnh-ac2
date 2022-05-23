# exercicio-cnh-ac2
import java.util.Scanner;
public class EX2 {

	public static void main(String[] args) {
		
		Scanner read = new Scanner(System.in);
        
		//variaveis criadas para identificar as notas e auxiliar nos calculos
		
        int numb1, numb2, numb3;
        
        // perguntas realizadas para que o usuario informe suas notas ao contador
        
        System.out.println("quantas questoes voce acertou no exame psicotecnico: ");
        numb1 = read.nextInt();
        System.out.println("quantos pontos voce fez no exame de legislacao: ");
        numb2 = read.nextInt();
        System.out.println("quantos pontos voce fez no exame pratico: ");
        numb3 = read.nextInt();
        
        // condição if junto aos calculos respectivos entre notas do aluno e o valor do exame 
        
        if(numb1==45);{
            System.out.printf("aprovado");
        }
        if(numb1<45){
            System.out.printf("reprovado");
        }
        else if(numb2>=21){
            System.out.printf("aprovado");
        }
        else if(numb2<21){
            System.out.printf("reprovado");
        }
        
        // condição junto ao calculo, printar texto final positivo
        
        else if(numb3>=20){
            System.out.printf("parabens, esta habilitado");
        }
        
     // condição junto ao calculo, printar texto final negativo
        
        else if(numb3<20){
            System.out.printf("refaca a prova");}
        
        }
	
	}
  
  ![image](https://user-images.githubusercontent.com/103973508/169919002-804d1fc9-875c-4860-a90a-066a77127148.png)
