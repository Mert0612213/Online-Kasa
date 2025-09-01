# Barkodlu Kasa Uygulaması

![Kasa Uygulaması Görseli](https://i.hizliresim.com/q9gbhzm.png)

Bu proje, **Laravel** ve **Quasar Framework** kullanılarak geliştirilmiş modern bir **barkodlu kasa** uygulamasıdır. Uygulama, kullanıcıların barkodları tarayarak ürünleri sepete eklemelerini ve satın almalarını sağlar. **ZXing** modülü ile barkod tarama işlemi gerçekleştirilir. Bu uygulama, alışveriş deneyimini daha hızlı ve verimli hale getirmeyi amaçlayan bir çözüm sunar.

## Özellikler

- **Barkod Tarama**: ZXing modülü ile kameradan barkodları hızlıca tarayarak ürünleri sepete ekleyebilirsiniz.
- **Ürün Yönetimi**: Ürünler, barkod, ürün adı ve fiyat gibi bilgilerle kolayca eklenebilir ve yönetilebilir.
- **Sepet Görüntüleme**: Sepetteki ürünler, ürün adı, birim fiyatı, miktarı ve toplam fiyat gibi bilgilerle listelenir.
- **Toplam Hesaplama**: Sepetinizdeki tüm ürünlerin toplam tutarı anında hesaplanır ve kullanıcıya gösterilir.
- **Modern Arayüz**: Quasar Framework kullanılarak şık ve kullanıcı dostu bir arayüz tasarlanmıştır.

## Kullanıcı Arayüzü

Uygulamanın kullanıcı arayüzü oldukça basittir ve kullanıcıların hızlı bir şekilde ürün eklemelerine olanak tanır. Ürünler, barkodla tarandıktan sonra sepete eklenir ve sepetin toplam tutarı otomatik olarak hesaplanır. Kullanıcılar, sepetteki ürünleri kolayca görebilir ve ödeme işlemi için "Satın Al" butonunu kullanabilirler.

### Anasayfa Görünümü
- **Ürün Ekleme**: Ürün barkodunu tarayarak hızlıca ürün ekleyebilirsiniz. Ayrıca, ürün adı, fiyat ve miktar bilgilerini de manuel olarak girebilirsiniz.
- **Sepet Görüntüleme**: Sepetinizdeki tüm ürünleri, miktarlarını ve toplam tutarı anlık olarak görebilirsiniz.
- **Barkod Okuma**: QR kod veya barkod tarama işlemi, kullanıcıların hızlıca işlem yapmasını sağlar.

## Teknolojiler

Bu proje, aşağıdaki teknolojiler kullanılarak geliştirilmiştir:

- **Backend**: 
  - **Laravel**: PHP tabanlı modern bir framework olup, veritabanı yönetimi ve backend işlevlerini sağlar.
  - **MySQL**: Ürün verileri ve sepet bilgileri için kullanılan ilişkisel veritabanı yönetim sistemi.

- **Frontend**: 
  - **Quasar Framework**: Vue.js tabanlı, hızlı ve şık bir kullanıcı arayüzü sunan framework.
  - **ZXing Modülü**: Barkod tarama işlemini gerçekleştiren kütüphane.

## Kullanıcı Deneyimi

Barkodlu kasa uygulamanız, alışveriş sürecini oldukça basit ve hızlı hale getirir. Sepete ürün eklerken veya ödeme yaparken kullanıcı dostu bir deneyim sunulur. 

- **Barkod Tarama**: Kameradan barkod tarayarak ürünleri hızlıca sepete ekleyebilirsiniz.
- **Hızlı Ürün Ekleme**: Ürün adı, barkod ve fiyat bilgilerini hızlıca girebilirsiniz.
- **Toplam Tutar Hesaplama**: Sepete eklenen ürünlerin toplam tutarı otomatik olarak hesaplanır.

## Proje Amacı

Bu proje, özellikle perakende sektöründe, mağaza sahiplerinin ve satış noktası çalışanlarının işlerini kolaylaştırmayı amaçlar. Barkodlu kasa uygulaması, ürünleri hızlıca eklemeyi ve satış işlemlerini hızlı bir şekilde tamamlamayı sağlar. Bu sayede kullanıcılar daha verimli çalışabilir ve zaman kaybını en aza indirir.

## Uygulamanın Kullanım Alanları

- **Perakende Mağazalar**: Mağaza çalışanları için hızlı ve kolay bir ödeme işlemine olanak tanır.
- **Online Satış Noktaları**: Online satış işlemleri için barkod tabanlı ürün eklemeleri sağlar.
- **Alışveriş Merkezleri**: Büyük alışveriş merkezlerinde hızlı ödeme ve kasa işlemleri için idealdir.

## Sonuç

Bu barkodlu kasa uygulaması, her seviyedeki kullanıcı için hızlı ve etkili bir alışveriş deneyimi sunar. Kullanıcı dostu arayüzü ve hızlı barkod okuma işlevi ile alışveriş süreçlerini daha verimli hale getirir.
