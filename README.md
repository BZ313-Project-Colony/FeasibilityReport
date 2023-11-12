# FeasibilityReport
### Grup Üyeleri
- Ahmet Faruk Çuha - 1030510500@erciyes.edu.tr
- İrem Tapsız - 1030510605@erciyes.edu.tr
- Semih Çay - 1030510327@erciyes.edu.tr
- Mustafa Umut İdam  - 1030510310@erciyes.edu.tr
- İsa Uçar - 1030510306@erciyes.edu.tr
- Elif İrem Keskin - 1030510558@erciyes.edu.tr
- Batuhan Erol - 1030510326@erciyes.edu.tr
- Sümeyye Korkmaz - 1030510287@erciyes.edu.tr

### Müşteri
Talha Yasin Aydın <br>
VoltaCar Elektrik Birim Başkanı <br>
Erciyes Üniversitesi Elektrik-Elektronik Mühendisliği <br>
1030210690@erciyes.edu.tr

## Proje Adı
QR Pass

## Amaç
Proje, davet ve etkinlik düzenlemelerinde QR teknolojisini kullanarak, davet oluşturup katılımcılarla organizasyon arasındaki iletişimi sağlayabilecek bir uygulama geliştirmeyi, böylece elle veri girişinin azaltılarak hata olasılığının azaltılması amaçlıyor. Ürün, iki tip kullanıcıya hitap etmektedir. Yönetici etkinlik ve etkinlik daveti oluşturma, davetlileri düzenleyebilme, davetli sayısının ve girişinin takibini sağlayabilme eylemlerini yapabilirken; kullanıcı oluşturulan etkinliğe kayıt gerçekleştirebilmelidir.

## Üstlenilecek Görevler
Proje yönetimi kısmında grup üyelerinin görevleri aşağıdaki maddeleri içermektedir

 - Projenin yürütülmesi sırasında bilgilendirme toplantıları düzenlemek, sunumlar gerçekleştirmek, 
 - Proje raporlarını düzenlemek, 
 - Projenin uygulanmasında ortaklar ve paydaşlar ile ilişkileri düzenlemek
 - Uygulama geliştirmek

Proje web ve mobil olmak üzere iki ana tabandan oluşmaktadır.
Web geliştirme kısmında

 - Etkinlik oluşturma arayüzü hazırlanması
 - Katılımcıların kayıt bilgilerini uygulamaya aktarabilecek bir kayıt sayfası oluşturulması
 - Her katılımcıya özel QR kodunun oluşturulması ve sistemde tutulması
 - Yöneticinin bütün katılımcılara davet mailini sorunsuzca atabileceği sistemin oluşturulması

Mobil geliştirme kısmında

 - QR okuma sistemi
 - Etkinliğe katılım gösteren katılımcıların bilgilerinin uygulamaya aktarılması 

sorunları çözülüp uygulama geliştirilecektir.

##  Faydalar
Organizasyonlarda katılımcı sayısının çokluğu sebebiyle katılımcıların etkinlik alanına girişlerinin takip edilmesi ve bilet bilgilerinin düzenli bir şekilde bir arada tutulması ve katılımcılara davet gönderilmesi zorlaşmaktadır. QR Pass müşterisi olanlar etkinliklerini tek bir siteden takip edebilecek. 

 1. Müşteri çok sayıda katılımcıya tek seferde davet gönderebilecek.
 2. Katılımcı olmak isteyenler site üzerinden form doldurarak etkinliklere başvurabilecekler.
 3. Geçmiş veya gelecek etkinliği seçip etkinlik katılımcılarını ve onların biletlerini görüntüleyebilecek.
 4. Biletleri ve QR kodları müşterilere bu site üzerinden gönderebilecek.
 5. Etkinlik alanına girişte katılımcıların biletlerini QR kod üzerinden mobil uygulamamızla kolayca takip edebilecek.

## Ön Gereksinim Analizi
Sistemin aşağıdaki işlevsel gereksinimleri karşılaması gerekir:
#### Web Arayüzü

