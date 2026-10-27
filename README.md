<div align="center">
  <img src="https://raw.githubusercontent.com/NothingManTR/Plantelligence/main/assets/3d-cad-pot.png" width="300" alt="Plantelligence 3D CAD Akıllı Saksı" />
  <h1>🌱 Plantelligence</h1>
  <h3>TÜBİTAK 2209-B — Üniversite Öğrencileri Sanayiye Yönelik Araştırma Projeleri Desteği Programı</h3>
  <p><strong>Yapay Zeka, Deneyap Kart ve 3 Tüplü NPK Dozajlama Tabanlı Otonom Akıllı Saksı ve Endüstriyel Sera Entegrasyonu</strong></p>

  <p>
    <a href="https://nothingmantr.github.io/Plantelligence/"><strong>🌐 Canlı Web Platformunu İnceleyin »</strong></a>
  </p>

  <p>
    <a href="#-tübitak-2209-b-sanayi-odaklı-çözüm">Sanayi Odaklı Çözüm</a> •
    <a href="#-sistem-mimarisi-ve-donanım-bileşenleri">Donanım Mimarisi</a> •
    <a href="#-3b-cad-tasarımı-ve-stl-üretim-modeli">3D CAD (.STL)</a> •
    <a href="#-özgün-fitlik-algoritması-ve-karar-motoru">Fitlik Algoritması</a> •
    <a href="#-12-haftalık-deneysel-büyüme-sonuçları">Deneysel Sonuçlar</a> •
    <a href="#-mobil-uygulama-arayüzü-figma">Mobil Uygulama</a> •
    <a href="#-proje-yürütücüsü">Proje Yürütücüsü</a>
  </p>

  <p>
    <img src="https://img.shields.io/badge/TÜBİTAK-2209--B_Sanayiye_Yönelik-dc2626?style=for-the-badge&logo=target&logoColor=white" alt="TÜBİTAK 2209-B" />
    <img src="https://img.shields.io/badge/Tarım-4.0_%26_Endüstriyel_Sera-16a34a?style=for-the-badge&logo=sprout&logoColor=white" alt="Tarım 4.0" />
    <img src="https://img.shields.io/badge/Donanım-Deneyap_Kart_(Tensilica_LX6)-0284c7?style=for-the-badge&logo=microchip&logoColor=white" alt="Deneyap Kart" />
    <img src="https://img.shields.io/badge/Yapay_Zeka-ESP32--CAM_Leaf_Pathology-eab308?style=for-the-badge&logo=tensorflow&logoColor=black" alt="Edge AI" />
    <img src="https://img.shields.io/badge/Haberleşme-RS485_Modbus_RTU-8b5cf6?style=for-the-badge" alt="RS485 Modbus" />
    <img src="https://img.shields.io/badge/3D_CAD-.STL_Üretime_Hazır-059669?style=for-the-badge&logo=blender&logoColor=white" alt="3D CAD STL" />
    <img src="https://img.shields.io/badge/Lisans-MIT-blue?style=for-the-badge" alt="MIT License" />
  </p>
</div>

---

## 🏭 TÜBİTAK 2209-B: Sanayi Odaklı Çözüm ve Katma Değer

**Plantelligence**, TÜBİTAK 2209-B *Üniversite Öğrencileri Sanayiye Yönelik Araştırma Projeleri Desteği Programı* kapsamında; endüstriyel seracılık, dikey tarım tesisleri ve modern iç mekan tarım işletmelerinde karşılaşılan kritik verimsizlikleri yerli ve milli teknolojilerle çözmek üzere geliştirilmiş **sanayi odaklı otonom bitki bakım ve gübreleme platformudur**.

