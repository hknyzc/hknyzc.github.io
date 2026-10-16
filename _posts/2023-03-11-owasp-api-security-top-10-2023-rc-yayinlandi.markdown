---
title: OWASP API Security Top 10 2023 RC Yayınlandı
layout: post
date: 2023-03-13 10:44
tag:
- API Security
- AppSec
star: false
category: blog
author: hakanyazici
---

![Resim](https://media.licdn.com/dms/image/D4D12AQFT9YxD57XKcw/article-cover_image-shrink_720_1280/0/1678628255020?e=1684368000&v=beta&t=LCoqxLRBrbW6SEuOVx-GsnLO7w40kFx9GYQ6DWiNxd4)

OWASP API Güvenlik Projesi ekibi, OWASP API Güvenliği İlk 10 2023 için hazırladıkları aday listeyi duyurduğunu belirtti. Açık Web Uygulaması Güvenlik Projesi (OWASP) tarafından açıklandığı gibi, API'ler modern uygulamaların kritik bir parçasıdır. API'ler farklı yazılım programlarının birbirleriyle iletişim kurmasına ve müşterilere, iş ortaklarına ve şirket içi ekiplere hizmet sağlamasına olanak tanırlar. API Güvenliği, Uygulama Programlama Arayüzlerinin (API'ler) güvenlik açıklarını, yanlış yapılandırmayı ve güvenlik risklerini azaltmaya yönelik stratejilere odaklanır. Güvenli API'ler olmadan, kuruluşlar ve tüketicileri çevrimiçi bir saldırıya kurban gitme riskiyle karşı karşıyadır. OWASP API Güvenliği İlk 10, kuruluşların API'leriyle ilişkili riskleri ve tehditleri ve bunları nasıl güvence altına alacaklarını anlamalarına yardımcı olan kapsamlı bir kılavuzdur.

# OWASP TOP 10 API 2019 ve OWASP TOP 10 API 2023 Arasındaki Farklar

OWASP API Top 10, geliştiricilerin API'lerle ilişkili en yaygın güvenlik risklerini anlamasına ve ele almasına yardımcı olmak için tasarlanmıştır. 2019'da hazırlanan liste aşağıdaki 10 riski içermekteydi:

1. Hatalı Nesne Düzeyinde Yetkilendirme (Broken Object Level Authorization) 
2. Bozuk Kullanıcı Kimlik Doğrulaması (Broken User Authentication) 
3. Aşırı Veri Teşhiri (Excessive Data Exposure) 
4. Kaynak Eksikliği ve Hız Sınırlaması (Lack of Resources & Rate Limiting) 
5. Hatalı Fonksiyon/Metod Seviyesi Yetkilendirmesi (Broken Function Level Authorization) 
6. Toplu Atama (Mass Assignment) 
7. Yanlış Güvenlik Yapılandırması (Security Misconfiguration) 
8. Enjeksiyon (Injection) 
9. Uygunsuz Varlık Yönetimi (Improper Assets Management) 
10. Yetersiz Kayıt ve Yetersiz İzleme (Insufficient Logging & Monitoring)

OWASP API Security Top 10 2023 RC ise, OWASP API Top 10 2019'un güncellenmiş bir sürümüdür. Yeni sürüm, değişen tehdit ortamını yansıtacak ve son sürümden bu yana ortaya çıkan yeni saldırı vektörlerini ele alacak şekilde oluşturuldu ve yayınlandı. OWASP API Security Top 10 2023 RC ise aşağıdaki 10 riski içerir:

1. Nesne Düzeyinde Hatalı Yetkilendirme (Broken Object Level Authorization) 
2. Hatalı Kimlik Doğrulaması (Broken Authentication) 
3. Nesne Özellik Düzeyindeki Hatalı Yetkilendirme (Broken Object Property Level Authorization ) 
4. Sınırlandırılmamış Kaynak Tüketimi (Unrestricted Resource Consumption ) 
5. Hatalı Fonksiyon/Metod Seviyesi Yetkilendirmesi (Broken Function Level Authorization) 
6. Sunucu Tarafı İstek Sahtekarlığı (Server Side Request Forgery) 
7. Yanlış Güvenlik Yapılandırması (Security Misconfiguration) 
8. Otomatik Tehditlere Karşı Koruma Eksikliği (Lack of Protection from Automated Threats) 
9. Yanlış Varlık Yönetimi (Improper Inventory Management) 
10. API'lerin Güvenli Olmayan Tüketimi (Unsafe Consumption of APIs)

# Farklara Bakış

OWASP API Security Top 10 2023 RC, aşağıdakiler gibi önceki sürümde bulunmayan yeni güvenlik risklerini içerir: 

***API3:2023 Nesne Düzeyindeki Hatalı Yetkilendirme***, ***API3:2019 Aşırı Veri Teşhiri*** veya ***API6:2019 Toplu Atama*** yoluyla hassas bilgilere yetkisiz erişim elde eden saldırganları bir araya getirdi . Her iki strateji de yetkisiz ve genellikle hassas verilere erişim elde etmek için API uç noktalarını manipüle etmeye odaklanıyordu.

***API4:2019 Kaynak Eksikliği ve Hız Sınırlaması***, ***API4:2023 Sınırlandırılmamış Kaynak Tüketimi*** olarak yeniden sınıflandırıldı ve bant genişliğini, CPU'yu, belleği veya bir API'nin belirli bir zamanda tüketebileceği depolama miktarını sınırlamaya karşı hız sınırlamaya odaklandı. Bu değişikliğin nedeni basitti, bazı API'ler hangi verileri paylaştıklarına bağlı olarak daha sıkı politikalara ihtiyaç duyar. API'ler, sistemler arasında sürekli olarak büyük miktarda veri ve hatta dosya paylaşmaya çalışan üçüncü taraf hizmetleri tarafından tüketiliyor ve sistem performansının etkilenmemesini veya bilgi işlem kaynaklarının aşırı tüketilmemesini sağlamak için daha katı politikalar gerektiriyor.

***API6:2019 Toplu Atama***, ***API6:2023 Sunucu Tarafı İstek Sahtekarlığı*** olarak yeniden sınıflandırılıyor , her ikisi de API'leri manipüle etmeye odaklanıyor. En büyük fark, Sunucu Tarafı İstek Sahteciliği API'deki çeşitli URI'leri test ederek dahili hizmetleri keşfetmek için kullanılırken Toplu Atama, verileri altyapıya karşı ortaya çıkarmak için API'leri keşfeder.

***API8:2023 Otomatik Tehditlere Karşı Koruma Eksikliği***, Enjeksiyona odaklanan API8:2019'dan bu yana önemli bir değişikliktir . Bu, API'lerden nasıl yararlandıkları konusunda daha akıllı olan, işletmeyi etkileyen işlevselliklerin yanı sıra uygulama hatalarını hedefleyen otomatikleştirilmiş bot ağları oluşturan saldırganlara bir yanıttır. 

***API9:2023 Yanlış Varlık Yönetimi***, veri akışı kör noktalarını ortadan kaldırmak ve ortamdaki tüm genel, özel, iş ortağı ve entegre API hizmetlerini izlemek için beklenen API kullanımını belgeleme ihtiyacını bilerek vurgulamak için ortaya çıkartılmıştır. Saldırganlar, üçüncü taraf API'lerdeki güvenlik açıklarından yararlanıyor ve bu API hizmetlerini kullanan kuruluşlar, veri ihlallerinin kurbanı oluyor. 

***API10:2023 Güvenli Olmayan API Tüketimi***, ***API10:2019'dan Yetersiz Günlük Kaydı ve İzlemeye*** odaklanan bir değişimdi . Güvenli Olmayan Tüketim API'leri, eylemlerin günlüğe kaydedilmesiyle şüpheli etkinliği izleme yeteneği yerine, üçüncü taraf API'lerle entegre olmayı seçerken daha fazla risk farkındalığına duyulan ihtiyacı vurgumaktadır. API Saldırıları, gerçek kullanıcı etkinliğini giderek daha fazla taklit ediyor. Bunun yerine, saldırganlar hassas verilere erişmek için üçüncü taraf API'lerdeki güvenlik açıklarından yararlanıyor.  

Bu değişiklikler, saldırganların modern uygulamalarımızı ve çevrimiçi hizmetlerimizi yönlendiren özel, genel ve üçüncü taraf API hizmetlerinden yararlanmak için stratejilerini nasıl geliştirdiğini vurgulamaktadır. Yukarıdaki değişiklikler ayrıca, kuruluşların üçüncü taraf hizmetleri seçerken daha fazla risk bilincinde olmaları, uygulanan API'lerin tüm yönlerini belgelemeleri ve API'lerin güvenli bir şekilde kullanılmasını sağlamak için koruma mekanizmalarını oluşturmaları için API Güvenlik programlarını nasıl olgunlaştırmaları gerektiğini belirtir.  

Şu an OWASP, API İlk 10 2023'ü her ne kadar aday olarak yayınlamış olsa da 4 yıllık bir sürede API Güvenliği'nin nasıl bir değişime uğradığını da net bir şekilde bizlere sunuyor. Aday olarak yayınlanan bu listeye sizin de önerilerde ve geribildirimlerde bulunma imkanınız mevcut.

Önümüzdeki günlerde netleşecek olan bu yeni API İlk 10 listesinin maddelerini de detaylı bir şekilde ele alacağım yazılarımı ve geçmişte hazırlamış olduğum yazıları da web sitemi olan https://hy.net.tr adresinde ulaşabilirsiniz. 

Ayrıca API, Uygulama Güvenliği ve DevSecOps konularında fikir alışverişi için bana her zaman ulaşabilirsiniz.

Kaynak: https://owasp.org/www-project-api-security/announcements/2023/02/api-top10-2023rc
