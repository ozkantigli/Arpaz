---
kaynak_dokuman: "Final_Completed_OTC-070-040_Mal_çıkış_süreçleri.pdf"
konu: "OTC-070-040 Mal Çıkış Süreçleri"
bicim: pdf
---

# Final_Completed_OTC-070-040_Mal_çıkış_süreçleri.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-040 Mal çıkış süreçleri

Çalıştay Detayı
Çalıştay kodu

Çalıştay Adı

OTC-070

Sevk ve Teslimat Yönetimi

Süreç Detayı (UPM)
L1 Kodu

L1 Süreç Adı

OTC

Order-to-Cash

L2 Kodu

L2 Süreç Adı

OTC-070

Sevk ve Teslimat Yönetimi

L3 Kodu

L3 Süreç Adı

OTC-070-040

Mal çıkış süreçleri (EWM/Total Depo/Arbarkod Entegrasyonu)

L4 Kodu

L4 Süreç Adı

OTC-070-040-010

MM Depo Mal Çıkış İşlemleri

OTC-070-040-020

EWM Depo Mal Çıkış İşlemleri

Doküman Detayı
Hazırlayan

SAP Çözüm Mimarı

Aslıhan Türkmen

Fuat Güney Günay / Onur Türkeş

SAP Proje Yöneticisi

Arçelik Proje Yöneticisi

Funda Taş

Tasarım Dokümanının Tanımı
1.

Amaç


<<< SAYFA 2 >>>
Bu doküman sevk ve teslimat yönetimi kapsamında ortaya çıkan mal çıkışı sürecinin Arçelik iş süreçlerinin tasarımını, SAP En İyi
Uygulamalar, Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları halinde
içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Mal çıkış işlemleri Arçelik Pazarlama bünyesindeki tüm satış organizasyonları için kullanılan bir süreçtir.

2.2

Ana Veri

Mal çıkışı sürecinde malzeme ve müşteri ana veri yapısı kullanılacaktır

2.3

Varsayımlar

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Sevkiyat ve mal çıkışı ilişkili Best Practice ve süreç akış diagramı aşağıdaki linkte yer almaktadır.
BD9-Sell from Stock Process

4. Arçelik Senaryolara Genel Bakış
Mal çıkış süreci depo içerisindeki fiziksel sürecin son aşamasıdır. Mal çıkışı gerçekleştiği anda sevkiyat işlemi tamamlanmış olur.
Mal çıkışından sonra E-irsaliye süreciyle devam edilir.
Yedek parça için mal çıkışı süreci farklılaşmamaktadır.
Solar tarafında tıra yüklenen adet kadar irsaliye kesilecektir. 3 çeşit solar paketi vardır. 32'li - 704, 29'lu - 754, 27'li - 594 adet ürün
tıra sığabilmektedir.
Ödeme kaydedici cihaz ve pompa yazar kasa irsaliyelerine özel durumlar aşağıdaki gibidir.
ÖKC (Ödeme Kaydedici Cihaz) sürecinde seri numarası ve mali ID (cihaz mali kimlik numarası) numarası eşleştirilir ve irsaliye üzerinde
gösterilir.
Cep telefonları için IMEI numarası e-irsaliye üzerinde bulunacaktır.
Pompa yazar kasa süreci benzin istasyonlarında kullanılan bir yazar kasadır. Pompa yazar kasa irsaliyesi düzenlikten sonra mali ID
bilgileri satış ekibi tarafından belge görüntüleme yapılarak gerekli bilgiler bayilere iletilmektedir.

4.1. OTC-070-040-010 MM Depo Mal Çıkış İşlemleri
MM depo çekme işlemleri Arbarkod ve Total Depo sistemlerinden yürütülecektir ve bu bilgi SAP S/4 HANA sistemine entegrasyonla
alınacaktır.
Çekme işlemlerinden sonra SAP S/4 HANA sisteminde mal çıkışı VL06O ya da VL02N işlem kodlarından yapılacaktır.

4.1.1.

Sürece Genel Bakış