##### Yönetici tarafı
- İçerisinde; etkinlik adı, tarihi, saati, mekânı, katılacak maksimum kişi sayısını içeren ve resim ekleyebildiği bir “Etkinlik” oluşturabilir.
- Eklediği “Etkinlikleri” listeleyip görebilir.
- Kullanıcıların Etkinliğe katılımı için her bir Etkinliğe özel olan kayıt linkini kopyalayabilir.
- Her bir Etkinliğin içerisindeki Etkinliğe kaydolan katılımcıların bilgilerini ve katılımcı sayısını ve okunmuş QR sayısını görebilir.
- Dilerse maksimum kişi sayısı dolmadan Etkinlik alımlarını kapatabilir.
- Dilerse oluşturduğu Etkinliği silebilir. ​
- Kendi kimliğiyle sisteme giriş yapar.

##### Katılımcı Tarafı
- Etkinliğe özel Url’den etkinlik bilgilerini görüntüleyebilir.
- Etkinliğe kaydolmak için ad, soy ad, e-posta bilgilerini gönderebilir.
     
#### Mobil Arayüzü
##### QR Okuyucu Kişisi tarafı
1. Kullanıcı adı ve şifre ile giriş yapılır.
2. Yöneticinin oluşturduğu Etkinlikleri listeleyip Etkinlik bilgilerini görebilir.
3. Her bir Etkinliğin içerisindeki Etkinliğe Kaydolan kullanıcıların bilgilerini ve QR okutma durumlarını (okuttu, onaylandı / okutmadı / okuttu, onaylanmadı) görebilir.
4. Her bir Etkinliğe ve katılımcıya özel QR’ları kamerayla okutup kendi inisiyatifiyle sisteme kaydeder veya kaydetmez.
5. Hem yöneticinin hem de gelecekteki geliştiricilerin bakış açısına göre kolayca genişletilebilir olmalıdır.

Sistem aşağıdaki işlevsel gereksinimlere sahip olabilir:  
1. Yönetici sonradan etkinlik bilgilerini güncelleyebilir.
2. Katılımcı sonradan kendi bilgilerini güncelleyebilir ya da silebilir.
 
  İsteğe Bağlı
1. Aynı Katılımcı birden çok kez kayıt oluşturmasın diye Katılımcı Arayüzünde e-posta kontrolü gerçekleştirilebilir.
2. QR Okuyucu Arayüzüne girişi onaylanmayan kullanıcıyı sonradan onaylanabilir hale getirilebilir.

## Teknik Gereksinimler (Fizibilite)
1. PaaS (Platform Cloud Service) - Heroku: Java Spring Boot ile oluşturduğumuz QRPass web servisimizi popüler, kullanışlı ve ucuz bir PaaS platformu olan Heroku üzerinde çalıştıracağız.
2. Veritabanı: Postgres: Etkinlik ve bilet bilgilerini depolamak için açık kaynak ve Java ile uyumlu olan Postgres veritabanını kullanacağız.
3. Mail Sender Library : Spring Boot Starter Email : Kullanıcıların maillerine kaydoldukları etkinliklere dair etkinlik bilgilerini ve QR kodlarını içeren bilet içeriğini güvenli bir şekilde mail yoluyla gönderebilmek için bu kütüphaneyi kullanacağız.
4. Hosting : Firebase Hosting:  QRPass admin paneli ve etkinlik kayıt formu olarak geliştireceğimiz iki ayrı frontend web projesini Firebase Hosting aracılığıyla host edeceğiz.
5. Flutter QR Scanner Library: Katılımcıların maillerine gelen QR kodlarını okuyup bilet durumlarını değiştirebilmek amacıyla oluşturacağımız mobil uygulamamızda development süresini kısaltmak adına hazır QR Scanner kütüphanesi kullanacağız.

