# 🍳 Akıllı Tarif Asistanı

Akıllı Tarif Asistanı, kullanıcının elindeki malzemeler ve ayırabileceği süreye göre **Google Gemini AI** kullanarak **mantıklı, kısa ve düzenli yemek tarifleri** üreten modern ve kullanıcı dostu bir web uygulamasıdır.

---

## 🚀 Özellikler

* 🥗 Kullanıcıdan **malzeme listesi** alma
* ⏱️ **Dakika bazlı süre** girişi
* 🤖 **Gemini AI** ile tarif üretimi
* 🍽️ Mantıklı ve yenilebilir tarifler
* 🚫 Uygunsuz malzemeleri otomatik eleme (ör. portakal + yumurta)
* 📋 Düzenli çıktı:

  * Malzemeler
  * Hazırlık
  * Pişirme
  * Servis önerisi
  * Kalori tahmini
* 👍 Beğendim / 👎 Beğenmedim geri bildirimi
* 💬 Beğenilmezse yorum alarak yeni tarif oluşturma
* 🔄 Tek tuşla **farklı tarif üretme**
* 🎨 Modern, mobil uyumlu ve mutfak temalı tasarım
* ⏳ Yükleme animasyonu ve hata yönetimi

---

## 🛠️ Kullanılan Teknolojiler

* **HTML5**
* **CSS3 (Responsive & Modern UI)**
* **Vanilla JavaScript**
* **Google Gemini API (generativelanguage.googleapis.com)**

> Backend gerektirmez – tüm uygulama tek bir `index.html` dosyası içindedir.

---

## 📦 Kurulum

1. Projeyi klonla veya indir:
   
   ```bash
   git clone https://github.com/abderahman23/akilli-tarif-asistani.git
   ```

3. `index.html` dosyasını aç.

4. Aşağıdaki satırı bul:

   ```js
   const GEMINI_API_KEY = "";
   ```

5. Kendi **Gemini API anahtarını** ekle:

   ```js
   const GEMINI_API_KEY = "API_KEYINIZI_BURAYA_YAPISTIRIN";
   ```

6. Dosyayı tarayıcıda aç 🎉

---

## 🔑 Gemini API Anahtarı Nasıl Alınır?

1. [https://makersuite.google.com/app/apikey](https://makersuite.google.com/app/apikey)
2. Google hesabınla giriş yap
3. Yeni bir API Key oluştur
4. Anahtarı projeye yapıştır


---

## 📸 Örnek Çıktı

```
Malzemeler:
- 4 yumurta
- 2 domates
- 1 soğan

Hazırlık:
- Sebzeleri doğra
- Yumurtaları çırp

Pişirme:
- Soğanı kavur, domatesi ekle
- Yumurtayı ekleyip pişir

Servis Önerisi:
- Sıcak servis et

Kalori:
- Yaklaşık 420 kcal
```

---

## ⚠️ Bilinen Sınırlamalar

* Kalori bilgisi **yaklaşık** değerdir
* API anahtarı frontend içinde olduğu için **canlı projede gizlenmelidir**
* Gemini API kota sınırlarına tabidir

---



## 👨‍🍳 Geliştirici

Bu proje, **öğrenme ve prototipleme amaçlı** geliştirilmiştir.
Modern AI tabanlı kullanıcı deneyimi örneği sunar.

---

