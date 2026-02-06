# 🐍 Proje 01: Veri Tipleri ve Operatörler Labı

## 📌 Genel Bakış

Bu proje, Python Masterclass eğitim serisi kapsamındaki ilk teknik uygulamadır. Amaç; kullanıcıyla etkileşime giren, aldığı verileri işleyen ve matematiksel hesaplamalar yapan dinamik bir Python scripti geliştirmektir.

---

## 🎯 Proje Senaryosu

Bu projede bir **"Yolculuk Maliyet Hesaplayıcı"** programı geliştirilecektir. Program, kullanıcıdan yolculuğa ilişkin temel bilgileri alacak, gerekli hesaplamaları gerçekleştirecek ve sonuçları ekrana yazdıracaktır.

Proje kapsamında aşağıdaki temel beceriler pekiştirilecektir:

- Kullanıcıdan veri alma (`input`) ve ekrana yazdırma (`print`) işlemleri
- Veri tiplerinin yönetimi (`int`, `float`, `str`, `bool`)
- Matematiksel operatörlerin kullanımı (`+`, `-`, `*`, `/`, `//`, `%`, `**`)
- Tip dönüşümü (`cast`) işlemleri

---

## 🚀 Teknik Gereksinimler

Aşağıda belirtilen adımlar `main.py` dosyası içerisinde eksiksiz olarak uygulanmalıdır.

### Bölüm 1: Veri Toplama

- [ ] Kullanıcıdan **adı** istenmeli (`str`).
- [ ] Gidilecek mesafe **km cinsinden** alınmalı (Örn: 450.5) ve `float` tipine dönüştürülmeli.
- [ ] Aracın 100 km'de tükettiği yakıt miktarı (litre) alınmalı ve `float` tipine dönüştürülmeli.
- [ ] Yakıtın güncel litre fiyatı alınmalı (`float`).

### Bölüm 2: Hesaplama (Temel İş Mantığı)

- [ ] **Toplam Tüketim:** Yolculuk boyunca harcanacak toplam yakıt miktarı (litre) hesaplanmalı.
- [ ] **Toplam Maliyet:** Yolculuğun toplam yakıt tutarı (TL) hesaplanmalı.
- [ ] **Kilometre Başına Maliyet:** 1 km başına düşen yakıt maliyeti (TL) hesaplanmalı.
- [ ] **Mola Sayısı:** Her 200 km'de bir mola verildiği varsayılarak toplam mola sayısı hesaplanmalı (`//` operatörü kullanılmalıdır).

### Bölüm 3: Raporlama ve Tip Kontrolü

- [ ] Hesaplanan tüm değerler düzgün ve okunabilir bir formatta ekrana yazdırılmalı.
- [ ] Kullanılan değişkenlerin veri tipleri `type()` fonksiyonu ile ekrana yazdırılarak doğrulanmalı (Örn: `Mesafe değişkeninin tipi: <class 'float'>`).

### Bonus Görev (Opsiyonel)

- [ ] Yolculuğun **gidiş-dönüş** toplam maliyeti hesaplanmalı (`* 2` veya `+` operatörü kullanılabilir).

---

## 🛠️ İpuçları

- `input()` fonksiyonu her durumda **string** tipinde değer döndürür. Matematiksel işlem gerçekleştirebilmek için ilgili değerlerin `float()` veya `int()` fonksiyonları aracılığıyla uygun tipe dönüştürülmesi gerekmektedir.
- Kodlarınızı yazarken yorum satırları (`#`) kullanarak her adımın ne işe yaradığını açıklamanız önerilir.

---

> **Not:** Sorularınız veya karşılaştığınız teknik sorunlar için eğitim ekibine başvurabilirsiniz.
