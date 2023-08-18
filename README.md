# Tekstil Ürün Depo Takip Sistemi

Bu proje, tekstil firmalarının ürettiği çeşitli tekstil ürünlerinin etkin bir şekilde yönetilmesi amacıyla tasarlanmış bir SQL tabanlı veritabanı projesini ayrıntılı bir şekilde açıklamaktadır. Temel amacı, ürünlerin depo giriş ve çıkışlarının kaydedilmesi yoluyla stok durumunun sürekli olarak izlenmesini sağlamak ve ürün takibini verimli bir şekilde gerçekleştirmektir.

## Projeyi Tanımlama

Tekstil sektöründe üretim yapan firmalar için, ürünlerin etkin bir şekilde yönetilmesi ve depo takibinin doğru bir şekilde yapılması büyük önem taşır. Bu veritabanı projesi, üretimden başlayarak ürünlerin depo süreçlerini izlemeyi ve envanter yönetimini sağlamayı hedefler.

## Proje Hedefleri

- **Ürün Tanımlama:** Üretim aşamasında ortaya çıkan çeşitli tekstil ürünleri, "Urunler" tablosunda tanımlanır. Ürün adı, kategori, birim fiyat gibi temel bilgiler bu tabloda saklanır.

- **Depo Giriş ve Çıkışlarının Kaydedilmesi:** Üretilen ürünlerin depo giriş ve çıkışları, "DepoGiris" ve "DepoCikis" tabloları üzerinden kaydedilir. Bu sayede ürünlerin hangi depoya girdiği veya hangi depodan çıktığı kaydedilir.

- **Stok Durumu İzleme:** Her depo giriş ve çıkışı, stok durumunun güncellenmesini sağlar. Bu sayede anlık olarak her ürünün stok durumu takip edilebilir.

- **Depo Transferleri:** Ürünlerin farklı depolar arasında transferi, "DepoTransfer" tablosu ile kaydedilir. Bu işlem, ürünlerin depo içi dağılımının yönetilmesini sağlar.

- **Talep Doğrultusunda Transferler:** Depolar, talep doğrultusunda kendi envanterlerindeki ürünleri başka depolara transfer edebilirler. Bu işlem, "DepoTransfer" tablosu üzerinden gerçekleştirilir.

## Veritabanı Yapısı

Projede kullanılan temel tablolar:

- **Urunler Tablosu:** Üretilen ürünleri tanımlar. Ürün adı, kategori, birim fiyat gibi detaylar bu tabloda saklanır.
- **Depolar Tablosu:** Depo bilgilerini içerir. Her depo için depo adı ve diğer detaylar bu tabloda tutulur.
- **DepoGiris ve DepoCikis Tabloları:** Ürünlerin depo giriş ve çıkışlarını kaydeder. Her işlem için ürün, miktar, tarih ve ilgili depo bilgileri tutulur.
- **DepoTransfer Tablosu:** Depolar arası ürün transferlerini kaydeder. Hangi ürünün hangi depolar arasında transfer edildiği bilgileri bu tabloda saklanır.
<img width="828" alt="Ekran Resmi 2023-08-18 13 26 43" src="https://github.com/ogulcandeniz-inac/Tekstil-Database/assets/109241786/ffbee378-1218-4616-ba44-e334e7d3e6b7">

Saygılarımla,  
[Oğulcan Deniz İnaç](https://github.com/ogulcandeniz-inac)