### ⚠️ Sanayinin Karşılaştığı Temel Sorunlar:
1. **Dengesiz ve Aşırı Gübreleme:** Endüstriyel seralarda standart takvim usulü gübreleme yapılması nedeniyle yıllık gübre sarfiyatının **%30-40'ı** israf edilmekte; toprakta aşırı tuzlanma ve yer altı sularında azot/fosfor ötrofikasyonu meydana gelmektedir.
2. **Yüksek İş Gücü ve Geç Teşhis:** Geniş ölçekli seralarda yaprak hastalıklarının insan gözüyle periyodik taranması yüksek iş gücü gerektirmekte; semptomlar fark edildiğinde mantar ve bakteri yayılımı çoktan mahsul kaybına yol açmaktadır.
3. **İthal Sistem Bağımlılığı ve Sensör Arızaları:** İthal sera kontrol ünitelerinin fahiş maliyetleri ve tekil sensör arızalarında (nem/sıcaklık sapması) tüm sulama döngüsünün kilitlenerek bitki köklerinin çürümesi.

### 💡 Plantelligence Sanayi Çözümü:
- **Yerli & Milli Kontrol Ünitesi:** İthal PLC ve IoT kartları yerine **Deneyap Kart** (TÜBİTAK & T3 Vakfı yerli çift çekirdekli Tensilica LX6 mimarisi) kullanılarak donanım maliyeti **%60** düşürülmüştür.
- **3 Tüplü Otonom NPK Dozajlama:** Azot (N), Fosfor (P) ve Potasyum (K) mineralleri 3 ayrı rezervuardan mililitrik dozaj pompalarıyla toprağın anlık ihtiyacına göre otonom enjekte edilir. Gübre sarfiyatında **%35 net tasarruf** sağlanır.
- **Endüstriyel RS-485 Modbus Uyumluluğu:** Sensör veriyolu endüstri standardı **RS-485 Modbus RTU** protokolü ile tasarlanmış olup mevcut sera otomasyon panolarına ve SCADA ağlarına doğrudan entegre edilebilir.
- **Edge AI ile Erken Yaprak Patolojisi:** ESP32-CAM üzerindeki hafifletilmiş yapay zeka modeliyle günde iki kez yaprak taraması yapılır; kloroz, külleme veya kök çürümesi henüz başlangıç evresinde saptanarak anında karantina/tedavi sinyali üretilir.
- **Sensör Arıza Tolerans Algoritması:** Herhangi bir sensörde anlık parazit veya hat kopması yaşandığında sistem geçmiş trend ve Kalman interpolasyonu ile tahmini veriyi hesaplar, sulama kesintiye uğramaz.

---

## 📑 TÜBİTAK 2209-B Bilimsel Değerlendirme Kriterleri Matrisi

| Kriter | Ağırlık | Projedeki Somut Karşılığı |
| :--- | :---: | :--- |
| **Araştırma Önerisinin Bilimsel Niteliği** | **%35** | 8 farklı çevresel parametrenin sensör füzyonu, yaprak patolojisinde TinyML/MobileNetV2 kullanımı, tarımsal bitki sağlığı literatürüne dayalı optimum katsayı matrisi. |
| **Yöntem** | **%25** | Çift çevrimli otonom rutin (Günde 2 kez yaprak AI taraması + Saatte 1 kez telemetri & NPK/su besleme döngüsü), matematiksel **Fitlik Fonksiyonu**, sensör arıza tolerans algoritması. |
| **Proje Yönetimi** | **%20** | 8 aşamalı iş paketi planı, risk analizi (sensör parazitleri, kamera lens kirlenmesi, pompa tıkanması için B planları), 12 aylık takvim. |
| **Sanayi Odaklı Çıktıları ve Yaygın Etkisi** | **%20** | Yerli Deneyap Kart entegrasyonu ile sanayide dışa bağımlılığın azaltılması, gübre ve su tasarrufuyla sera işletme maliyetlerinin düşürülmesi, seri üretime uygun 3D CAD/STL kalıp tasarımı. |

---

## 🎛️ Sistem Mimarisi ve Donanım Bileşenleri

Plantelligence, bitki kök bölgesi ve yaprak mikroklimasını eşzamanlı izleyen **8 parametreli endüstriyel sensör dizilimi** ile donatılmıştır:

