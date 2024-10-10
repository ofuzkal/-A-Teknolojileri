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
- **TCP (Transmission Control Protocol)**: Bağlantı temelli ve güvenilir veri aktarımı sağlar. Hataları düzeltir ve eksiksiz veri iletimini garanti eder.
- **UDP (User Datagram Protocol)**: Bağlantı gerektirmeyen, daha hızlı ancak güvenilir olmayan bir veri aktarım protokolüdür. Hata kontrolü uygulama katmanına bırakılır.

## DHCP (Dynamic Host Configuration Protocol)
DHCP, bir ağ üzerindeki cihazlara otomatik olarak IP adresi, ağ geçidi ve DNS sunucusu gibi ayarların atanmasını sağlar. Genellikle ev ve halka açık ağlarda kullanılır. DHCP’nin avantajları şunlardır:
- **IP çakışmalarını önler**.
- **Otomatik güncellemeler** sayesinde yeni bir ağa bağlanıldığında IP adresi ve ağ ayarları otomatik olarak yapılandırılır.

## IPv4 ve IPv6
IP adresleri iki formdadır: 
- **IPv4**: 32-bit adresleme kullanır ve yaklaşık 4.3 milyar adres sağlar. Ancak bu sınırlı sayı, internetin büyümesiyle yetersiz kalmıştır.
- **IPv6**: 128-bit adresleme sunar ve çok daha büyük bir adres alanı sağlar. Ayrıca daha gelişmiş güvenlik ve seçenekler sunar.

### IPv4 Adres Yapısı
Bir IPv4 adresi dört oktetten oluşur, örneğin: `192.168.2.1`. Her bir oktet 8 bitten oluşur ve adres 32 bitten meydana gelir. Bu sayede 4 milyardan fazla cihaz adreslenebilir.

### IPv6 Adres Yapısı
IPv6, 128-bit uzunluğunda adresler sunar ve bu da çok daha geniş bir adresleme alanı sağlar. IPv6’nın başlıca avantajları:
- Daha fazla adres kapasitesi.
- Basit başlık yapısı.
- Daha gelişmiş güvenlik özellikleri.

## Sonuç
TCP/IP, internette veri transferi ve iletişim için kritik öneme sahip bir protokoller kümesidir. Farklı cihazların ve işletim sistemlerinin birbiriyle sorunsuz bir şekilde iletişim kurmasını sağlar. IPv4 adreslerinin tükenmesiyle birlikte, IPv6’ya geçiş hızlanmış ve gelecekte internette daha yaygın bir şekilde kullanılacaktır.
