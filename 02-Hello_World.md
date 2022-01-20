# İlk Kodumuz Hello World
Merhaba arkadaşlar bu dersimizde C dilinde ilk
kodumuzu yazacağız

___________________________________________________
#include <stdio.h>

int main()

{

    printf("Hello World");

    return 0;
}
___________________________________________________
Evet Hello World ü yazdırmak için bu kodu 
kullanıyoruz tamam sizde bir sorun çıkmadıysa
devam edebiliriz şimdi ise kodumuzu tanıyalım

1. #include <stdio.h> : Bir önişlemci komutudur ve daha program derlenmeden önce devreye girerek istenilen değişiklikleri kaynak dosya üzerinde gerçekleştirir Bu programda stdio.h (standart input-output) başlık dosyasını programa dahil eder Bu başlık dosyasında standart giriş-çıkış fonksiyonlarının prototipleri mevcuttur Burada programdaki komutun amacı printf fonskiyonunu programa dahil etmektir


2. int main() : Bu satırda programda işe main fonksiyonun tanımlanmasıyla başlanmıştır main fonksiyonun C dilinde özel bir amacı vardır Programın çalışma zamanında başladığı yer main fonksiyonudur


3. { : main fonksiyonunun başladığı yeri belirtir


4. printf("Hello World"); : Bu satırda "Hello World" yazısını (karakter dizisini) ekrana bastırmak için printf fonksiyonu çağrılır ki bu fonksiyonu 1. satırdaki stdio.h başlık dosyası ile programa dahil etmiştik


5. return 0; : return kodu main fonksiyonumuzu 0 geri dönüş değeriyle sonlandırır


6. } : main fonksiyonunun bittiği yeri belirtir