## Kapsam
Projenin genel amaçları yukarıda belirtilmiş olup bu amaçlar doğrultusunda Erciyes Üniversitesi Kulüp faaliyetlerini kolaylaştırmak ve hızlandırmak için üniversite öğrencilerini kapsayan “QR Pass” yazılım projesine başlanmıştır. Projenin kapsamı belirtilen amaçlar doğrultusunda sınırlanmış olup net bir şekilde belirlenmiştir. Proje kapsamında 2 farklı arayüz yapılması hedeflenmiştir. 1.Arayüz yönetim arayüzü olmakla beraber bu arayüz kulüp yöneticileri için planlanmıştır. Kulüp yöneticilerinin hızlı ve kolay bir şekilde kulüp faaliyetleri oluşturup yayınlamasını ve katılımcıların etkinliğe giriş takibi için katılımcılara hızlı bir şekilde QR kod göndermesini ve takip edilebilmesini sağlamaktadır. 2.arayüz ise etkinliklere katılmak isteyen öğrencilerin hızlıca kayıt oluşturabileceği arayüzü hedeflemektedir. Projenin genel kapsamları bu şekildedir. Kullanıcı verilerini sadece yönetici arayüzüne sunulması planlanmıştır bu kapsamda veri güvenliği hedeflenmiştir.

## Önerilen Teslimatlar
**Proje Teslimatları**

 -  *Proje Planı*: Proje için bir yol haritası görevi görmesi amacıyla hazırlanan belgeleri kapsayacaktır. Projenin kapsamını, hedeflerini, zaman planlamasını Gantt şeması, kilometre taşları, zaman çizelgesi ve SWOT analizi kullanarak görünür hale getirilecek; müşterinin ve grup üyelerinin ürün geliştirme ilerlemesi konusunda haberdar olması sağlanacak.
 - *Gereksinim Analizi*: Geliştirilecek yazılımın işlevsel ve işlevsel olmayan gereksinimlerini açıklayan ayrıntılı bir belge. Bu belge, ürünün müşterinin istekleri doğrultusunda geliştirilmesine katkı sağlayacak; bir hata veya değişiklik tespitinin kolayca yapılmasına yardımcı olacak.
 - *Tasarım Belgeleri*: Bu belgeler yazılım mimarisi ve tasarımı için bir plan sağlar. Sistem mimarisini, veri tabanı tasarımları ve kullanıcı arayüz tasarımlarını kapsayabilir. Bu belgeler müşteriye projenin nasıl uygulanacağının gösterilmesinde yardımcı olur, aynı zamanda 
 -  *Kaynak Kod*: Yazılım ekibi tarafından yazılan gerçek kod dosyaları. Kod iyi belgelenmeli ve kodlama standartlarına uygun olmalıdır.
 - *Test Dökümanları*: Yazılımın belirtilen gereksinimleri karşıladığını doğrulamak için test stratejisini ve özel test senaryolarını özetleyen belgeleri içerir. Agile geliştirme süreci benimsendiği için süreç boyunca testler yapılıp sorunların hızlıca çözülmesine yardımcı olması amaçlanmıştır.
 - *Kullanıcı Belgeleri*: Yazılımın nasıl kurulacağına, yapılandırılacağına ve kullanılacağına ilişkin talimatlar sağlayan kılavuz. Bu, müşteri ve kullanıcının sistemi anlamasına ve çalıştırmasına yardımcı olur.
 - *Bakım ve Destek belgeleri*: Yazılımın bakımına ve desteğine yardımcı olacak yönergeler ve belgelerden oluşacaktır. Bu, sorun giderme kılavuzlarını, SSS'leri ve güncellemeleri içerebilir. Projenin uzun süreli olup olmamasına göre bu teslimatın bulunurluk durumu değişiklik gösterebilir.
 - *Proje Kapanış Raporu*: Projenin bitirildiğini göstermek amacıyla süreç özetini ve sonuçları özetleyen belge. Kapanış belgesinde projenin özeti, başarıları, zorlukları ve öğrenilen dersleri vurgulanacak ve bu bilgiler müşteri ve projeyle ilgilenen diğer paydaşlarla paylaşılacaktır. Rapor gelecekteki projeler için öneriler de içerebilir

