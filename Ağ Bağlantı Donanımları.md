# Ağ Bağlantı Donanımları

Farklı topoloji ve teknolojilere göre yapılandırılan ağlar, çeşitli bağlantı cihazları kullanabilir. Bu cihazlar, ağların verimli ve güvenli çalışmasını sağlar.

## 1. Repeater (Tekrarlayıcı)
- Tekrarlayıcı, zayıflayan sinyalleri güçlendirerek daha uzun mesafelere iletilmesini sağlar.
- Genellikle kablosuz ağlarda sinyalin menzilini artırmak için kullanılır.

## 2. HUB
- Hub, bağlı cihazlar arasında veri iletimini gerçekleştiren, yönetimsel özellikleri bulunmayan bir ağ cihazıdır.
- Hub, veriyi ağdaki tüm cihazlara gönderir. Bu da gereksiz veri trafiğine neden olabilir.
- Tak-çalıştır mantığıyla çalışır.
- Ağ güvenliği açısından açıklara neden olabileceği için modern ağlarda kullanılmamalıdır.

## 3. Switch (Anahtar)
- Switchler, ağdaki cihazların birbirleriyle haberleşmesini sağlayan cihazlardır. 
- Gelen veriyi yalnızca hedef cihaza iletir, bu sayede gereksiz yayın trafiğini engeller.
  
### Switch Türleri
#### 3.1. Yönetilemeyen Anahtarlar (Unmanaged Switches)
- Konsol (console) bağlantısı veya web arayüzü olmayan anahtarlardır. Yalnızca temel switching fonksiyonlarını yerine getirirler.
- Tak-çalıştır mantığıyla çalışır ve ayar gerektirmez.

#### 3.2. Yönetilebilen Anahtarlar (Managed Switches)
- Konsol veya web arayüzünden yönetilebilir, merkezi ve kenar lokasyonlarda kullanılabilir anahtarlardır.
- Ağ yönetimi ve optimizasyonu için birçok ayarı özelleştirebilirsiniz.

#### 3.3. Endüstriyel Anahtarlar (Industrial Switches)
- Zorlu çevresel koşullarda (soğuk, sıcak, nemli ortamlarda) çalışabilecek şekilde üretilmiş, dayanıklı anahtarlardır.
- Yönetilebilir ve yönetilemez türleri bulunur. Genellikle MOBESE, otomasyon ve askeri projelerde kullanılırlar.
- Soğuk (-40°C), sıcak (+75°C/85°C) ve yüksek nem (%5-95) gibi zorlu ortamlarda çalışabilirler.

## 4. Router (Yönlendirici)
- Router, iki veya daha fazla farklı ağ arasında veri yönlendirmesi sağlayan bir ağ cihazıdır.
- Routerlar, genellikle internet trafiğini yönetmek ve ağları birbirine bağlamak için kullanılır.

## 5. Gateway (Ağ Geçidi)
- Gateway, iki farklı ağ protokolü kullanan ağlar arasında veri alışverişi sağlamak için kullanılan cihazdır. 
- Ağ geçitleri, ağlar arasında veri dönüştürme işlemi yapar.

## 6. NIC (Ağ Kartı) ve Modem
- **NIC (Network Interface Card):** Bilgisayarların yerel ağa bağlanmasını sağlayan donanım kartıdır.
- **Modem:** ISP'ler tarafından sağlanan ve yerel ağın internete çıkmasını sağlayan cihazdır. Modern modemlerde DHCP sunucusu, güvenlik duvarı (firewall) gibi ek özellikler bulunur.

## 7. Erişim Noktası (Access Point - AP)
- Access Point, kablolu bir ağı kablosuz hale getirmek için kullanılan cihazdır. Kablolu ağları genişleterek kablosuz cihazların bağlanmasını sağlar.
  
### 7.1. Kablosuz Yerel Alan Ağı Kontrolcüleri (Wireless LAN Controller - WLC)
- WLC, ağda yer alan AP'leri yönetmek ve yapılandırmak için kullanılan cihazlardır.
- Kanal ve frekans yönetimi gibi kablosuz ağın optimizasyonunu sağlar.
- Bir AP'de kimliği doğrulanmış kullanıcıların diğer AP'lerden de erişim sağlamasına olanak tanır.
