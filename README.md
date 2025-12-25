# 🚲 Konya Akıllı Bisiklet Haritası Uygulaması

Bu proje, **Konya Büyükşehir Belediyesi Açık Veri Portalı** üzerinden paylaşılan konumsal veriler kullanılarak geliştirilmiş, **Flutter tabanlı** bir mobil uygulamadır.  
Uygulama, şehir içi bisiklet ulaşımını desteklemek amacıyla bisiklet altyapı noktalarını harita üzerinde bütünleşik bir şekilde sunmaktadır.

## 🎯 Projenin Amacı
Bu çalışmanın temel amacı;
- Kiralık bisiklet istasyonlarını,
- Bisiklet park alanlarını,
- Bisiklet tamir–bakım istasyonlarını

harita üzerinde görselleştirerek kullanıcıların **şehir içi bisiklet ulaşımını daha verimli, güvenli ve planlı** bir şekilde gerçekleştirmelerine yardımcı olmaktır.

---

## 🗺️ Uygulama Özellikleri
- 📍 OpenStreetMap tabanlı harita altyapısı
- 📌 Farklı istasyon türleri için ayrı marker gösterimi
- 🔍 İstasyon arama ve filtreleme
- 📏 Kullanıcı konumuna göre **en yakın istasyon** tespiti
- 🧭 Rota oluşturma ve navigasyon
- 🔊 **Sesli yönlendirme (Text-to-Speech)**
- 🔁 Rota dışına çıkıldığında otomatik yeni rota hesaplama

---

## 🧱 Kullanılan Teknolojiler
- **Flutter** (Mobil uygulama geliştirme)
- **Dart** (Programlama dili)
- **OpenStreetMap** (Harita altyapısı)
- **flutter_map** (Harita bileşeni)
- **Riverpod** (Durum yönetimi)
- **Geolocator** (Konum servisleri)
- **CSV** (Açık veri setleri)
- **Text-to-Speech (TTS)** (Sesli yönlendirme)

---

## 📊 Kullanılan Veri Setleri
Veriler, **Konya Büyükşehir Belediyesi Açık Veri Portalı** üzerinden temin edilmiştir:

- Kiralık Bisiklet İstasyonları
- Bisiklet Park Alanları
- Bisiklet Tamir–Bakım İstasyonları

Veri setleri CSV formatında olup uygulamaya **asset** olarak entegre edilmiştir.

---

## 🧩 Mimari Yapı
Uygulama **katmanlı mimari** yaklaşımı ile geliştirilmiştir:

- **Model Katmanı**: Veri yapıları
- **Servis Katmanı**: İş mantığı
- **Provider Katmanı**: Durum yönetimi
- **UI Katmanı**: Kullanıcı arayüzü

Bu yapı sayesinde uygulama; okunabilir, sürdürülebilir ve geliştirilebilir bir yapıya sahiptir.

----

## ▶️ Kurulum ve Çalıştırma
```bash
git clone https://github.com/ahmtbaskankol1/konya_akilli_bisiklet_haritasi.git
cd konya_akilli_bisiklet_haritasi
flutter pub get
flutter run
## Geliştirici
Ahmet Emir Baskankol
