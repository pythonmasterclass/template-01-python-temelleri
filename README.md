# 🐍 Proje 01: Veri Tipleri ve Operatörler Labı

Merhaba Geliştirici! 👋
Python Masterclass yolculuğundaki ilk teknik göreviniz hazır. Bu projede amacımız; kullanıcıyla etkileşime giren, aldığı verileri işleyen ve matematiksel hesaplamalar yapan dinamik bir script hazırlamak.

## 🎯 Proje Senaryosu
Bir **"Yolculuk Maliyet Hesaplayıcı"** programı yazacağız. Program kullanıcıdan gidilen yolu, aracın ne kadar yaktığını soracak ve sonuçları hesaplayıp ekrana basacak.

Bu süreçte şu kaslarınızı çalıştıracaksınız:
* Kullanıcıdan veri alma (`input`) ve ekrana basma (`print`).
* Veri tiplerini yönetme (`int`, `float`, `str`, `bool`).
* Matematiksel işlemler (`+`, `-`, `*`, `/`, `//`, `%`, `**`).
* Tip dönüşümleri (`cast` işlemleri).

---

## 🚀 Görev Listesi (Technical Requirements)

`main.py` dosyasının içinde aşağıdaki adımları gerçekleştiren kodları yazmalısın:

### Bölüm 1: Veri Toplama
- [ ] Kullanıcıdan **adını** isteyin (`str`).
- [ ] Gidilecek mesafeyi (**km cinsinden**) isteyin (Örn: 450.5) -> `float`'a dönüştürün.
- [ ] Aracın 100 km'de kaç litre yaktığını isteyin -> `float`'a dönüştürün.
- [ ] Yakıtın litre fiyatını isteyin -> `float`.

### Bölüm 2: Hesaplama (Core Logic)
- [ ] **Toplam Tüketim:** Araç toplam kaç litre yakıt harcar?
- [ ] **Toplam Maliyet:** Toplam yakıt tutarı kaç TL tutar?
- [ ] **Kilometre Başına Maliyet:** Araç 1 km'de kaç TL yakıyor?
- [ ] **Mola Sayısı (Tam Bölme):** Her 200 km'de bir mola verilecekse, kaç kez mola verilir? (`//` operatörünü kullanın).

### Bölüm 3: Raporlama ve Tip Kontrolü
- [ ] Hesaplanan tüm verileri düzgün bir formatta ekrana yazdırın.
- [ ] Kullanılan değişkenlerin tiplerini (`type()`) ekrana yazdırarak kontrol edin (Örn: "Mesafe değişkeninin tipi: <class 'float'>").

### Bonus Görev (Opsiyonel) 🌟
- [ ] Yolculuğun **gidiş-dönüş** maliyetini hesaplayın (`* 2` veya `+` operatörü).

---

## 🛠️ İpuçları
* `input()` fonksiyonu her zaman **string** (metin) döndürür. Matematiksel işlem yapmak için `float()` veya `int()` fonksiyonlarını kullanarak dönüştürmeyi unutma.
* Kodlarını yazarken yorum satırları (`#`) kullanarak ne yaptığını açıkla.

Başarılar! Kod seninle olsun. 🚀
