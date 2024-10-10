# TCP/IP ve Ağ Protokolleri

## Giriş
Ağ protokolleri, bilgisayarlar arası veri akışını düzenler. TCP/IP (Transmission Control Protocol/Internet Protocol), internette veri transferi için kullanılan en temel protokollerden biridir ve OSI modelinin 3. ve 4. katmanlarında çalışır. TCP/IP protokol grubu, internette kullanılan servislerin çoğunu sağlar. Bunlar arasında e-posta, dosya transferi, haber grupları ve WWW erişimi bulunur.

Her ne kadar TCP/IP tek bir protokol gibi görünse de aslında bir protokoller kümesidir. Bu küme, her biri farklı görevleri olan birçok protokolden oluşur.

## Neden TCP/IP?
- **Üretici bağımsızlığı**: Herhangi bir donanım veya yazılıma bağımlı değildir.
- **Çapraz platform**: Farklı işletim sistemleri ve cihazlar arasında veri alışverişi sağlar.
- **UNIX uyumluluğu**: Özellikle UNIX tabanlı sistemlerle tam uyumludur.
- **Yönlendirilebilirlik**: TCP/IP yönlendirilebilir bir protokoldür.
- **Yaygın kullanımı**: İnternette en çok kullanılan protokol grubudur.
- **Global adresleme**: IP adresleri ile geniş bir adresleme alanı sunar.

## IP (Internet Protocol)
IP, veri paketlerinin yönlendirilmesi için adres bilgisi ve kontrol bilgilerini içeren bir protokoldür. IP, internet üzerindeki temel ağ işlemlerini gerçekleştirir ve paketlerin doğru adrese ulaşmasını sağlar. IP, bağlantı temelli (connection-oriented) bir protokol değildir ve paketlerin içerik doğruluğunu garanti etmez, sadece başlık kısmındaki hataları bulur ve düzeltir.

### IP Adresleme
Her cihazın internette tanımlanabilmesi için bir **IP adresi** vardır. Bu adresler iki ana bölüme ayrılır:
1. **Network ID**: Ağa ait segment numarası.
2. **Host ID**: Aygıtın numarası.

### IP Adres Sınıfları
- **A Sınıfı**: Büyük ağlar için (0-127 arası). IBMNET gibi büyük ağlarda kullanılır.
- **B Sınıfı**: Orta ölçekli ağlar (128-191 arası). Okullar ve hastaneler kullanır.
- **C Sınıfı**: Küçük ağlar için (192-223 arası). Genelde ev ve küçük işletmelerde tercih edilir.
- **D Sınıfı**: Çoklu yayın (multicast) için ayrılmıştır (224-239 arası).
- **E Sınıfı**: Deneysel ve bilimsel araştırmalar için ayrılmıştır (240-255 arası).

## TCP ve UDP
IP katmanına doğrudan erişim sağlanamaz; bu yüzden **TCP** ve **UDP** adlı iki protokol kullanılır:
- **TCP (Transmission Control Protocol)**: Bağlantı temelli ve güvenilir veri aktarımı sağlar. Hataları düzeltir ve eksiksiz veri
