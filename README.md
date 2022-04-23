# sums-up-multiples-of-four
Java101_17 tek bir sayı girilene kadar kullanıcıdan girişleri kabul eden ve girilen değerlerden çift ve 4'ün katları olan sayıları toplayıp ekrana basan program

https://www.patika.dev/tr

/*Ödev
Java döngüler ile tek bir sayı girilene kadar kullanıcıdan girişleri kabul eden ve girilen değerlerden çift ve 4'ün katları olan sayıları toplayıp ekrana basan programı yazıyoruz.*/

import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
	    
	    int num, total=0 ;
	    
	    Scanner input=new Scanner(System.in);
	    
        do{
            System.out.print("Sayı giriniz : ");
	        num=input.nextInt();
            
	        if(num%4==0){
	            total+=num ;
	        }
        }
	        while(!(num%2==1));
	        System.out.print("Toplam : "+total);
	       
    }
}
