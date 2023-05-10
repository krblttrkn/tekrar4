# Taksimetre Programı
Java ile gidilen mesafeye (KM) göre taksimetre tutarını ekrana yazdıran programı yazın.
* Taksimetre KM başına 2.20 TL olacak.
* Minimum ödenecek tutar 20 TL'dir. 20 TL altındaki ücretlerde yine 20 TL alınacaktır.
* Taksimetre açılış ücreti 10 TL'dir.

```
import java.util.Scanner;

public class Taximeter {
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        int km ;
        double PerKm=2.2,total=10;

        System.out.print("Mesafeyi km cinsinden giriniz :");
        km = input.nextInt();

        total += PerKm*km;
        total = (total<20) ? 20 : total;
        System.out.print("Toplam Tutar :"+total);
    }
}
```
# Patika Profilim
***
<a href="https://academy.patika.dev/profile">Patika Profilim</a>