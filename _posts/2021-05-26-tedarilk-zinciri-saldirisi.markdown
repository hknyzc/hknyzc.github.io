---
title: Tedarik Zinciri Saldırısı (Supply Chain Attack)
date: 2021-05-26 09:00
tags:
- DevSecOps
- AppSec
- Uygulama Güvenliği
star: false
category: blog
author: hakanyazici

---
![Resim](https://miro.medium.com/max/1684/0*yCU4CQz-FpfFZXTH)


Bu yazımda size Tedarik Zinciri ve saldırıları hakkında bilgi vermek istiyorum. Öncelikle “Tedarik Zinciri nedir?” biraz ondan bahsetmeliyim.

# Tedarik Zinciri Nedir ?
Bilişim sektöründe “Tedarik Zinciri” dediğimiz kavramı, ürünler ya da hizmetlerin tedarikçiden müşteriye doğru hareketlerini kapsayan ve bu süreç içerisindeki grupları, insanları, teknolojileri, faaliyetleri ve kaynakları kapsayan sistemlerin bütününe verilen isimdir.
Şirketlerin maliyetlerini düşürüp, rekabetçi iş ortamında kalabilmek için tedarik zincirlerini geliştirirler. Optimize edilmiş bir tedarik zinciri daha düşük maliyetler ve daha hızlı bir üretim döngüsü ile sonuçlandığından, tedarik zinciri yöntemi çok önemli bir süreçtir. Peki şimdi gelin biraz da bu sistemler bütününe yapılan saldırılardan bahsedelim.


# Tedarik Zinciri Saldırısı Nedir?
Tedarik zinciri saldırıları, tedarik zinciri ağındaki güvenlik açıklarından yararlanarak bir şirkete zarar vermeye çalışan bir siber saldırı girişimidir. Tedarik zinciri saldırısı, firmanın ağına erişim sağlamak için sürekli ağ korsanlığı veya sızma süreçleri sonucunda saldırılan şirkete zarar veren kesintilere yol açar.
Tedarik zincirlerinin birbirleri ile bağlanması ile risk daha da artmaktadır.Accenture 2020’de yapılan siber saldırıların %40’ının genişletilmiş tedarik zincirinden kaynakladığını belirtiyor.
Bir tedarik zinciri saldırısı, hedefteki şirkete zarar vermek için zincirdeki bir şirketin bilgisayar sistemlerine sızmaya ve bunları bozmaya çalışır. Buradaki fikir, hedef şirkete göre, şirketin kilit tedarikçilerinin veya satıcılarının saldırıya karşı daha savunmasız olabilmeleri ve bu da onları zincirin zayıf halkası olarak nitelendirilmesidir. Bu nedenle bu saldırılar bilgisayar korsanlığı girişimleri ile veya kötü amaçlı yazılım yerleştirme yoluyla ortaya çıkabilir ve ana hedeflere yapılan saldırılara göre daha yaygın olabilir.

# Tedarik Zinciri Saldırı Türleri
Bir tedarik zincirine saldırmanın birçok yolu bulunmaktadır. Bu saldırı türleri çok geniş kapsamlıdır. Aşağıda en yaygın türlerini özetleyeceğim.
## Yazılım Güncelleme Saldırısı
Tedarik zinciri saldırılarının en büyük tehditlerinden birisi yazılım güncellemeleri şeklinde gelir. Neredeyse her şirket, süreçlerinde birçok üçüncü parti yazılım çözümlerine bağımlıdır. Geçmişten günümüze bilgi teknolojilerindeki güvenlik uzmanları, yazılımın güvenlik açıklarının tehlikeleri konusunda uyarılarda bulunurlar. Bunun en kolay çözümü yazılımların güncellenmiş ve zaafiyetlere karşı yamaları yayınlanmış versiyonlarını kullanmaktır.
Peki bu güncelleme ve yamalar aslında tehlikenin ta kendisiyse ?
Tespit edilmesi gereken en zorlu tehditlerden biri, güvenlik açıklarının, istismarların ve hatta kötü amaçlı yazılımların kasıtlı olarak yazılım güncellemelerine dahil edilmesidir.
Tabii ki hiçbir şirket bunu kasıtlı olarak yapmaz. Ancak bir şirket ve geliştirme ortamı tehlikeye düştüyse, kötü niyetli biri yazılım güncellemesine bir dizi kötü amaçlı kod yazılım enjekte edebilir. Sisteme gönderilen bu güncelleme sayesinde kötü amaçlı kod ağınızın tamamına yayılmaya başlar.
Geçtiğimiz yıl gerçekleşen SolarWinds saldırısı bu türe ait örneklerin en günceli ve en güçlülerindendir. Bu atakta yer alan virüslü güncelleme, sayısı bilinemeyecek kadar çok işletmede ve hatta ABD devlet kurumlarında bilinmeyen sayıda sisteme yayıldı. Saldırı oldukça karmaşık olduğundan hasarın ne kadar derinleştiği hala bilinmemektedir.
Bu tür saldırılar acımasız olduğu kadar uygulanması da zordur. Kötü amaçlı yazılımları meşru bir yazılım güncellemesine yerleştirme için o şirkette yeterli erişim elde etmek kesinlikle çok uzun soluklu ve zor bir süreçtir.
## Önceden Yüklenmiş Kötü Amaçlı Yazılım İçeren Cihazlar
Diğer bir tedarik zinciri saldırı tehdidi iste altyapınıza eklediğiniz fiziksel cihazlardan gelir. Cihazların önceden yüklenmiş kötü amaçlı yazılımlarla gönderildiği çok sayıda senaryo bulunmaktadır. 2015 yılında ortaya çıkan Superfish skandalı da bu saldırıya en büyük örneklerden biridir.
Ayrıca zaman zaman bazı hükümetlerin bile önceden yüklenmiş kötü amaçlı yazılımların bulunduğu USB sürücüleri ile bağlantılı oldukları gündeme gelmektedir.
## Üçüncü Parti Hesaplarının Çalınması ve/veya Kaybı
Bilgi güvenliği yöneticilerinin üzerinde durması gereken açık ara en önemli tehdit, kendi işgücünün sahip olduğu kötü alışkanlıklardır. İzin verildiği takdirde personeller korkunç diye tabir edebileceğimiz parolalar kullanır, bunları belirli sürelerle değiştirmez ve hatta açık bir şekilde bir yerlere yazarlar. İnandırıcı olmasa bile oltalama e-postalarına tıklarlar. Bunlar bu tehlikenin sadece ufak bir kesiti.
Sorun şu ki, aynı sorun üçüncü parti hizmet personelleri için de geçerlidir. Bazı işlemler için, başka bir yolu olmadığından, onlara hassas verilere erişim sağlayan hesap bilgilerinin verilmesi gerekebilir. Kötü niyetli kişiler bu hesaplara ait bilgileri ele geçirirse sizin için inanılmaz sonuçlar yaratabilecek zararlar meydana gelebilir.
2013 yılında ortaya çıkan bir ihlalde, kötü niyetli kişiler doğrudan birincil hedefe saldırmadılar. Tek yaptıkları şey sistem bakım personelinin hesap bilgilerini çalmaktı. Sonrasında müşteri bilgilerinden oluşan bir hazineye girmeleri için gereken kapıyı aralamış oldular.
Şimdiye kadar tedarik zinciri saldırıları için kullanılan yollardan sadece en önemli üçünü ele aldık. Bunlar gibi daha nice saldırı yollarını kısa bir araştırma ile sizin de bulmanız mümkün.

# İşletmenizi Tedarik Zinciri Saldırılarından Korumak İçin Bazı Öneriler
Tedarik zinciri saldırıları hakkında şu anda bildikleriniz göz önüne alındığında, büyük olasılıkla şirketinizin bunları önlemek için neler yapabileceğini merak ediyorsunuz.
İşte risk yönetimi için bazı stratejiler:
## Yazılım Kurulum Yetkilerini Kontrol Edin
Her türlü yazılım yükleme yetkilerinin belirlenmiş olması gerekir, ki bu kurumsal işletmelerde zahmetsizdir. Yazılım kurulumu ve güncellemeleri için yetkilendirme yapabileceğiniz yönetici güvenlik kontrollerini veya BT araçlarını kullanın. Güvenlik ekibinin bu yüklemeleri onaylamadan önce dikkatlice incelemesi gerekmektedir.
## Dosya ve Ağ Erişimine Katı Bir Denetim Uygulayın
Her çalışanın her dosyaya erişmesi gerekmediği gibi aynı durum üçüncü parti hizmet personelleri için de geçerlidir. Üçüncü parti personelinin yalnızca ihtiyaç duydukları veriye erişebildiğinden ve başka bir işlem yapamadıklarında emin olun.
## Tedarik Zincirinizi İnceleyin ve Haritalandırın
 - BT tedarik zincirinizi net bir şekilde anlıyor musunuz?
 - Saldırı yüzeyini tedarik zincirinizle bağlantılı olarak azaltmak için nerede iyileştirmeler yapabilirsiniz?
 - Üçüncü parti bağlantılarınız en katı siber güvenlik standartlarına uygun mu ?
 - Yazılım derleme sürecini nasıl yönetiyorlar ?

Maalesef ki, birçok işletme bu soruların cevaplarına sahip değildir. Bu zincirin halkalarının ne yaptığını ve neye erişimlerinin olduğunu belirlemek için zaman ayırın. Kontrol listesi ve güvenlik anketleri hazırlayın. Zincirin halkalarına verilerinizi güvende tutmak için yaptıklarıyla ilgil rahatsız edici sorular sormaktan çekinmeyin. Sözleşmelerinizde güvenlik beklentileri oluşturmayı düşünün. Ek olarak, zincirinizin halkaları iki faktörlü kimlik doğrulamayı etkinleştirirlerse tehdit aktörleri için ek bir uçurum daha oluşturulmuş olur.
## Birbirleriyle Bağlantılı Cihazlar İçin Güvenlik Stratejisi Geliştirin
Gün geçtikçe daha fazla sayıda cihaz internete açılıyor. Bu cihazların birbirleri arasındaki bağa Nesnelerin İnterneti (IoT) adı veriliyor. Sağlam işlevsellikleri ve yüksek performans sağladıkları için günümüzde bunların kullanılması zorunlu bir hal almış durumda. Ancak bu durum büyük bir de risk getiriyor: Bağlı her cihaz potansiyel bir güvenlik tehdididir.
Onları yasaklayamayacağınız için yönetmeyi öğrenmelisiniz. Bu cihazlar için bir siber güvenlik stratejisi geliştirmeye yatırım yapın.
## Kendinizi ve Ekibinizi Sürekli Eğitin
Ağınızın güvenliğini sağlamak, en son tehditlere ve tehdit vektörlerine ayak uydurmak için hem güçlü teknik bilgi hem de dikkatli olmayı gerektirir. BT uzmanlarının hazırlıklı olduğu tehlikelerden çok daha fazlası gün geçtikçe ortaya çıkıyor.
Tedarik zinciri saldırıları dahil olmak üzere siber saldırıları önlemek için gerektiği kadar hazır mısınız? Altyapınızın içinde nereye bakacağınızı biliyorsanız ele alınması gereken bazı kör veya zayıf noktalar keşfedebilirsiniz. Nereye bakacağınızı bilmiyorsanız ya da profesyonel bir yardıma ihtiyacınız var ise benimle iletişime geçebilirsiniz.

 **Hakan Yazıcı <br>Uygulama Güvenliği Mühendisi**<br>
 **Endpoint Bilgi Teknolojileri Güvenliği ArGe A.Ş - 2021**<br>
 **LinkedIn: https://www.linkedin.com/in/hakan-yazici/**<br>
 **Kaynakça: https://www.office1.com/blog/supply-chain-attack**<br>