<div align="center">
  <img src="assets/circuit-diagram.png" alt="Devre Şeması ve Pin Dağılımı" width="850" />
  <p><em>Deneyap Kart, ESP32-CAM ve Endüstriyel Sensör Matrisi Bağlantı Şeması</em></p>
</div>

### 🛠️ Donanım Malzeme Listesi (BOM)

| Modül / Bileşen | Donanım Modeli | Arayüz / Protokol | Görev ve Fonksiyon |
| :--- | :--- | :--- | :--- |
| **Ana İşlemci** | **Deneyap Kart** (Dual-Core Tensilica LX6 240MHz) | SPI / I2C / UART / GPIO | Tüm sensörlerin taranması, fitlik hesabı ve eyleyici kontrolü |
| **Görsel Teşhis Birimi** | **ESP32-CAM (OV2640 2MP)** | Wi-Fi 802.11 b/g/n & Web Stream | 7/24 canlı video akışı ve yaprak patolojisi fotoğraf analizi |
| **Toprak NPK Sensörü** | **RS485 Endüstriyel Toprak NPK Probu** | RS485 Modbus RTU (MAX485) | Topraktaki Azot (N), Fosfor (P) ve Potasyum (K) ölçümü (mg/kg) |
| **Toprak pH Analizi** | **DFRobot SEN0161 Analog pH Probu** | Analog ADC | Toprak asidite/alkalinite dengesi (0 - 14 pH) |
| **Optik Işık Sensörü** | **TSL2591 Yüksek Hassasiyetli Işık Sensörü**| I2C (0x29) | Fotosentez lüks seviyesi ölçümü (188 μLux – 88,000 Lux) |
| **Hava Kalitesi & VOC** | **CCS811 & MiCS-5524 Gaz Sensörleri** | I2C / Analog ADC | Karbondioksit ($eCO_2$) ve uçucu organik bileşik (VOC) seviyesi |
| **İklim Sensörleri** | **BMP280 & DHT11** | I2C / 1-Wire | Ortam sıcaklığı, bağıl nem ve barometrik hava basıncı |
| **Toprak Nemi** | **FC-28 / Kapasitif Nem Probu** | Analog ADC | Kök bölgesi nem doygunluğu (%) |
| **NPK Besin Dozajlama** | **3 Tüp Tuz (Azot, Fosfor, Potasyum)** | 3x 12V Peristaltik Dozaj Pompası | Mililitrik otonom mineral enjeksiyonu |
| **Sulama & Aydınlatma** | **12V Dalgıç Su Pompası + Full Spektrum LED** | Röle Kanalları & PWM | Otonom sulama ve yapay fotosentez aydınlatması |

---

## 🖨️ 3B CAD Tasarımı ve STL Üretim Modeli

Saksı gövdesi, endüstriyel seralarda ve iç mekanlarda modüler montaj kolaylığı sağlayacak şekilde SolidWorks ve Tinkercad üzerinde tasarlanmış ve 3D yazıcı üretimine hazır hale getirilmiştir:

<div align="center">
  <img src="assets/3d-cad-pot.png" alt="3D CAD Akıllı Saksı Modeli" width="750" />
  <p><em>Plantelligence Modüler 3D CAD Akıllı Saksı Gövdesi</em></p>
</div>

### 📐 CAD Mekanik Özellikleri:
- **Entegre Kamera Kulesi:** Bitki büyümesini engellemeyen, ayarlanabilir odak açısına sahip ESP32-CAM montaj kulesi.
- **3 Tüplü NPK Enjeksiyon Kanalları:** Gövde arkasına gizlenmiş, 3 ayrı besin rezervuarından gelen serum hortumları için sızdırmaz giriş portları.
- **Sensör Geçiş Koridoru:** NPK, pH ve nem problarının kök bölgesine kablo karmaşası olmadan doğrudan inmesini sağlayan iç kanal.
- **Fazla Su Drenaj Haznesi:** Kök çürümesini engelleyen çift tabanlı tahliye haznesi.
- **Üretime Hazır CAD Dosyaları:** Repodaki [`assets/smart-pot-model.stl`](assets/smart-pot-model.stl) ve [`assets/Incredible-Jaagub.stl`](assets/Incredible-Jaagub.stl) dosyaları doğrudan 3D baskı (PLA/PETG) veya endüstriyel plastik enjeksiyon kalıplaması için kullanılabilir.

