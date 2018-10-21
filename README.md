# numeros-pares-100

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package numerospares;

/**
 *
 * @author Adolf
 */
public class NumerosPares100 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int numero=1;
        int limite=100;
        while(numero<=100){
            if(numero%2==0){
                System.out.println(numero);
            }
            numero++;
        }
    }
    
}
