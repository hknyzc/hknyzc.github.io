---
title: En Tehlikeli 25 Yazılım Açığı Güncellendi
date: 2021-07-29 10:00
tags: 
- Uygulama Güvenliği
- mitre
- DevSecOps 
star: false
category: blog
author: hakanyazici

---

<span class="c13">MITRE, geçmiş iki yıl boyunca yazılımcıların başına bela olan en yaygın ve en tehlikeli açıkların ilk 25 listesini paylaştı.</span>

<span class="c13"></span>

<span class="c13">Yazılım zafiyetleri, bir yazılım çözümünün kodunu, mimarisini, uygulamasını veya tasarımını etkileyen ve üzerinde çalıştığı sistemleri potansiyel olarak saldırılara maruz bırakan kusurlar, hatalar, güvenlik açıkları ve diğer çeşitli hata türleridir.</span>

<span class="c13"></span>

<span class="c13">MITRE, Ulusal Güvenlik Açığı Veritabanından (NVD) (yaklaşık 27.000 CVE) elde edilen 2019 ve 2020 yıllarına ait Yaygın Güvenlik Açıkları ve Etkilenmeleri (Common Vulnerabilities and Exposures) verilerini kullanarak ilk 25 listesini güncelledi.</span>

<span class="c13"></span>

<span class="c13">MITRE tarafından yapılan açıklamaya göre “Bir CWE’nin bir güvenlik açığının temel nedeni olduğu sıklığı ile sömürünün öngörülen ciddiyetini birleştiren sıralı bir zayıflık sırasını hesaplamak için bir puanlama formülü kullanır. Bu yaklaşım, gerçek dünyada şu anda hangi güvenlik açıklarının görüldüğüne nesnel bir bakış sağlar, özel anketler ve görüşler yerine kamuya açık olarak bildirilen güvenlik açıkları üzerine kurulu bir analitik titizlik temeli oluşturur ve süreci kolayca tekrarlanabilir hale getirir.”</span>

<span class="c13"></span>

<span class="c13">MITRE'nin 2021'deki en önemli 25 hatası, genellikle keşfedilmeleri kolay, yüksek etkiye sahip oldukları ve son iki yılda piyasaya sürülen yazılımlarda yaygın oldukları için tehlikelidir.</span>

<span class="c13"></span>

<span class="c13">Ayrıca, saldırganlar tarafından, potansiyel olarak savunmasız sistemlerin tam kontrolünü ele geçirmek, hedeflerin hassas verilerini çalmak veya başarılı bir istismarın ardından bir hizmet reddini (DoS) tetiklemek için kötüye kullanılabilirler.</span>

<span class="c13"></span>

<span class="c13">Aşağıdaki liste, genel olarak topluluğa en kritik ve güncel yazılım güvenliği zayıflıkları hakkında fikir vermektedir.</span>

<span class="c13"></span>

<span class="c13"></span>

<a id="t.83140adf6283dde21ac70b63e9e496db9b1604cc"></a><a id="t.0"></a>

<table class="c28">

<tbody>

<tr class="c2">

<td class="c22" colspan="1" rowspan="1">

<span class="c4"> Sırası </span>

</td>

<td class="c33" colspan="1" rowspan="1">

<span class="c4">&nbsp; ID </span>

</td>

<td class="c23" colspan="1" rowspan="1">

<span class="c4">&nbsp; ADI </span>

</td>

<td class="c27" colspan="1" rowspan="1">