---

## 🧠 Özgün Fitlik Algoritması ve Karar Motoru

Sistem, endüstriyel güvenilirlik sağlamak amacıyla **iki paralel çevrim** halinde çalışır:

1. **Günde 2 Kez Görsel Çevrim:** ESP32-CAM kamerası ile yaprak fotoğrafları taranır. Veri tabanındaki hastalık profilleriyle karşılaştırılır; semptomlar belirlenirse telemetriye bildirim gider ve tedavi başlatılır.
2. **Saatte 1 Kez Telemetri Çevrimi:** Tüm sensörler taranarak aşağıdaki **Fitlik Fonksiyonu** ile sistem sağlığı puanlanır:

$$\text{Fitlik} = 100 - 100 \times \sum_{\text{sensors}} \frac{(X_i - X_{opt})^2}{X_{opt}} \times w_i$$

- $X_i$: Anlık ölçülen sensör değeri
- $X_{opt}$: İlgili bitki türünün ideal büyüme eşiği
- $w_i$: Sensörün bitki fizyolojisindeki ağırlık katsayısı

Fitlik değeri belirlenen eşik değerin altına düştüğünde ilgili alt eyleyici (sulama pompası, azot/fosfor/potasyum dozajlama veya LED aydınlatma) otomatik tetiklenir.

<div align="center">
  <img src="assets/algorithm-flowchart.png" alt="Algoritma Akış Şeması" width="850" />
  <p><em>TÜBİTAK 2209-B Otonom Algoritma ve Karar Akış Şeması</em></p>
</div>

### 🛡️ Sensör Arıza Tespiti ve Kalman Düzeltme
Sensör hatası veya anlık parazit durumlarında sistem geçmiş veriler üzerinden hata tespit algoritmasını çalıştırarak veriyi düzeltir:

<div align="center">
  <img src="assets/fault-tolerance.png" alt="Sensör Arıza Düzeltme Grafiği" width="750" />
  <p><em>Sıcaklık ve Nem Sensörü Hata Tespiti ve Kalman Düzeltme Eğrileri</em></p>
</div>

---

## 📊 12 Haftalık Deneysel Büyüme Sonuçları

Klasik saksı ve Plantelligence Akıllı Saksı arasında yürütülen 12 haftalık kontrollü deneyler:

<div align="center">
  <img src="assets/growth-chart.png" alt="12 Haftalık Bitki Büyüme Karşılaştırması" width="750" />
  <p><em>Akıllı Saksı ile Klasik Saksının Bitki Büyümesine Etkisi (12 Hafta)</em></p>
</div>

- **Bezelye Bitkisi:** Akıllı saksıda **75 cm** boya ulaşırken, klasik saksıda 53 cm'de kalmıştır (**%41.5 büyüme artışı**).
- **Kaktüs:** Akıllı saksıda **13 cm**, klasik saksıda 8 cm büyüme kaydedilmiştir (**%62.5 büyüme artışı**).

---

## 📱 Mobil Uygulama Arayüzü (Figma)

"Bitkileriniz Artık Cebinizde!" konseptiyle Figma üzerinde tasarlanan mobil kullanıcı deneyimi:

<div align="center">
  <img src="assets/mobile-ui.png" alt="Plantelligence Mobil Arayüzü" width="850" />
  <p><em>Figma Ortamında Tasarlanan Plantelligence Mobil Kullanıcı Arayüzü</em></p>
</div>

