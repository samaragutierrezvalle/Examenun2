# Examenun2
import java.util.Scanner;

public class ClasePrincipal {
    public static void main(String[] args) {
        Scanner leer = new Scanner(System.in);
       int [] arrayp = new int[9];
        for (int i = 0; i <4 ; i++) {
            System.out.println("Ingresa numeros pares");
            arrayp[i]=leer.nextInt();
        }


        for (int j = 4; j <9 ; j++) {
            System.out.println("Ingresa numeros impares");
            arrayp[j]=leer.nextInt();
        }
        Numeros(arrayp,0);

    }

    public static void Numeros(int [] array, int indice){
        if(indice == array.length){

        }
        else {
            System.out.println(array[indice]);
            Numeros(array,indice+1);

        }
    }
}
