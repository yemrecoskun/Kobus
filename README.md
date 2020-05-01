# English Readme: [README-EN.md](https://github.com/yemrecoskun/Kobus/blob/master/README-EN.md)
# Kobus (Kocaeli Otobüs)
## Projemizde Kullanılan Programlar,Diller:
- ASP.NET MVC (HTML,CSS,JS,C#)
- Veri Yapıları Bağlı Liste(Çift Yönlü) Yapısı
- Dosya İşlemleri (Veri tabanı)
- Katmanlı Mimari
## Projemizin Amacı:
Yeni kurulacak olan bir otobüs ﬁrmasına bilet satış otomasyonu.
Program iki bölümden oluşmaktadır: Sefer işlemleri ve Bilet işlemleri.
### Sefer işlemleri: 
- Tüm gidiş ve dönüş seferleri eklenmesi elle programlanmaktadır. 
- Sefer no, güzergah bilgisi, tarihi ve saati, yolcu kapasitesi, plakası, kaptanı, bilet ﬁyatı girilen bir otobüs, artık seferler listesine eklenmiştir. 
- Sefer listesine eklenen bir otobüsün tüm koltukları numaralandırılarak, yolcu bilgileri, durum (Boş, Rezervasyon, Dolu), ﬁyat, özellikleri otomatik olarak listeye eklenerek hazır hale getirilir. 
- Sefer ekleme, Sefer silme, kaptan değiştirme, sefer gelir hesaplama, sefer listeleme, geçmiş seferleri listeleme, tüm sefer sayısı işlemlerini sefer işlemleri bölümünde yapılabilmelidir. 
### Bilet satış işlemleri:
- Bu bölümde mevcut seferler listelenebilmeli, sefer seçilebilmeli.
- Seçilen seferle ilgili bilgiler ve otobüs koltuk bilgileri listelenebilmeli. 
- Boş birkoltuğa yolcu bilgileri girilerek,rezervasyon ve ya satış yapılabilmeli. Satış iptali yapılabilmeli.
## Projemizin Yazılım Mimarisi:
- Projeyi çift yönlü bağlı liste şeklinde gerçekleştirilmektedir. [CiftYonluListe.cs](https://github.com/yemrecoskun/Kobus/blob/master/Kobus/Substructure/DoubleDirectionalList.cs)
- Tüm kayıt işlemleri text dosyasına yapılmaktadır.
- Günlük yapılan işlemleri [log()](https://github.com/yemrecoskun/Kobus/blob/master/Kobus/Entity/Entity.cs) fonksiyonundan [log.txt](https://github.com/yemrecoskun/Kobus/blob/master/Kobus/File/log.txt) dosyasına gg.AA.yyyy SS:DD - İşlem şekilde yazılmaktadır.
- Projemiz tamamen dinamik bir yapıdadır.
