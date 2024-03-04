# .NET Core Rehberi
Bu rehber, .NET Core ile geliştirme yapmaya yeni başlayanlar için hazırlanmıştır. .NET Core'un temellerinden başlayarak kurulum sürecine kadar gerekli tüm bilgileri içermektedir.

## Giriş ve Kurulum

.NET Core, Microsoft tarafından geliştirilen açık kaynak bir yazılım geliştirme platformudur. Çapraz platform desteği ile Windows, macOS ve Linux üzerinde çalışabilir. Web, mobil, masaüstü ve mikroservisler dahil olmak üzere birçok farklı türde uygulama geliştirmek için kullanılabilir.

### .NET Core'un Avantajları

- Çapraz Platform Desteği: .NET Core, farklı işletim sistemlerinde çalışabilir.
- Yüksek Performans: Optimize edilmiş kod yürütme süreleri ile yüksek performans sunar.
- Açık Kaynak: Geliştirici topluluğunun katkılarıyla sürekli gelişir.
- Esnek Dağıtım: Uygulamalarınızı kendi içinde veya Docker konteynerlerinde dağıtabilirsiniz.

### .NET Core'un Tarihçesi ve .NET ile İlişkisi

NET Core projesi, Microsoft'un .NET teknolojisini Linux ve macOS gibi diğer işletim sistemlerinde de kullanılabilir hale getirme çabasının bir sonucu olarak ortaya çıktı. Bu, Microsoft'un .NET platformunu daha geniş bir kitleye ve farklı platformlara açma stratejisinin bir parçasıydı.

.NET Core 1.0: .NET Core'un ilk sürümü, Haziran 2016'da yayınlandı. Bu sürüm, Microsoft'un .NET platformunu Windows dışındaki işletim sistemlerinde çalışacak şekilde genişletme çabasının ilk meyvesiydi. .NET Core 1.0, temel .NET özelliklerini içeriyordu ve özellikle web ve sunucu uygulamaları geliştirmek için tasarlanmıştı.

.NET Core 2.0: Ağustos 2017'de yayınlanan bu sürüm, performans iyileştirmeleri ve API yüzeyinin genişletilmesi gibi önemli gelişmeler getirdi. .NET Standard 2.0 ile uyumluluk, geliştiricilere daha geniş bir API setine erişim sağladı ve .NET Framework ile daha iyi uyumluluğu mümkün kıldı.

.NET Core 3.0 ve 3.1: Eylül 2019'da yayınlanan .NET Core 3.0, masaüstü uygulama geliştirme (Windows Forms ve WPF) desteği gibi önemli yenilikler sundu. .NET Core 3.1 ise Aralık 2019'da LTS (Long Term Support) olarak yayınlandı ve stabilite ve performans odaklı iyileştirmeler içerdi.

.NET Core, .NET Framework'ün evrimleşmiş bir versiyonu olarak görülebilir. Microsoft, .NET Core ile birlikte, platformlar arası uygulama geliştirmeyi ve .NET ekosisteminin geleceğini şekillendirmeyi amaçladı. .NET Core'un başarısı ve geliştirici topluluğundan aldığı olumlu geri dönüşler, Microsoft'un .NET platformunu birleştirme ve tek bir .NET ekosistemine geçiş yapma kararında önemli bir rol oynadı.

.NET 5, .NET Core ve .NET Framework'ün geleceği olarak tanıtıldı ve Kasım 2020'de yayınlandı. .NET 5 ile, Microsoft .NET Core'un platformlar arası özelliklerini ve .NET Framework'ün zengin API yüzeyini birleştirerek, tek bir .NET çalışma zamanı ve geliştirme platformu oluşturma yolunda önemli bir adım attı. Bu birleşme, .NET 6, .NET 7 ve sonrasında da devam eden .NET'in gelecekteki sürümleriyle devam ediyor.

.NET Core, .NET'in evriminde kritik bir dönüm noktasıdır ve Microsoft'un yazılım geliştirme alanında daha açık, erişilebilir ve platformlar arası bir yaklaşım benimsemesinde önemli bir rol oynamıştır. Bu geçiş, geliştiricilere daha fazla esneklik ve seçenek sunarak .NET ekosisteminin büyümesine ve çeşitlenmesine olanak tanımıştır.

### .NET Core Kurulumu ve Gereksinimleri

.NET Core SDK'sının kurulumu için aşağıdaki adımları takip edin:
```
# Windows için
choco install dotnet-sdk

# MacOS için
brew install --cask dotnet-sdk

# Linux için
sudo apt-get install dotnet-sdk-3.1
```

### İlk .NET Core Uygulamasının Oluşturulması

İlk uygulamanızı oluşturmak için:

```
dotnet new console -o FirstApp
cd FirstApp
dotnet run
```

### Visual Studio ve Visual Studio Code ile .NET Core Geliştirme

## Temel Programlama Kavramları
### C# Dilinin Temelleri
### Değişkenler, Veri Tipleri ve Operatörler
### Kontrol Yapıları: Karar Yapıları ve Döngüler
### Metotlar ve Fonksiyonlar
### Hata Yakalama ve İstisna Yönetimi

## Nesne Yönelimli Programlama (OOP)
### Sınıflar ve Nesneler
### Miras Alma ve Polimorfizm
### Arayüzler ve Soyut Sınıflar
### Kapsülleme ve Erişim Belirleyiciler
### OOP İlkeleri ve .NET Core'daki Uygulamaları

## .NET Core ile Uygulama Geliştirme
### .NET Core Uygulama Türleri
### ASP.NET Core ile Web Uygulamaları
### Entity Framework Core ile Veritabanı İşlemleri
### MVC ve Razor Sayfaları
### Web API'leri ve RESTful Servisler
### Blazor ile İstemci Tarafı Uygulamaları

## İleri Seviye Konular
### Dependency Injection
### Middleware Katmanları
### Kimlik Doğrulama ve Yetkilendirme
### Unit Test ve Entegrasyon Testleri
### Performans Optimizasyonu ve Güvenlik En İyi Uygulamaları

## Ek Kaynaklar ve Projeler
### Örnek Uygulamalar ve Çalışma Projeleri
### .NET Core ile Mikroservis Mimarisine Giriş
### Bulut Tabanlı Uygulamalar ve Azure Entegrasyonu
### .NET Core Güncellemeleri ve Geleceği
### Topluluk ve Destek Kaynakları
