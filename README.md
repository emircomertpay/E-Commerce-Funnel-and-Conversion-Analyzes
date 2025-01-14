# E-Ticaret Hunisi ve Dönüşüm Analizi

Bu proje, çevrimiçi bir mağazanın dönüşüm hunisini analiz etmek ve kullanıcı davranışlarını incelemek amacıyla gerçekleştirilmiştir. 
Veriler, **BigQuery**'deki GA4 genel veri kümesinden alınmış ve **Power BI** kullanılarak analiz edilmiştir. 
Projenin temel amacı, pazarlama departmanına dönüşümleri ve kullanıcı adımlarını görselleştirerek mağaza performansını artırmaya yönelik öneriler sunmaktır.
## Kullanılan Araçlar
- **BigQuery**: Veri çekme ve sorgulama
- **SQL**: Verileri dönüştürme ve filtreleme
- **Power BI**: Verileri görselleştirme
- **DAX**: Hesaplanan metrikler ve özel ölçümler
## Projenin Amacı
Bu rapor, aşağıdaki hedeflere ulaşmayı amaçlamaktadır:
- Mağaza dönüşüm hunisinin görselleştirilmesi
- Ziyaret, sipariş ve satış metriklerinin analiz edilmesi
- Trafik kaynakları, cihaz kategorileri ve dil tercihleri gibi faktörlerin dönüşümlere etkisinin belirlenmesi
## Grafikler ve Sonuçlar

### 4.1 Kullanıcı Dönüşüm Hunisi
- **Grafik Açıklaması:** Oturum başlangıcından satın almaya kadar olan kullanıcı adımları.
- **Sonuç:** En fazla kullanıcı kaybı "sepete ekleme" ve "sipariş vermeye başlama" arasında yaşanmıştır.

### 4.2 Gün Bazlı Oturum Açan Tekil Kullanıcı Sayısı
- **Grafik Açıklaması:** Belirli bir tarih aralığında günlük oturum açan kullanıcılar.
- **Sonuç:** Trafik zirve noktaları kampanya veya özel günlere bağlı olabilir.

### 4.3 Cihaz Kategorisi Grafiği
- **Grafik Açıklaması:** Kullanıcıların web sitesine erişim için kullandığı cihaz kategorileri.
- **Sonuç:** Masaüstü cihazlar en çok tercih edilen kategoridir.

### 4.4 İşletim Sistemi Grafiği
- **Grafik Açıklaması:** Kullanıcıların işletim sistemi tercihleri.
- **Sonuç:** Mobil cihazlardaki iOS ve Android oranı yüksektir.

### 4.5 Kaynak Grafiği
- **Grafik Açıklaması:** Kullanıcıların siteye ulaşım kaynakları.
- **Sonuç:** Google organik aramaları en büyük trafik kaynağıdır.
## Öneriler
- Sepete ekleme ve ödeme süreçlerini kullanıcı dostu hale getirin.
- Gece saatlerinde özel kampanyalar düzenleyin.
- Trafik çeşitliliğini artırmak için alternatif kaynakları analiz edin.
## SQL Sorguları

### Events
Sorguyu BigQuery'de görmek için <u>https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1sfinal-projesi-1!2sus-central1!3s2d4f4896-0250-4018-ad8b-197f145613c5!2e1</u>


### Siparişler
Sorgu bağlantısı: <u>(https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1sfinal-projesi-1!2sus-central1!3s42a12edf-267d-4989-98bf-a119331a0478!2e1

### OturumBaşlangıc
BigQuery sorgusunu görüntülemek için 
(https://console.cloud.google.com/bigquery?ws=!1m7!1m6!12m5!1m3!1sfinal-projesi-1!2sus-central1!3s44b9e93f-85a6-41b7-bdb8-9aeba80d6b0a!2e1)
