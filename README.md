import java.util.Scanner;

    public class matriz{

        public static void main (String[]args){

        Scanner scanner = new Scanner(System.in);

        int[][] matriz = new int[3][2];

        System.out.println("Digite os valores da matriz 3x2:");

        for (int i = 0; i < 3; i++) {

            for (int j = 0; j < 2; j++) {

                System.out.print("Digite o valor para A[" + (i+1) + "][" + (j+1) + "]: ");

                matriz[i][j] = scanner.nextInt();

            }

        }
        System.out.println("\nMatriz A(3,2):");

        for (int i = 0; i < 3; i++) {

            for (int j = 0; j < 2; j++) {

                System.out.print(matriz[i][j] + "\t");

            }

            System.out.println(); 

        }
        scanner.close();

    }
    
    public static int par(int x){
        int n;
        if(n % 2== 0){
             System.out.println ("Esses numeros na matriz são pares");
    }

}

    public static int impar(int y){
        int n;
        if(n % 2 !=0){
             System.out.println ("Esses numeros na matriz são impares");
    }

}

public void div11(){
        int n;
        if(n % 11 ==0){
             System.out.println ("Esses numeros na matriz são divisiveis de 11");
    }

}

public void primos(){
        
        int h;
        
        int v;
        
        if(h %  && v <=1){
          
                System.out.println ("Esses numeros na matriz são numeros Primos");
   
    }

}

}
