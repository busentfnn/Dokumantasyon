---
SayfaID: KarmaDekont
SayfaTipi: 
---

# Karma Transfer Hareketi 

**Erişim Linki :** [erp.aaro.com.tr/KarmaDekont](erp.aaro.com.tr/KarmaDekont/)

![Image](../TemelHareketler/karmatransferhareketi.png "Karma Transfer Hareketi")

## Ulaşım 


- Sol sekmede Aaro kullanıcı bilgilerinin hemen altındaki arama motorundan "karma" şeklinde aratarak ulaşabilirsiniz.
- Sol menüden *Banka -> Hareket Oluştur -> Diğer İşlemler -> Karma Transfer Oluştur* şeklinde ulaşabilirsiniz. 
- Sol menüden *Demirbaş -> Hareket Oluştur -> Diğerler -> Karma Transfer Oluştur* şeklinde ulaşabilirsiniz. 
- Sol menüden *Gelir Gider -> Hareket Oluştur -> Diğerler -> Karma Transfer Oluştur* şeklinde ulaşabilirsiniz. 
- Sol menüden *Kasa -> Hareket Oluştur -> Diğer İşlemler -> Karma Transfer Oluştur* şeklinde ulaşabilirsiniz. 
- Sol menüden *Musteri/Satici -> Hareket Oluştur -> Diğerler -> Karma Transfer Oluştur* şeklinde ulaşabilirsiniz. 
- Sol menüden *Stok -> Hareket Oluştur -> Karma Transfer Oluştur* şeklinde ulaşabilirsiniz. 

## Tanım 


Karma transfer hareketi, banka, depo, müşteriler ve gelir-gider gibi farklı alanlarda yapılan işlemleri tek bir işlem altında birleştiren bir süreçtir. 
Bu tür bir işlem, birden fazla varlık veya değerin aynı anda farklı hesaplar veya birimler arasında aktarılmasını sağlar.
Karma transfer hareketi, banka, depo, müşteriler ve gelir-gider gibi farklı alanlarda yapılan işlemleri tek bir işlem altında birleştiren bir süreçtir. 
Bu tür bir işlem, birden fazla varlık veya değerin aynı anda farklı hesaplar veya birimler arasında aktarılmasını sağlar.

Örneğin, bir işletme gün sonunda şu işlemleri yapmak isteyebilir:
Örneğin, bir işletme gün sonunda şu işlemleri yapmak isteyebilir:

- Banka hesabından para çekmek (banka)
- Depodan mal çıkışı yapmak (depo)
- Müşteri hesabına ödeme almak (müşteriler)
- İşletmenin gelir ve giderlerini kaydetmek (gelir-gider)

Bu işlemler ayrı ayrı yapılabileceği gibi, karma transfer hareketi sayesinde tek bir işlem olarak da gerçekleştirilebilir. 
Böylece, banka hesabından çekilen para depo hesabına eklenir, müşteri ödemesiyle birlikte gelir-gider hesabı güncellenir ve bu hareketler bir buton olarak işlenir. 
Bu yöntem, işletmelerin işlemlerini daha hızlı, düzenli ve hatasız bir şekilde yapmasına olanak tanır.

### Genel 

**Şirket-Şube:** Kartın ait olduğu şirket ve şubeyi belirtir. Şirket-şube kullanım detayları için linke tıklayınız. [Şirket-Şube](../TemelOzellikler/SirketSubeKart.md)

**Tarih:** İşlemin yapıldığı tarihi belirtir.

**Belge No:** Belge numarasını ifade eder. Otomatik sıradaki numara gelir. İstenirse seri kullanılabilir.

**Girilmesi Zorunludur.**

**Depo:** Bu işlemin kullanıldığı depoyu belirtir.


**Vade:** Karma transfer hareketlerinde vade, birden fazla işlemle ilgili borç veya alacakların ödenmesi gereken son tarihleri ifade eder. 
Bu vade, transfer edilen varlıkların veya değerlerin ilgili hesaplara ne zaman tam olarak yansıtılacağını belirler. 
	Örneğin, banka transferi, müşteri ödemesi ve depo çıkışı gibi işlemlerin her biri için belirlenen son tarihler, karma transfer hareketinin vadeleri olarak adlandırılır.

### Detay

**Proje:** Bu hareketin hangi projeye ait olduğunu belirtir. Kalemlerde değiştirilebilir.

**Plasiyer:** Bu hareketin hangi plasiyere ait olduğunu belirtir. Kalemlerde değiştirilebilir.

**Tip:** Alt hareket tipini belirtir.


**Açıklamalar:** Ek açıklamaları belirtir. [Açıklama](../TemelOzellikler/Aciklama.md)

### Etiketler

**Etiketler:** Bu kartı gruplamak ve sonrasında gruplu rapor alabilmek için kullanılır. [Etiketler](../TemelOzellikler/Etiketler.md)

### Belgeler