Arbarkod sistemi; Arçelik depolarında SAP S/4 HANA sisteminde oluşturulan satış ve STO teslimat numaralarına istinaden seri no / mali
id / IMEI no belirlenir ve çekme miktarlarının güncellendiği bir sistemdir. Ürün üzerindeki barkod el terminali aracılığı ile okutularak SAP
S/4 HANA sistemine entegre olarak çekme miktarı ve seri no / mali id / IMEI no bilgileri gönderilir.
Ayrıca Arbarkod ve Total depo sistemlerinde seri numarası / IMEI bilgisi bulunmaktadır. İade işlemlerinde iade teslimat vb. belgeye
istinaden okutmalarda seri numaralar Arbarkod sisteminde tutulmaktadır.
Bayi yönetmeni tarafından cep telefonu ve notebookta iade işlemleri gerçekleştirilirken Arbarkod ve Total depo sistemlerinde tutulan
seri numarası / IMEI ile sistemde otomatik olarak referans faturanın bulunması sağlanacaktır. Böylece hangi faturadan referansla iade
olduğu bilgisi olduğu için fiyat belli olmaktadır. İade kokpitinden cep telefonu ve notebook için iade işlemleri yapılırken seri numarası /
IMEI bilgisi girilerek referans fatura bulunur ve faturaya istinaden iade siparişi oluşturulur.


<<< SAYFA 3 >>>
D2D su arıtma mal çıkış işlemleri ZSD_0014 D2D kokpitinden yapılacaktır.
H2O su arıtma için S4HANA üzerinde herhangi bir işlem yapılmayacaktır. Tevfik Ünlüer

4.1.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070040-01 Mal Çıkış İşlemleri
SD070040-01 Mal Çıkış İşlemleri Süreç Akışı Ekran Görüntüsü :

4.1.3.

Süreç Adımları

Mal çıkış süreç adımları aşağıdaki gibidir :
1. SAP S/4 HANA sisteminde oluşturulan teslimatın seri no okutulması ve çekme işlemleri Arbarkod ve Total depo sistemlerinde
yapılır.
2. Çekme bilgisi ve seri no SAP S/4 HANA sistemine entegrasyonla alınır ve teslimata yazılır. (Çekme sürecine ilişkin detaylar
dokümanında Final_Completed_OTC-070-030 Çekme İşlemleri yer almaktadır.)
3. VL02N/VL06O işlem kodlarından mal çıkışı yapılır.
4. E-irsaliye işlemleri gerçekleşir.
5. E-irsaliye oluştuktan sonra bayilere mail gönderilir.
6. Bir araca ilişkin bütün teslimatların mal çıkışının yapılmasından sonra fiili miktarlar Ortec-Lotus sistemine gönderilecektir.
(Realizasyon entegrasyonuna ilişkin detaylar Final_Completed_OTC-070-020 Nakliye planlama dokümanında yer almaktadır.)

4.2. OTC-070-040-020 EWM Depo Mal Çıkış İşlemleri
EWM depo mal çıkış işlemleri EWM sistemlerinden yürütülecektir.

4.2.1.

Sürece Genel Bakış

EWM sisteminde mal çıkışı yapılacaktır. Sürece ilişkin detaylar Final_OTC-070-040 Mal çıkış süreçleri-EWM dokümanında yer almaktadır

4.2.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070040-01 Mal Çıkış İşlemleri
SD070040-01 Mal Çıkış İşlemleri Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 4 >>>
4.2.3.

Süreç Adımları

Mal çıkış süreç adımları aşağıdaki gibidir :
1. SAP S/4 HANA sisteminde oluşturulan teslimatın mal çıkışı EWM sisteminde yapılır.
2. Mal çıkışı bilgisi SAP S/4 HANA sistemine gönderilir.
3. E-irsaliye işlemleri gerçekleşir.

5.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

6.

İlişkili Olan Diğer Süreç Dokümanları

No

UPM Süreç Adı

Referans Doküman Linki

Açıklama

1

Sevkiyat Planlama

Final_Completed_OTC-070-010 Sevkiyat planlama

Teslimat belgesinin oluşturulması detaylandırılmıştır.

2

Mal çıkış süreci - EWM

Final_OTC-070-040 Mal çıkış süreçleri-EWM

EWM'deki mal çıkış süreçleri detaylandırılmıştır.

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF
Tipi

WRICEF Sorumlusu
(Arçelik/SAP)

CR

SATH2140

EWM Delivery Update - N/A

Geliştir
me

Aslıhan Türkmen

X

SATH2131

ÖKC (Ödeme Kaydedici Cihaz) Fatura ve Pompa Yazar Kasa Fatura Süreçlerinde seri numarası ve
Mali ID numarasının eşleşmesi - N/A

Geliştir
me

Aslıhan Türkmen

X

SATH2129

Siparişin sevkiyatı yapıldıktan sonra ilgili müşteri kullanıcılarına mail gönderilmesi - N/A

Geliştir
me

Aslıhan Türkmen

X
