# OSI Modeli ve Katmanları

Bilgisayar ağlarının ilk zamanlarında, sadece aynı üreticiden alınan cihazlar birbirleriyle iletişim kurabiliyordu. 1970'lerin sonlarına doğru ISO (International Organization for Standardization), OSI (Open System Interconnection) modelini tanımlayarak bu sorunu çözdü. Farklı üreticilerin cihazları artık aynı ağda haberleşebilecekti.

OSI modeli, yedi katmandan oluşur ve ağ yapılandırmalarını standartlaştırarak karmaşıklığı azaltmayı amaçlar. Bu model, farklı cihazlar arasında veri transferini kolaylaştıran bir referans modeldir.

## OSI Katmanları

1. **Uygulama Katmanı (Application Layer)**  
   Kullanıcıların bilgisayarlarla doğrudan etkileşimde bulunduğu katmandır. HTTP, SSH, FTP gibi protokoller bu katmanda yer alır.

2. **Sunum Katmanı (Presentation Layer)**  
   Verinin formatlanması, şifrelenmesi ve sıkıştırılması işlemleri bu katmanda gerçekleştirilir.

3. **Oturum Katmanı (Session Layer)**  
   İki cihaz arasında oturum kurulması, kullanılması ve sonlandırılması bu katmanda yapılır.

4. **Taşıma Katmanı (Transport Layer)**  
   Verinin uçtan uca iletimi sağlanır. TCP ve UDP protokolleri bu katmanda çalışır.

5. **Ağ Katmanı (Network Layer)**  
   Verinin ağlar arasında iletimi sağlanır ve yönlendirme işlemleri gerçekleştirilir. IP protokolü bu katmanda kullanılır.

6. **Veri Bağlantısı Katmanı (Data Link Layer)**  
   Fiziksel katmana veri iletimi yapılır. Ethernet ve Wi-Fi bu katmanda çalışan protokollerdir.

7. **Fiziksel Katman (Physical Layer)**  
   Verinin bitler halinde fiziksel ortamda iletilmesi sağlanır. Metal kablolar, fiber optik kablolar veya kablosuz sinyaller kullanılır.

---

# TCP/IP Modeli ve Katmanları

TCP/IP, internetin temel protokolü olarak kullanılan bir protokoller grubudur. DARPA ve Berkeley Software Distribution tarafından geliştirilmiştir.

## TCP/IP Katmanları

1. **Uygulama Katmanı (Application Layer)**  
   OSI modelindeki Uygulama, Sunum ve Oturum katmanlarına karşılık gelir. FTP, SMTP, SNMP gibi protokoller bu katmanda çalışır.

2. **Taşıma Katmanı (Transport Layer)**  
   OSI'deki Taşıma Katmanıyla birebir aynı işlevdedir. TCP ve UDP bu katmanda çalışır.

3. **Internet Katmanı (Internet Layer)**  
   OSI'deki Ağ Katmanına karşılık gelir. IP, ICMP, ARP gibi protokoller burada çalışır.

4. **Ağ Arayüzü Katmanı (Network Interface Layer)**  
   OSI modelindeki Veri Bağlantısı ve Fiziksel Katmanlara denk gelir. Ethernet ve Wi-Fi bu katmanda kullanılır.