- **Giriş ve Kimlik Doğrulama:** Güvenli kullanıcı girişi ve profil yönetimi.
- **Ana Kontrol Paneli:** Bitki koleksiyonu, sağlık durum filtreleri (Önemli, Sağlıklı, Sağlıksız) ve anlık özet.
- **Bitki Detay & Canlı Telemetri:** Yıldız Çiçeği ekranı üzerinden anlık nem (%72), sıcaklık (16°C), ışık (%93) ve ESP32-CAM canlı video yayını.
- **Arıza & Hastalık Teşhisi:** Civanperçemi üzerinde tespit edilen kök çürümesi uyarısı ve tek tıkla **"Tedaviye Başla"** otonom müdahale komutu.

---

## 📅 TÜBİTAK 2209-B Proje İş Paketleri

| İş Paketi | Tarih Aralığı | Açıklama ve Faaliyetler |
| :---: | :--- | :--- |
| **İP-01** | 1 - 7 Ocak 2024 | Proje Planlama, Sanayi Probleminin Tanımlanması ve Yöntem Belirleme |
| **İP-02** | 8 - 21 Ocak 2024 | Sanayi Tipi Sensör Matrisi (RS485 Modbus) ve Donanım Araştırması |
| **İP-03** | 22 Ocak - 11 Şubat 2024 | 3D CAD Akıllı Saksı Tasarımı (Tinkercad / STL) ve Sensör Entegrasyonu |
| **İP-04** | 12 - 25 Şubat 2024 | Deneyap Kart Gömülü Yazılımı, Fitlik Fonksiyonu ve Edge AI Modelleri |
| **İP-05** | 26 Şubat - 17 Mart 2024 | Mobil Uygulama Arayüzü (Figma) ve Telemetri Entegrasyonu |
| **İP-06** | 18 Mart - 7 Nisan 2024 | 12 Haftalık Kontrollü Büyüme Deneyleri ve Hata Ayıklama |
| **İP-07** | 8 - 21 Nisan 2024 | Final Sanayi Prototipinin Tamamlanması ve Saha Testleri |
| **İP-08** | 22 - 28 Nisan 2024 | TÜBİTAK 2209-B Proje Sonuç Raporu ve Sanayi Sunumu |

---

## 👨‍💻 Proje Yürütücüsü

<table border="0">
  <tr>
    <td width="130" align="center" valign="top">
      <img src="https://github.com/NothingManTR.png" width="110" style="border-radius:50%;" alt="Taha Can Tunç" />
    </td>
    <td>
      <h3>Taha Can Tunç</h3>
      <p><strong>TÜBİTAK 2209-B Proje Yürütücüsü & Geliştirici</strong></p>
      <p>Manisa Celal Bayar Üniversitesi Mekatronik Mühendisliği öğrencisi. Gömülü sistemler (C/C++), yerli mikrokontrolörler (Deneyap Kart, ESP32, STM32), endüstriyel haberleşme protokolleri (RS485 Modbus RTU), yapay zeka, görüntü işleme ve açık kaynak Linux sistemleri üzerine çalışmaktadır. Plantelligence projesinin 3D CAD mekanik modellemesi, elektronik devre tasarımı, gömülü yazılımı, fitlik algoritması ve web platformunu tasarlamış ve geliştirmiştir.</p>
      <p>
        🌐 <a href="https://nothingmantr.github.io/Taha-Can-Tunc/">Portfolyo Web Sitesi</a> • 
        🐙 <a href="https://github.com/NothingManTR">GitHub (@NothingManTR)</a> • 
        💼 <a href="https://www.linkedin.com/in/taha-can-tun%C3%A7-454313275/">LinkedIn</a> • 
        ✉️ <a href="mailto:tcttaha@gmail.com">tcttaha@gmail.com</a>
      </p>
    </td>
  </tr>
</table>

---

## 📜 Lisans

Bu proje **[MIT Lisansı](LICENSE)** kapsamında açık kaynaklı olarak paylaşılmıştır.

<div align="center">
  <sub>TÜBİTAK 2209-B Üniversite Öğrencileri Sanayiye Yönelik Araştırma Projeleri Desteği Programı Kapsamında Yürütülmektedir.</sub>
</div>