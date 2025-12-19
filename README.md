# Online İngilizce Öğrenim & Canlı Ders Platformu

**Cloudflare RealtimeKit Tabanlı Teknik ve Ürün Tanımı**

## Proje Tanımı

Bu proje, bireysel ve grup bazlı canlı İngilizce derslerinin verilebildiği, öğretmenler ve öğrenciler için profesyonel bir sınıf deneyimi sunan, tamamen markaya özel bir **online eğitim platformunun** geliştirilmesini kapsamaktadır.

Platform web tabanlı olacak, modern bir kullanıcı arayüzüne sahip olacak ve canlı ders altyapısı **Cloudflare RealtimeKit** kullanılarak sağlanacaktır. Bu sayede sistem hem global ölçekte stabil çalışacak hem de uzun vadede maliyet açısından sürdürülebilir olacaktır.

---

## Platformun Amacı

Platformun temel amacı, kullanıcıların kesintisiz ve kaliteli bir canlı ders deneyimi yaşamasını sağlarken, işletme tarafında ölçeklenebilir ve kontrol edilebilir bir yapı oluşturmaktır.

Cloudflare’ın edge-first mimarisi sayesinde canlı dersler düşük gecikme ile gerçekleşir, farklı coğrafyalardan katılan kullanıcılar için bağlantı kalitesi korunur ve sistem büyüdükçe altyapı darboğazları yaşanmaz.

---

## Canlı Ders Altyapısı (Cloudflare RealtimeKit)

Canlı dersler **Cloudflare RealtimeKit** altyapısı ile sağlanacaktır. Bu yapı, WebRTC tabanlı gerçek zamanlı video ve ses iletişimini Cloudflare’ın global ağı üzerinden sunar.

Platformda aşağıdaki canlı ders senaryoları desteklenecektir:

* Bire bir (1-on-1) özel dersler
* 15–20 kişilik grup dersleri
* Öğretmen merkezli canlı sınıflar
* Konuşma pratiği için küçük gruplar

Canlı ders sırasında:

* Video ve sesli iletişim
* Ekran paylaşımı
* Gerçek zamanlı sohbet
* El kaldırma ve moderasyon
* Rol bazlı yetkilendirme (öğretmen / öğrenci)
* Ders kaydı ve tekrar izleme

özellikleri kullanılabilecektir.

---

## Ders ve Sınıf Yönetimi

Platform üzerinden öğretmenler ve admin kullanıcılar dersleri kolayca yönetebilir.

Bu kapsamda:

* Ders ve sınıf oluşturma
* Ders takvimi ve saat planlama
* Öğrenci atama ve katılım takibi
* Canlı ders sırasında öğretmen kontrol araçları
* Ders geçmişi ve kayıt arşivi

gibi temel yönetim fonksiyonları sunulacaktır.

---

## Etkileşimli Öğrenme Deneyimi

Canlı derslerin verimliliğini artırmak için etkileşimli araçlar desteklenecektir.

Bunlar arasında:

* Dijital yazı tahtası
* Çizim ve annotation
* Ders materyali paylaşımı
* PDF, görsel ve video destekleri

yer alacaktır. Bu yapı, yüz yüze sınıf deneyimine yakın bir öğrenme ortamı oluşturmayı hedefler.

---

## Kullanıcı Yönetimi

Platformda farklı kullanıcı rolleri bulunacaktır:

* Öğrenciler
* Öğretmenler
* Admin kullanıcılar

Kullanıcılar için:

* Kayıt ve giriş
* Profil bilgileri
* Ders geçmişi
* Katılım ve ilerleme takibi

gibi temel özellikler sağlanacaktır.

---

## Ödeme ve Gelir Modeli

Platform, farklı gelir modellerine uygun şekilde tasarlanacaktır.

Desteklenen modeller:

* Aylık abonelik
* Ders paketleri
* Özel ders kredileri
* Ders başı ödeme
* Öğretmen gelir paylaşımı

Ödeme altyapısı olarak Türkiye için **Iyzico**, global kullanım için **Stripe** entegre edilebilir.

---

## Teknik Yapı

Platformun teknik mimarisi modern ve ölçeklenebilir bir yapı üzerine kurulacaktır.

### Frontend

* Next.js (React)
* Responsive ve modern arayüz
* SEO uyumlu yapı

### Backend

* Node.js (NestJS veya benzeri)
* REST API ve WebSocket
* JWT tabanlı kimlik doğrulama
* Rol bazlı yetkilendirme

### Gerçek Zamanlı Altyapı

* Cloudflare RealtimeKit
* WebRTC tabanlı video ve ses
* Cloudflare edge ağı üzerinden düşük gecikme
* Ders kayıtları için Cloudflare Stream / R2

### Veri Katmanı

* PostgreSQL veya MongoDB
* Kullanıcı, ders, paket ve ödeme verileri

---

## Geliştirme Süreci

Proje aşamaları aşağıdaki şekilde planlanmaktadır:

* Analiz ve kullanıcı deneyimi çalışmaları
* Arayüz ve frontend geliştirme
* Backend geliştirme
* Cloudflare RealtimeKit entegrasyonu
* Test, optimizasyon ve canlıya alma

Toplam geliştirme süresi yaklaşık **9–12 hafta** olarak öngörülmektedir.

---

## Maliyet Yapısı

### Geliştirme Maliyeti (Tek Seferlik)

Toplam geliştirme maliyetinin **7.500 – 12.000 USD** aralığında olması beklenmektedir. Bu maliyet; frontend, backend, canlı ders entegrasyonu, test ve optimizasyon süreçlerini kapsamaktadır.

---

### Aylık Operasyonel Giderler

Aylık giderler kullanım miktarına bağlı olarak değişmekle birlikte yaklaşık olarak:

* Cloudflare RealtimeKit & canlı iletişim: 150 – 700 USD
* Sunucu ve backend maliyetleri: 50 – 150 USD
* Kayıt ve medya depolama: 50 – 200 USD

Toplamda **250 – 1.000 USD / ay** aralığında öngörülmektedir.

---

## Ölçeklenebilirlik ve Gelecek Planları

Bu altyapı ilerleyen aşamalarda:

* Mobil uygulamalar (iOS / Android)
* AI destekli konuşma ve telaffuz analizi
* Otomatik seviye belirleme
* Sertifika sistemi
* Kurumsal eğitim paketleri

gibi ek özellikler için uygundur.

