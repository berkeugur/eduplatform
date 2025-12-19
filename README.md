# İngilizce Öğrenim & Canlı Ders Platformu

**Teknik Altyapı – Özellikler – Maliyet Raporu**

## 1. Proje Özeti

Bu proje, bireysel veya grup halinde **canlı İngilizce dersleri**, **özel dersler**, **konuşma pratikleri** ve **etkileşimli sınıf deneyimi** sunan, tamamen markaya özel bir **online eğitim platformu** geliştirilmesini kapsar.

Platform:

* **Web tabanlı** olacak
* **Next.js** ile geliştirilecek
* **Agora** gerçek zamanlı video & ses altyapısı kullanılacak
* Ölçeklenebilir, güvenli ve gelir üretmeye uygun olacak

---

## 2. Hedef Kullanıcılar

* Öğrenciler (bireysel / grup)
* Öğretmenler
* Admin & operasyon ekibi
* (Opsiyonel) Kurumsal müşteriler

---

## 3. Temel Özellikler

### 3.1 Canlı Ders Altyapısı (Agora)

Agora Education Solutions kullanılarak:

* Canlı **video & sesli dersler**
* **1-on-1 özel ders**
* **15–20 kişilik grup dersleri**
* **Ekran paylaşımı**
* **Canlı chat**
* **Ders kaydı & tekrar izleme**
* **Breakout rooms** (konuşma pratiği)
* **El kaldırma**
* **Rol bazlı yetkiler** (öğretmen / öğrenci)

Agora’nın global altyapısı sayesinde:

* Düşük gecikme
* Yüksek ses & görüntü kalitesi
* Dünya genelinde stabil bağlantı

---

### 3.2 Sınıf ve Ders Yönetimi

* Ders oluşturma
* Ders takvimi
* Öğrenci atama
* Katılım listesi
* Canlı ders içi kontrol paneli
* Öğretmen kontrol yetkileri

---

### 3.3 Etkileşim & Öğrenme Araçları

* **Interactive Whiteboard**
* Yazı / çizim / annotation
* Ders materyali paylaşımı
* PDF, görsel, video destekleri
* (Opsiyonel) Quiz & mini testler

---

### 3.4 Kullanıcı Yönetimi

* Kayıt / giriş
* Öğrenci profili
* Öğretmen profili
* Ders geçmişi
* Katılım & ilerleme takibi

---

### 3.5 Ödeme & Gelir Modeli (Opsiyonel)

* Paket satın alma
* Aylık üyelik
* Özel ders kredileri
* Ders başı ödeme
* Öğretmen gelir paylaşımı

> Ödeme altyapısı olarak **Iyzico / Stripe** entegre edilebilir.

---

## 4. Teknik Mimari

### 4.1 Frontend

* **Next.js (React)**
* SSR / SEO uyumlu
* Modern UI (Tailwind / Shadcn)
* Responsive (Desktop / Tablet / Mobile)

---

### 4.2 Backend

* **Node.js (NestJS)** veya benzeri
* REST / WebSocket
* JWT authentication
* Rol bazlı yetkilendirme

---

### 4.3 Gerçek Zamanlı İletişim

* **Agora SDK**
* Video
* Audio
* Messaging
* Recording
* Analytics

---

### 4.4 Veritabanı

* PostgreSQL veya MongoDB
* Kullanıcılar
* Dersler
* Paketler
* Ödeme kayıtları

---

## 5. Agora Altyapısının Avantajları

* Eğitim odaklı SDK
* 1-on-1’den **binlerce kullanıcıya kadar ölçek**
* Düşük latency
* Global CDN
* Güvenli veri akışı
* Canlı kalite & kullanım analitikleri

Preply, HelloTalk gibi büyük EdTech markaları tarafından aktif kullanılmaktadır.

---

## 6. Tahmini Geliştirme Süreci

| Aşama              | Süre           |
| ------------------ | -------------- |
| Analiz & UX        | 1–2 hafta      |
| UI / Frontend      | 3–4 hafta      |
| Backend            | 3–4 hafta      |
| Agora entegrasyonu | 1–2 hafta      |
| Test & Yayın       | 1 hafta        |
| **Toplam**         | **9–12 hafta** |

---

## 7. Maliyet Tahmini

### 7.1 Geliştirme Maliyeti (Tek Seferlik)

| Kalem               | Tahmini                 |
| ------------------- | ----------------------- |
| Frontend            | 4.000 – 6.000 USD       |
| Backend             | 4.000 – 6.000 USD       |
| Agora entegrasyonu  | 2.000 – 3.000 USD       |
| Test & optimizasyon | 1.000 – 2.000 USD       |
| **Toplam**          | **11.000 – 17.000 USD** |

---

### 7.2 Aylık Operasyonel Giderler

| Kalem              | Tahmini                            |
| ------------------ | ---------------------------------- |
| Agora (video/ses)  | 200 – 1.000 USD *(kullanıma göre)* |
| Sunucu (VPS/Cloud) | 50 – 150 USD                       |
| Storage & kayıtlar | 50 – 200 USD                       |
| **Toplam**         | **300 – 1.300 USD / ay**           |

> Agora fiyatları **dakika bazlıdır**, kullanıcı sayısı arttıkça maliyet lineer artar.

---

## 8. Ölçeklenebilirlik & Gelecek Genişletmeler

* Mobil uygulama (iOS / Android)
* AI destekli konuşma analizi
* Otomatik seviye tespiti
* Sertifika sistemi
* LMS entegrasyonu
* Kurumsal paketler

---

## 9. Sonuç

Bu yapı ile:

* Profesyonel, ölçeklenebilir
* Gelir üretmeye hazır
* Global kullanıma uygun
* Markaya özel
* Uzun vadede büyüyebilen

bir **online İngilizce öğrenim platformu** inşa edilebilir.