Yapacağımız işlem için elimizde belgeler var ise jpg, png, pdf vb. formatlardaki belgeleri buraya yükleyebiliriz.
Buraya işlem gerçekleşirkenki görselleri yükleyebiliriz.

Belge eklemek için tıklayalım ;


- *Daha önce yüklediklerimden seç -> Belgeyi seç
-> İlişkilendir* şeklinde belge üye ekleme işlemimizi gerçekleştirebiliriz.
- *Yüklenecek belge veya resimleri -> Belgeyi ya da
 belgeleri seç -> Yükle* şeklinde belge yükleme işlemimizi gerçekleştirebiliriz.

Belge kullanım detayları için linke tıklayınız. [Belge](../TemelOzellikler/Belgeler.md)

### Notlar 

İşleme ait özel notlar ekleyebiliriz. Önemli bir detay varsa, bu ayrıntıları burada belirtebiliriz. Notların kullanım detayları için lütfen bağlantıya tıklayınız.[Notlar](../TemelOzellikler/Notlar.md)

### Kayıt Bilgileri

Kartın hangi kullanıcı tarafından ve hangi tarihlerde oluşturulduğu ve değiştirildiği bilgisini içerir.

Kart iş akışı süreçlerine dahil edildiğinde hangi kullanıcı tarafından hangi tarihte onaylandığı bilgilerini içerir. 

### Kalem Ekleme

- Yeni Stok Kalemi Ekle: Karma transfer hareketi için stok kalemini ifade eder. 
- Yeni Gelirgider Kalemi Ekle: Karma transfer hareketi için gelir gider kalemini ifade eder. 
- Yeni Demirbaş Kalemi Ekle: Karma transfer hareketi için demirbaş kalemini ifade eder. 
- Yeni Vergi Kalem Ekle: Karma transfer hareketi için vergi kalemini ifade eder. 
- Yeni Cari Kalemi Ekle: Karma transfer hareketi için cari kalemini ifade eder. 
- Yeni Kasa Kalemi Ekle: Karma transfer hareketi için kasa kalemini ifade eder. 
- Yeni Banka Kalemi Ekle: Karma transfer hareketi için banka kalemini ifade eder. 


## Kaydetme ve Silme

- Doldurulması gereken alanlar girildikten sonra sağ alt köşedeki *Kaydet* butonuna tıklayarak karma transfer işleminizi tamamlayabilirsiniz.
- Kayıtlı bir kartı silmek için sol altta bulunan sil butonuna tıklayarak silebilirsiniz.

Elbette, işte metindeki hataları düzeltilmiş hali:

---

## Yazdır

- Sayfanın sağ üstünde bulunan yazıcı sembolü ile sayfaya tanımlanan özel çıktı formatlarıyla farklı çıktılar alınabilir.
- Kartta bulunan bilgilerin kullanıcının isteğine bağlı olarak özel tasarımla yazdırılmasını sağlar.
- Birden çok çıktı tasarımı yapılabilir ve değiştirilebilir.
- Kullanıcıya özel teklif formu gibi farklı tasarımlar yapılabilir.
- Çıktı tasarımlarının her birine ayrı ayrı yetkiler verilerek, sadece istenilen kullanıcının belirli çıktılara ulaşması sağlanabilir.
- Çıktılar program üzerinden e-mail olarak gönderilebilir.

## Düzenleme 

Karma transfer hareketine ekleme yapmak ya da herhangi bir düzeltme yapmak için kalem işaretini seçerek açılan ekranda düzenlemeleri yapabiliriz.

## Ek İşlemler

Sayfanın sağ üstünde bulunan, üst üste üç çizgi şeklinde olan düğme ile ek işlemlere ulaşılır.
- Yevmiye Fişi: Yevmiye fişi, işletmelerde gerçekleşen her türlü mali işlemin tarih, miktar ve açıklama bilgileri ile birlikte kaydedildiği muhasebe belgesidir.
- Kopyala: Karma transfer hareketini kopyalamak için kullanılır.
- Kur Güncelle: Döviz kurunda değişiklik yapmak için kullanılır.
- Tüm Kalemlerde Değiştir: Buradan depo, proje, sözleşme, vergi muafiyeti, vergilerin yenilenmesi, iskonto oranı, referans ithalat/ihracat, plasiyer ve referans teslim tarihi gibi bilgileri tüm kalemler için toplu olarak değiştirebilirsiniz.
- Döviz Türü Değiştir: Döviz türü değişikliği yapabiliriz.
- Görev Oluştur: Karma transfer hareketi için görev oluşturup, kişi atayabiliriz; açıklama, bitiş tarihi, hatırlatma süresi, yönetici, kullanıcı, tamamlanma tipi, tekrar şekli bilgilerini ekleyerek görev tanımlama işlemini gerçekleştirebiliriz.
- Görev Başlat: Açılan listedeki görevlerden başlatacağımız görevi seçelim, *"Kaydet"* diyerek görevi başlatabiliriz.
- Grid Sütunları Ayarla: Burada kartın detaylarının görünmesinde değişiklikler yapabilirsiniz.
