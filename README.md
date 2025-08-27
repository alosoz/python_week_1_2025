# python ders hazrilik 1. hafta

## ✅ **Proje 1: Favori Film Listesi**

**Amaç:** Liste, input, string ve print kullanımını pekiştirmek.

**Görev:**

* Kullanıcıdan 3 favori filmini sırayla girmesini isteyin.
* Filmleri bir listeye ekleyin.
* Sonra şu çıktıları yazdırın:

  1. Listenin tamamı
  2. İlk film
  3. Son film
  4. Listedeki filmlerin sayısı

**İpucu:**

* `len()`, `list[index]` kullanılacak.

---

## ✅ **Proje 2: Yaş Kontrolü**

**Amaç:** Input, type dönüşümü, koşul ve print ile pratik yapmak.

**Görev:**

* Kullanıcıdan yaşını isteyin.
* Eğer yaşı 18’den küçükse “Reşit değilsiniz” yazdırın, aksi halde “Reşitsiniz” yazdırın.
* Kullanıcıdan **doğum yılını** isteyin ve yaşını hesaplayın (şu anki yılı sabit olarak kullanabilirsiniz, örn. `2025`).
* Hesaplanan yaşı ekranda gösterin.

---

## ✅ **Proje 3: Kelime Analiz Aracı**

**Amaç:** String metodları, döngü, koşul, liste, set kullanımı.

**Görev:**

* Kullanıcıdan bir cümle alın.
* Şu analizleri yapın:

  1. Cümledeki toplam karakter sayısı (boşluklar hariç).
  2. Cümledeki kelime sayısı.
  3. Cümlede geçen tüm farklı kelimeleri bir **set** içinde gösterin.
  4. Cümledeki en uzun kelimeyi bulun.

**İpucu:**

* `split()`, `len()`, `set()` kullanılabilir.
* Döngü ile her kelimenin uzunluğunu karşılaştırın.

---

## ✅ **Proje 4: Mini Market Sepeti **

**Amaç:** Sözlük, liste, döngü, koşul, type dönüşümü pratikleri.

**Görev:**

* Aşağıdaki ürünleri ve fiyatlarını bir sözlükte saklayın:

  ```python
  urunler = {"elma": 3, "muz": 5, "ekmek": 2, "sut": 4}
  ```
* Kullanıcıya bir alışveriş listesi oluşturması için 3 ürün ismi girmesini isteyin.
* Her ürünün fiyatını sözlükten bulun ve toplam fiyatı hesaplayın.
* Kullanıcıya şu çıktıyı verin:

  ```
  Sepetiniz: elma, muz, sut
  Toplam fiyat: 12 TL
  ```

**İpucu:**

* `for` döngüsüyle girilen ürünleri kontrol edin.
* Fiyatı bulunamazsa “Bu ürün mevcut değil” mesajı verin.

---

## ✅ **Proje 5: Öğrenci Not Sistemi**

**Amaç:** Listeler, sözlükler, döngüler, koşullar, string metodları, input ve type dönüşümleri ile kapsamlı bir uygulama.

**Görev:**

* Kullanıcıdan **en az 3 öğrencinin adını** girmesini isteyin (ör. `Ali, Ayşe, Mehmet`).
* Her öğrenci için **3 ders notu** alın.
* Bu bilgileri şu şekilde bir **sözlük içinde saklayın**:

  ```python
  ogrenciler = {
      "Ali": [80, 90, 70],
      "Ayşe": [85, 75, 95],
      "Mehmet": [60, 70, 65]
  }
  ```
* Her öğrencinin **ortalamasını hesaplayın** ve ekrana yazdırın:

  ```
  Ali: Ortalama 80.0
  Ayşe: Ortalama 85.0
  Mehmet: Ortalama 65.0
  ```
* **Ekstra:** En yüksek ortalamaya sahip öğrenciyi bulun ve yazdırın.

**İpucu:**

* `split()`, `sum()`, `len()` kullanılabilir.
* Döngü ile ortalama hesaplayın.

---

## ✅ **Proje 6: Mini Kütüphane Yönetim Sistemi**

**Amaç:** Değişkenler, listeler, demetler, setler, sözlükler, döngüler, koşullar, string metodları, input, type dönüşümleri.

**Görev:**

* Bir sözlük ile kütüphane oluşturun, içinde kitaplar ve durumları olsun:

  ```python
  kutuphane = {
      "Python101": "Mevcut",
      "VeriBilimi": "Mevcut",
      "Algoritmalar": "Mevcut"
  }
  ```
* Kullanıcıya bir **menü** gösterin:

  ```
  1 - Kitap Ekle
  2 - Kitap Al (ödünç al)
  3 - Kitap İade Et
  4 - Tüm Kitapları Görüntüle
  5 - Çıkış
  ```
* Kullanıcı seçimine göre:

  1. Yeni kitap ekleyin (`Mevcut` olarak).
  2. Kitap ödünç alın → durumunu `Ödünçte` yapın.
  3. Kitap iade edin → durumunu tekrar `Mevcut` yapın.
  4. Tüm kitapları listeleyin ve mevcut/ödünçte sayılarını yazdırın.
  5. Programdan çıkın.

**Ekstra**

* Kitap isimlerini büyük/küçük harfe duyarsız yapın (`lower()`).
* Ödünç alınan kitapları bir **set** içinde tutun.
* Kullanıcı aynı kitabı eklemeye çalışırsa uyarı verin.