**Ürün Teslimatları**

 - *Admin Paneli*: Adminin kullanıcı bilgilerini girip uygulamaya giriş yapabileceği panel. Adminin etkinlik bilgilerini düzenleyip etkinlik oluşturabildiği panel. Düzenlediği etkinliklerin bilgilerini tutulduğu ve admin tarafından görüntülenebildiği panel. Oluşturulan etkinliğe katılım talebi gönderen kişilerin bilgilerinin ve QR verisinin görüntülendiği, katılımcıların düzenlenebildiği, katılımcı sayısının sınırlandırılabildiği, katılım talebinin kapatılabileceği, tüm katılımcılara tek seferde QR içeren davet mailinin gönderilebildiği panel.
 - *Kayıt Web Paneli*: Sistemde oluşturulmuş olan etkinliklerin tarihe göre sıralandığı, katılımcının katılmak istediği etkinliği seçip bilgilerini görüntüleyebileceği panel. Etkinlik bilgilerinin görüntülenebildiği, katılımcının gerekli bilgileri girip etkinliğe katılım talebi oluşturabildiği panel.
 - *QR okuyucu mobil uygulama*: Uygulama tarafından katılımcıya gönderilen QR görüntüsünün okunup girişinin onaylanabileceği panel.
 - *QR API*: Katılımcıya özel QR oluşturulması. QR aracılığı ile katılımcıların tanımlanması. Katılımcıların etkinliğe giriş durumlarının takibi.
 - *Veri tabanı*: Admin bilgileri, etkinlik bilgileri, katılımcı bilgileri, QR bilgileri gibi uygulama içi verileri depolama. Admin ve kullanıcı verileri gibi kişisel verilerin 3. partilerden korunması. Verilerin birbiriyle ilişkilendirilmesi.


### Geçiş
...

## Yazılım Geliştirme Süreci
Proje, üniversite kulüplerinin etkinlik yönetimini optimize etmek ve katılım sürecini kolaylaştırmak amacıyla geliştirilmektedir. Projenin gereksinimleri genel olarak belirlenmiş olup müşterinin değişen istekleri doğrultusunda düzeltmelere açık şekilde ilerleyecektir. Yapılan yazılımın geliştirilmesi sürecinde gereksinim analizi, veri tabanı tasarımı, kullanıcı ve yönetici arayüzü geliştirme, QR kod oluşturma ve yönetme, e-posta bildirimleri, güvenlik, test ve hata düzeltme, dağıtım gibi adımların tamamlanıp planlanması yapılmıştır. Proje, agile(çevik) modelini benimsemekte ve bu yaklaşımın projenin başarısına katkı sağlayan çeşitli avantajları bulunmaktadır.

Proje, şu ana aşamalardan oluşan bir çevik geliştirme sürecini benimsemektedir:
*İlk Planlama ve Gereksinim Belirleme:*
Proje ekibi ve müşteri bir araya gelir, genel hedefleri belirler ve ilk iterasyonun planlamasını yapar.
*İlk İterasyon (Sprit):*
Kısa süreli bir süreç içinde, belirlenen gereksinimlere yönelik çalışmalar gerçekleştirilir ve minimum işlevsel bir ürün (MVP) oluşturulur.
*Müşteri Geri Bildirimi ve Güncelleme:*
Oluşturulan MVP müşteriye sunulur, geri bildirimler alınır ve gerekli güncellemeler yapılır.
*İkinci İterasyon ve Sonraki Adımlar:*
Süreç tekrarlanır, her iterasyon yeni gereksinimlere uyum sağlayacak şekilde geliştirilir.
*Sürekli Entegrasyon ve Test: *
Her iterasyon sonrasında sürekli entegrasyon ve test süreçleri uygulanır, böylece kalite kontrol sağlanır. 

Bu aşamalar, projenin belirlenen hedeflere ulaşabilmesi için adım adım ilerleyeceği bir süreci temsil etmektedir. Her aşama, belirli görevlere ve süreçlere odaklanarak projenin başarılı bir şekilde tamamlanmasına katkı sağlayacaktır. Ayrıca bu süreçte projede bulunan herkesin projenin hangi aşamasında olunduğu hakkında tamamıyla bilgi sahibidir. Proje şeffaf şekilde ilerlemekte ve takım çalışmasıyla yürütülmektedir.


### Taslak Plan (Temel Faaliyetler ve Kilometre Taşları)
...

### Görünürlük Planı
...

### Ticari Hususlar
...

### Risk Analizi
...

### Sonuç
...
