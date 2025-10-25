## 🧭 Proje Adı: **Öğrenci Bilgi ve Not Yönetim Sistemi (v1)**

### 🎯 Kullanılan Kavramlar

* `list`, `dict` (koleksiyon yapıları)
* `for`, `while` döngüleri
* `if-elif-else` karar yapıları
* `def` fonksiyon tanımları
* `len()`, `sum()`, `max()` gibi yerleşik fonksiyonlar
* kullanıcı girişi (`input()`)

---

# 🎓 Öğrenci Bilgi ve Not Sistemi 

### 🔹 Program akışı 
1️⃣Kullanıcıdan işlem seçmesi istenir:
  - 1 → Yeni öğrenci ekle
  - 2 → Öğrencileri listele
  - 3 → Sınıf ortalamasını göster
  - 4 → En yüksek not alan öğrenciyi bul
  - 5 → Ortalama altındakileri göster
  - 6 → Çıkış

2️⃣Her öğrenci sözlük olarak saklanır:
```python
ogrenci = {"isim": "Ahmet", "not": 84, "durum": "İyi", "harf": "B"}
````

3️⃣Not durumları:
| Aralık | Harf | Durum    |
| ------ | ---- | -------- |
| 85-100 | A    | Mükemmel |
| 70-84  | B    | İyi      |
| 50-69  | C    | Geçti    |
| 0-49   | F    | Kaldı    |

---

### 🔹 Fonksiyonlar

* `harf_notu(not)` → harf karşılığı döndürür
* `durum_belirle(not)` → “Geçti” veya “Kaldı” döndürür
* `ortalama_hesapla(ogrenciler)` → sınıf ortalamasını hesaplar
* `en_yuksek_not(ogrenciler)` → en yüksek notu bulur
* `ortalama_altindakiler(ogrenciler)` → ortalamanın altındakileri listeler

---

### 🔹 Kod Akışı

```python
while True:
    print("\n1. Öğrenci Ekle")
    print("2. Öğrencileri Listele")
    print("3. Sınıf Ortalaması")
    print("4. En Yüksek Not Alan Öğrenci")
    print("5. Ortalama Altındakiler")
    print("6. Çıkış")
```

Kullanıcı seçim yapar, ardından ilgili fonksiyon çalışır.

---




