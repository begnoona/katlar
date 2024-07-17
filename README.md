import java.util.Scanner;

public class Main {



    public static void main(String[] args) {

    
   /*Java döngüler ile girilen sayıya kadar olan
    4 ve 5'in kuvvetlerini ekrana yazdıran programı yazıyoruz.
    */
        int sayi,i;
        
        Scanner input =new Scanner(System.in);
        System.out.print("Lütfen sınır sayısını giriniz: " );
        sayi=input.nextInt();
        for(i=1;i<=sayi;i*=2){
            System.out.print(i);

        }









    }
}
