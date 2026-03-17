# Krank Mili Konum Sensörü (Crankshaft Position Sensor - CPS) Demo

Bu proje, içten yanmalı motorların kalbi sayılan **Krank Mili Konum Sensörü (CPS)**'nin çalışma prensiplerini, donanımsal mimarisini ve arıza tespit prosedürlerini teknik bir perspektifle ele alan kapsamlı bir çalışmadır. 📄

---

## Proje Hakkında
Modern otomotiv elektroniğinde motor zamanlaması ve senkronizasyonu için kritik öneme sahip sensör teknolojileri detaylandırılmıştır. Bu çalışmada:  

- Sensörün fiziksel yapısı  
- Sinyal üretim mekanizmaları  
- Farklı sensör tipleri (**Manyetik vs. Hall Efekt**) karşılaştırmalı olarak analiz edilmiştir  

---

## Teknik İçerik ve Öne Çıkanlar 🛠

### Genel Tanım
Krank milinin dönüş hızını (RPM) ve açısal pozisyonunu algılayan elektromekanik bileşenin, motor kontrol ünitesi (ECU) ile olan etkileşimi.

### Çalışma Prensibi
Faraday'ın Elektromanyetik İndüksiyon Yasası temelinde "60-2 dişli" yapısı ile konum hesaplama.

### Donanımsal Mimari
- Demir nüve  
- Kalıcı mıknatıs  
- Bobin sargıları  

### Sensör Karşılaştırması
- **Manyetik (Endüktif):** Dayanıklı, maliyeti düşük, analog sinyal üretimi  
- **Hall Efekt:** Hassas, dijital kare dalga çıkışı, ADC gerektirmeyen hızlı tepki süresi  

### Teknik Spesifikasyonlar
- Çalışma sıcaklığı: $-40^{\circ}C$ ile $+150^{\circ}C$  
- Hava boşluğu (air gap) hassasiyeti: 0.5–1.5 mm  
- Ölçüm kapasitesi: 10.000+ RPM  

### Arıza Teşhisi
- Diagnos cihazı (DTC analizi) ile sinyal kontrolü  
- Osiloskop yardımıyla sinyal doğrulama süreçleri  

---

## PDF Erişimi
Detaylı doküman için PDF dosyasını aşağıdaki linkten inceleyebilirsiniz:  

https://drive.google.com/file/d/1vLKYVqsceY0ar9xyNWOahX_WMR36E2t9/view?usp=sharing

---

> ⚠️ Bu proje **tanıtım amaçlı** hazırlanmıştır ve herhangi bir üretim veya ticari uygulama için tasarlanmamıştır.
