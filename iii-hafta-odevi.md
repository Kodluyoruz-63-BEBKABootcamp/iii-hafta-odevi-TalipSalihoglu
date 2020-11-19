## .Net kodu nasıl derlenir?
 Kodunun çalışabilmesi için öncelikle C# derleyicisi (Roslyn) tarafından derlenmesi gerekmektedir. Kod derlendikten sonra elimizde MSIL(Microsoft Intermediate Language), CIL (CommonIntermediate Language) yani bir IL (Intermediate Language) oluşur. Oluşan IL (MSIL, CIL) kodunun çalıştırılabilmesi için .NET Framework içerisinde yer alan CLR’a (Common Language Runtime) ihtiyacımız vardır. CLR JIT(Just In Time) derleme yaparak IL kodumuzu makine diline dönüştürür.

## Roslyn Complier 
.NET Compiler Platform (Roslyn) çözümleyiciler stil, kalite, bakım, tasarım ve diğer sorunlar için C# veya Visual Basic kodunuzu inceler. Bu denetleme veya analiz, tüm açık dosyalardaki tasarım zamanı sırasında yapılır.

## Restful servisler nasıl çalışır ve alternatifleri nelerdir?
REST, client-server arasındaki haberleşmeyi sağlayan HTTP protokolü üzerinden çalışan bir mimaridir. REST ,servis yönelimli mimari üzerine oluşturulan yazılımlarda kullanılan bir transfer yöntemidir.İstemci ve sunucu arasında XML ve JSON verilerini taşıyarak uygulamanın haberleşmesini sağlar.REST mimarisini kullanan servislere ise RESTful servis denir.
SOAP(en: Simple Access Protocol ,tr: Basit Nesne Erişim Protokolu) en temel anlamda, internet üzerinden küçük miktarda bilgileri yada mesajları aktarma protokoludur. SOAP mesajları XML formatındadırlar ve genellikle HTTP(Hyper Text Transfer Protocol) protokolu(bazende TCP/IP) kullanılarak gönderilirler. SOAP ,XML tabanlı kullanıma mecbur bırakır. Bu konuda esnek değildir.

## Extension Method
Extension methodlar genişletilebilir methodlardır. Herhangi bir tip üzerinde herhangi bir değişikliğe uğratmadan genişletilebilir olmasını sağlayabiliriz.Extension Method oluşturmak için önemli özellikler:
* Public static bir class 

* Oluşturmak istediğimiz method da static olarak tanımlanmalıdır.

* Methodu oluştururken hangi tip üzerinde bu metodun çalışmasını sağlayacağımızı this keyword’ü ile belirlemeliyiz.

## MVC'nin alternatifleri nelerdir?

* HMVC - Hierarchical Model-View-Controller
* MVVM - Model-View-ViewModel
* MVP - Model View Presenter
* MVA - Model View Adapter
* PAC - Presentation Abstraction Control
* RMR - Resource-Method-Representation
* ADR - Action-Domain-Responder

## Architectural Pattern nedir?
Yazılımlar mimari yapılara çok benzer. Bileşen, Servis, vb yapılarından oluşan uygulamaların Yapısı,Davranış şekilleri, Birbirleri İle İletişim Şekilleri gibi özellikler benzer problemler oluşturur. Bu problemleri gidermek için kullanılan, sistemin tamamında benzer örneklerin görüldüğü çözümlere/yapılara Mimari örüntüler denir.

## ViewData,ViewBag,TempData Farkları?
Bu nesnelerin kullanım amacı küçük boyutlardaki verilerimizi Controller dan View kısmına aktarmaktır. ViewData Dictionary tipindedir.Fakat ViewBag asp.net mvc 3 ile birlikte gelen yeni ve runtime içerisinde oluşan dinamik bir nesnesidir.ViewData ve ViewBag nesnesi o anki HTTP istek içerisinde geçerlidir. Yaşam döngüsü bir sonraki isteğe kadardır. Ama TempData Yaşam döngüsü o anki ve bir sonraki HTTP istek içerinde geçerlidir.
