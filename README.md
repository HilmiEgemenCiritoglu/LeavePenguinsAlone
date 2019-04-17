# Leave Penguins Alone
![Alt text](/img_penguins.jpg?raw=true "Title")
<br><br>
Bu projenin amaci clickbait seklinde kullanici ceken 'haber' sitelerine hic bir 'hit' vermemektir. 
https://en.wikipedia.org/wiki/Media_of_Turkey

### Arka Plan?

Her isletim sistemi host dosyasi denilen bir dosya tutar. Bu dosya IP ve domain isimlerinden olusan bir duz metin dosyasidir.
Bir websitesine baglanmaya calistiginizda isletim sisteminiz once bu host dosyasina bakar. Eger o websitesi host dosyasinda mevcutsa oradaki IP ye baglanir. Eger yoksa dns protokulunu kullanarak web sitesinin IPsini bulur ve websitesine baglanmak icin o adrese http sorgusu gonderirsiniz. 
Eger biz host dosyasini degistirir ve bir domaini 0.0.0.0 olarak kaydedersek; biz bu web sitesine baglanmaya calistigimizda entry mevcut oldugu icin dns sorgusu calismaz ve 0.0.0.0 baglanmaya calisiriz. Fakat bu adres gecersiz oldugundan herhangi bir websitesi acilmaz. Daha fazla bilgi icin: https://github.com/StevenBlack/hosts

### Nasil kullanilir?
Bu projede bulununan Domains.txt dosyasindaki alan adlarini(domainleri) host dosyasina eklerseniz, bu sitelere bilgisayarinizdan erisiminizi engelleyecektir. Host dosyasinin nerede oldugunu bilmiyorsaniz, burayi ziyaret edebilirsiniz:
[Tutorial](https://www.howtogeek.com/howto/27350/beginner-geek-how-to-edit-your-hosts-file/)

=======