<span class="c4">&nbsp; Puanı</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[1]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-787](https://cwe.mitre.org/data/definitions/787.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Out-of-bounds Write</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">65.93</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[2]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-79](https://cwe.mitre.org/data/definitions/79.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Neutralization of Input During Web Page Generation ('Cross-site Scripting')</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">46.84</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[3]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-125](https://cwe.mitre.org/data/definitions/125.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Out-of-bounds Read</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">24.9</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[4]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-20]( https://cwe.mitre.org/data/definitions/20.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Input Validation</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">20.47</span>

</td>

</tr>

<tr class="c24">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[5]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-78](https://cwe.mitre.org/data/definitions/78.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">19.55</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[6]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-89](https://cwe.mitre.org/data/definitions/89.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection')</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">19.54</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[7]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-416](https://cwe.mitre.org/data/definitions/416.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1"> &nbsp;Use After Free</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">16.83</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[8]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-22](https://cwe.mitre.org/data/definitions/22.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal')</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">14.69</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[9]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-352](https://cwe.mitre.org/data/definitions/352.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Cross-Site Request Forgery (CSRF)</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">14.46</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[10]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-434](https://cwe.mitre.org/data/definitions/434.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Unrestricted Upload of File with Dangerous Type</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">8.45</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[11]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-306](https://cwe.mitre.org/data/definitions/306.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Missing Authentication for Critical Function</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">7.93</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[12]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-190](https://cwe.mitre.org/data/definitions/190.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Integer Overflow or Wraparound</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">7.12</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[13]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-502](https://cwe.mitre.org/data/definitions/502.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Deserialization of Untrusted Data</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">6.71</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[14]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-287](https://cwe.mitre.org/data/definitions/287.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Authentication</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">6.58</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[15]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-476](https://cwe.mitre.org/data/definitions/476.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;NULL Pointer Dereference</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">6.54</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[16]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-798](https://cwe.mitre.org/data/definitions/798.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Use of Hard-coded Credentials</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">6.27</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[17]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-119](https://cwe.mitre.org/data/definitions/119.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Restriction of Operations within the Bounds of a Memory Buffer</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">5.84</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[18]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-862](https://cwe.mitre.org/data/definitions/862.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Missing Authorization</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">5.47</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[19]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-276](https://cwe.mitre.org/data/definitions/276.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Incorrect Default Permissions</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">5.09</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[20]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-200](https://cwe.mitre.org/data/definitions/200.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Exposure of Sensitive Information to an Unauthorized Actor</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">4.74</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[21]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-522](https://cwe.mitre.org/data/definitions/522.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Insufficiently Protected Credentials</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">4.21</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[22]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-732](https://cwe.mitre.org/data/definitions/732.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Incorrect Permission Assignment for Critical Resource</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">4.2</span>

</td>

</tr>

<tr class="c3">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[23]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-611](https://cwe.mitre.org/data/definitions/611.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Restriction of XML External Entity Reference</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">4.02</span>

</td>

</tr>

<tr class="c9">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[24]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-918](https://cwe.mitre.org/data/definitions/918.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Server-Side Request Forgery (SSRF)</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">3.78</span>

</td>

</tr>

<tr class="c29">

<td class="c12" colspan="1" rowspan="1">

<span class="c4">[25]</span>

</td>

<td class="c16" colspan="1" rowspan="1">

<span class="c8">[CWE-77](https://cwe.mitre.org/data/definitions/77.html)</span>

</td>

<td class="c7" colspan="1" rowspan="1">

<span class="c1">&nbsp;Improper Neutralization of Special Elements used in a Command ('Command Injection')</span>

</td>

<td class="c15" colspan="1" rowspan="1">

<span class="c1">3.58</span>

</td>

</tr>

</tbody>

</table>

<span class="c13"></span>

<span class="c13"></span>

# <span class="c31">En çok yararlanılan 10 güvenlik açığı</span>

<span class="c13"></span>

<span class="c13">Geçen yıl, 12 Mayıs'ta Siber Güvenlik ve Altyapı Güvenlik Ajansı (CISA) ve Federal Soruşturma Bürosu (FBI), 2016 ve 2019 yılları arasında en çok yararlanılan 10 güvenlik açığının bir listesini de yayınlamıştı.</span>

<span class="c13"></span>

<span class="c13">"İlk 10 içinde, Çin, İran, Kuzey Kore ve Rusya'dan devlet destekli siber aktörler arasında en sık kullanılan üç güvenlik açığı CVE-2017-11882, CVE-2017-0199 ve CVE-2012-0158," CISA söz konusu. "Bu güvenlik açıklarının üçü de Microsoft'un OLE teknolojisiyle ilgilidir."</span>

<span class="c13"></span>

<span>Çinli bilgisayar korsanları Aralık 2018'den itibaren sık sık</span> <span class="c21">[CVE-2012-0158](https://nvd.nist.gov/vuln/detail/CVE-2012-0158)</span><span class="c13">'den yararlanarak hedeflerinin güvenlik güncellemelerini hemen uygulayamadıklarını ve tehdit aktörlerinin yama yapılmadığı sürece hataları kötüye kullanmaya devam edeceklerini gösterdi.</span>

<span class="c13"></span>

<span class="c13">Saldırganlar ayrıca Office 365 gibi bulut işbirliği hizmetlerinin aceleye getirilmesinden kaynaklanan güvenlik açıklarından yararlanmaya da odaklanıyor.</span>

<span class="c13"></span>

<span>Yamasız Pulse Secure VPN güvenlik açıkları (</span><span class="c21">[CVE-2019-11510](https://nvd.nist.gov/vuln/detail/CVE-2019-11510)</span><span>) ve Citrix VPN (</span><span class="c21">[CVE-2019-19781](https://nvd.nist.gov/vuln/detail/CVE-2019-19781)</span><span class="c13">), devam eden COVID-19 pandemisinin neden olduğu uzaktan çalışmaya geçişin ardından geçen yıl da favori bir hedef oldu.</span>

<span class="c13"></span>

<span class="c13">CISA, eski yama uygulanmamış güvenlik hatalarını azaltmanın en kolay ve en hızlı yolu olarak, ömrünü tamamlamış yazılımlardan mümkün olan en kısa sürede geçiş yapılmasını önerir.</span>

<span class="c13"></span>

<span class="c13">2016'dan bu yana en çok yararlanılan 10 güvenlik açığının tam listesi, NVD girdilerine doğrudan bağlantılarla birlikte aşağıda mevcuttur.</span>

<span class="c13"></span>

<span class="c13"></span>

<span class="c13"></span>

<a id="t.e8bff33dce42df03a467e488fb31ee89a8b9ca11"></a><a id="t.1"></a>

<table class="c28">

<tbody>

<tr class="c9">

<td class="c30" colspan="1" rowspan="1">

<span class="c4">CVE</span>

</td>

<td class="c26" colspan="1" rowspan="1">

<span class="c4">İlişkili Kötü Amaçlı Yazılım</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2017-11882](https://nvd.nist.gov/vuln/detail/CVE-2017-11882)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">Loki, FormBook, Pony/FAREIT</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2017-0199](https://nvd.nist.gov/vuln/detail/CVE-2017-0199)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">FINSPY, LATENTBOT, Dridex</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2017-5638](https://nvd.nist.gov/vuln/detail/CVE-2017-5638)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">JexBoss</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2012-0158](https://nvd.nist.gov/vuln/detail/CVE-2012-0158)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">Dridex</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2019-0604](https://nvd.nist.gov/vuln/detail/CVE-2019-0604)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">China Chopper</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2017-0143](https://nvd.nist.gov/vuln/detail/CVE-2017-0143)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">Multiple using the EternalSynergy and EternalBlue Exploit Kit</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2018-4878](https://nvd.nist.gov/vuln/detail/CVE-2018-4878)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">DOGCALL</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2017-8759](https://nvd.nist.gov/vuln/detail/CVE-2017-8759)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">FINSPY, FinFisher, WingBird</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2015-1641](https://nvd.nist.gov/vuln/detail/CVE-2015-1641)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">Toshliph, Uwarrior</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c18">[CVE-2018-7600](https://nvd.nist.gov/vuln/detail/CVE-2018-7600)</span>

</td>

<td class="c20" colspan="1" rowspan="1">

<span class="c1">Kitty</span>

</td>

</tr>

</tbody>

</table>

<span class="c13"></span>

 **Hakan Yazıcı <br>Uygulama Güvenliği Mühendisi**<br>
 **Endpoint Bilgi Teknolojileri Güvenliği ArGe A.Ş - 2021**<br>
 **LinkedIn: https://www.linkedin.com/in/hakan-yazici/**<br>
