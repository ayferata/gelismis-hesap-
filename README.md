# gelismis-hesap-
import java.util.Scanner
        public class Main {
    public static void main (String[]args){
        Scanner scan =new Scanner(System.in);
        int select;
        String menu="1-toplama işlemi\n"
                    "2-çıkarma işlemei\n"
                    "3-çarpma işlemei\n"
                    "4-bölme işlemei\n"
                    "5-üslü sayı hesaplama\n"
                    "6-mod alma\n"
                    "7-dikdörtgen alan ve çevre hesabı\n"
                    "0-çıkış yap"
                            do{
                                System.out.println("bir işlem seçiniz: ");
                                select= scan.nextInt();
                                switch (select){
                                    case 1:
                                    sum(a,b);
                                    break;
                                    case 2:
                                        minus(a,b);
                                        break;
                                    case 3:
                                        times (a,b);
                                        break;
                                    case 4:
                                        divided(a.b):
                                        break;
                                    case 5 :
                                        System.out.println("üs hesabı: "+power(a,b));
                                        break;
                                    case 6:
                                        System.out.println("mod işlemi: "+mod(a,b));
                                        break;
                                    case 7:
                                        colcle (a,b);
                                        break;
                                    default:
                                        System.out.println("geçersiz işlem girdiniz");


                                }

                            }
