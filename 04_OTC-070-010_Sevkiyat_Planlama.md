---
kaynak_dokuman: "Final_Completed_OTC-070-010_Sevkiyat_planlama.pdf"
konu: "OTC-070-010 Sevkiyat Planlama (teslimat yaratma, sevkiyat kokpiti ZSD_0023)"
bicim: pdf
---

# Final_Completed_OTC-070-010_Sevkiyat_planlama.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-010 Sevkiyat planlama

Çalıştay Detayı
Çalıştay kodu

Çalıştay Adı

OTC-070-010

Sevkiyat planlama

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

OTC-070-010

Sevkiyat planlama (teslimat yaratma seçenekleri ve sevkiyat kokpiti)

L4 Kodu

L4 Süreç Adı

OTC-070-010-010

Teslimat Belgesinin Manuel Yaratılması

OTC-070-010-020

Teslimat Belgesinin Otomatik Yaratılması

OTC-070-010-030

Teslimat Belgesinin Sevkiyat Kokpitinden Yaratılması

OTC-070-010-040

Teslimat Belgesinin Door to Door Kokpitinden (ZSD2D) Yaratılması

OTC-070-010-050

Müşteri Hizmetleri Yedek Parça Teslimat Belgesinin Yaratılması

OTC-070-010-060

Müşteri Hizmetleri Ürün Değişimi Teslimat Belgesinin Yaratılması

Doküman Detayı
Hazırlayan

SAP Çözüm Mimarı

Aslıhan Türkmen

Fuat Güney Günay / Onur Türkeş

SAP Proje Yöneticisi

Arçelik Proje Yöneticisi

Funda Taş


<<< SAYFA 2 >>>
Tasarım Dokümanının Tanımı
1.

Amaç

Bu doküman sevkiyat ve teslimat yönetimi süreçleri kapsamında ortaya çıkan Arçelik iş süreçlerinin tasarımını, SAP En İyi Uygulamalar,
Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları halinde içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Sevkiyat ve teslimat yönetimi Arçelik Pazarlama bünyesindeki tüm satış organizasyonları için kullanılan bir süreçtir.

2.2

Ana Veri

Sevkiyat planlama sürecinde malzeme ve müşteri ana veri yapısı kullanılacaktır.

2.3

Varsayımlar

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Teslimat ve sevkiyat ilişkili Best Practice ve süreç akış diagramı aşağıdaki linkte yer almaktadır.
BD9-Sell from Stock Process

4. Arçelik Senaryolara Genel Bakış
Teslimat belgesi manuel, otomatik ya da sevkiyat kokpitinden yaratılacaktır. Teslimat belgesi yaratma seçenekleri kanal bazlı
farklılaşabilir.
Teslimat belgeleri oluşturulduktan sonra nakliye planlamasının yapılması için teslimatlar SAP S/4 HANA sisteminden Ortec-Lotus
sistemine entegrasyonla gönderilecektir.
Bu sürece ilişkin detaylar Final_Completed_OTC-070-020 Nakliye planlama dokümanında yer almaktadır.

Teslimat belgelerinin süreç bazlı oluşma şekilleri aşağıda yer almaktadır.
Süreç Adı

Otomatik

Müşteri hizmetleri personele yedek parça satışı

Manuel

Fonksiyon

X

Mağazadan siparişi müşterinin direkt teslim aldığı montajsız ürünler

X

Dropshipment süreci

X

Bayi, Altus, Grundig, Kurumsal kanal ve HVAC & Energy
(İklimlendirme ve Solar) sevkiyat süreçleri

X

İşlem
kodu
VL01N

ZSD_FM_SALESDOC
UMENT_CREATE

X

ZSD_00
23

WEB, Marketplace ve Personel

X

ZSD_00
23

Migros, ŞOK, BİM, A101,Vatan

X

ZSD_00
23

Mağaza Flextra süreci

X

Door to Door

X

Müşteri hizmetleri kanalından yapılan WEB yedek parça satışı

X

Job

ZASD:
SEVKIYATI_601
/ABCP

ZSD_00
14
ZASD:601S WEB
YP DELIVERY


<<< SAYFA 3 >>>
Müşteri hizmetleri Servis yedek parça satışı

X

Müşteri hizmetleri ürün değişimi

X

ZSD_00
33

ZASD:601S YP
ATP + DELIVERY

VL10C

ZBSD:6018 YP
ATP + DELIVERY

VL10C

SAP S/4 HANA sisteminde oluşturulan teslimat belgesinin Ortec-Lotus sistemine gönderilmediği durumlar bulunmaktadır. Bunun
kontrolünün yapılabilmesi için teslimat belgesi üzerinde nakliye planı yapılmayacak belgeler için (Ortec-Lotus sistemine gönderilmemesi
için) teslimat blokajı girilecektir. Eğer bloke edilen teslimat daha önce Lotus sistemine gönderildiyse SAP S/4 HANA sisteminden job ile
entegrasyon tetiklenecektir ve teslimatın araç planı yapılmadıysa Lotus sisteminden silinecektir.
SAP standartında teslimat blokajı başlık bazında eklenmektir, kalem bazında da blokaj eklenmesi CR maddesi altında takip edilmektedir.
SATH-6942 - Teslimatlardaki ürünler bazında toplu blokaj konulması

DEFERRED

Bloke nedenleri aşağıdaki gibidir;
Satıcı durdurdu
Bayi depo problemli
Blokeli ürün
Stok eksi
Hasarlı ürün vb.

Teslimat belgesinin Ortec-Lotus sistemine gönderilmediği durumlar aşağıda listelenmiştir :
Mağazadan yapılan satışlarda müşterinin direkt teslim aldığı montajsız ürünler için depo yeri olarak mağaza belirlenir, bu depo
yeri Ortec-Lotus ilişkisiz olur. Bu ürünler için teslimat belgesi otomatik oluşur.
Kargo teslimatları Ortec-Lotus sistemine gönderilmeyecektir. Satış siparişinde biliniyorsa kargo firması muhatap listesinde
bulunacaktır. Kargo teslimatları kullanılan süreçler aşağıdaki gibidir;
Bilişim depo sevkiyatları sadece kargo ile yapılmaktadır.
Web depolardan sevkiyatlar kargo ile yapılmaktadır. Web tarafında kargo firması entegrasyonu Hybris+Mulesoft tarafından
yapılmaktadır.
Door to Door satışlarda kargo teslimatı otomatik değildir, gerekirse münferiden yapılmaktadır. D2D sevkiyat süreçleri mail ile
manuel olarak takip edilmektedir. D2D sevkiyatları servislere Arçelik araçları veya kargo olmak üzere iki şekilde yapılmaktadır.
Bunlar dışında kalan bayi satışlarında belgelerde münferit olarak sevkiyat departmanı tarafından yapılmaktadır. Örneğin Vatan,
MC
6002- ANK Ankara depo Ortec ilişkisiz olacaktır. Teslimat oluşturulduktan sonra EWM üzerinden süreç devam edecektir.
Ortec-Lotus ilişkisi SAP S/4 HANA sisteminde tasarlanan bir bakım tablosundaki parametrelere göre belirlenmektedir. ZSD_T0007
(ZSD_T_DLV_CONFIG) işlem kodundan Ortec-Lotus sürecine dahil olacak teslimatlar için bakım yapılır.

4.1.

OTC-070-010-010 Teslimat Belgesinin Manuel Yaratılması

Teslimat belgesinin yetkili kullanıcı tarafından manuel olarak SAP S/4 HANA sisteminden yaratıldığı süreçtir.

4.1.1.

Sürece Genel Bakış

Müşteri hizmetleri personele yedek parça satışı yapılırken referansız teslimat manuel olarak yaratılır.
Perakende kanalı; personel satış sevkiyat sürecinin montajlı ve montajsız süreçleri aşağıdaki gibidir :
Montajlı ürün sevkiyatı: Ürünler sevk araçlarıyla önce servislere gönderilir ve servisler aracılığıyla personelin adresine ürünler
ulaştırılır.
Montajsız ürün sevkiyatı: Personelin iş yerine teslim edilmektedir.

Manuel teslimat yaratılan süreçler için standart ekranlar kullanılmaktadır. (VL01N/ VL10A / VL10B /VL10C)
AATP modülünün dahil olmadığı özellikle müşteri hizmetleri süreçlerinde teslimat belgesi manuel oluşturulur.

4.1.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri


<<< SAYFA 4 >>>
SD070010-03 Sevkiyat planlama Elle Münferit
SD070010-03 Sevkiyat planlama Elle Münferit Süreç Akışı Ekran Görüntüsü :Dr

4.1.3.

Süreç Adımları

Teslimat yaratma akışın adımları aşağıdaki gibidir:
1. SAP S/4 HANA sisteminde teslimat belgesi manuel olarak yaratılır.
2. Oluşan teslimat belgeleri SAP S/4 HANA sisteminden Ortec-Lotus sistemine nakliye planlaması için entegrasyonla
gönderilecektir.
3. Kargo teslimatları Ortec-Lotus sistemine gönderilmeyecektir.

4.2.

OTC-070-010-020 Teslimat Belgesinin Otomatik Yaratılması

Teslimat belgesinin otomatik olarak SAP S/4 HANA sisteminden yaratıldığı süreçtir.

4.2.1.

Sürece Genel Bakış

Aşağıdaki süreçler için teslimat belgeleri otomatik oluşur.
Mağazadan yapılan müşterinin direkt teslim aldığı montajsız ürünler için teslimat otomatik oluşur.
Dropshipment sürecinde teslimat otomatik oluşur. Süreci ilişkin detaylar Final_OTC-060-010 Satış Siparişi Alım Süreçleri
(Dropshipment Satış Süreci) dokümanında açıklanmaktadır.
ZSD_0023- Sevkiyat kokpitine kurulan job ile açık ve teyitli siparişler için teslimat belgeleri otomatik oluşmaktadır.

4.2.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070010-01 Sevkiyat planlama Toplu Otomatik
SD070010-01 Sevkiyat planlama Toplu Otomatik Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 5 >>>
4.2.3.

Süreç Adımları

Otomatik teslimat oluşturma süreç akışı aşağıdaki gibidir:
1. Mağaza siparişlerinde müşterinin direkt teslim aldığı ürünler için teslimat oluşması, mal çıkışı ve faturalama otomatiktir.
2. ZSD_0023 ekranından teslimatlar job ile otomatik oluşur. Varyant: ZASD:SEVKIYATI_601/ABCP

4.3. OTC-070-010-030 Teslimat Belgesinin Sevkiyat Kokpitinden Yaratılması
SAP S/4 HANA sistemi üzerinde geliştirilecek sevkiyat kokpiti üzerinden açık siparişler teyit alınan miktarlarıyla görüntülenebilecektir.
Sevkiyat kokpitinden müşteri siparişleri (SD) ve transit siparişlerin- stok nakil siparişleri (MM) teslimatları oluşturulacaktır.
Teslimat belgeleri sevkiyat kokpiti üzerinden oluşturulacaktır.

4.3.1.

Sürece Genel Bakış

Altus, Grundig, Kurumsal kanal ve HVAC & Energy (İklimlendirme ve Solar) sevkiyat süreçleri sevkiyat kokpiti üzerinden yürütülecektir.
PGS ve Mutfak süreçleri için de sevkiyat kokpiti kullanılacaktır.
Teyit alan, teslimat blokajı olmayan, kredi blokajı onaylanan teslimata dönüşmeyen açık siparişler sevkiyat kokpitinde listelenir.
Teyit almayan siparişler sevkiyat kokpitinde görünmemektedir.
Sevkiyat noktası bazında yetki objesi bulunmaktadır. Her depo kullanıcısı kendi deposuna düşen açık siparişleri teslimata çevirmektedir.

Sevkiyat kokpitinden teslimatlar 2 şekilde oluşturulur:
1- Teslimatlar, ZASD:SEVKIYATI_601/ABCP varyantına kurulan job ile 30 dakikalık sıklıklarla oluşur.
2- Müşteri ana verisinde veya sipariş üzerinde "birleştirme" intikatörü olduğunda malı teslim alan ve sevkiyat noktası aynı olan
siparişler birleşerek tek bir teslimat oluşur.
ZASD:SEVKIYATI_601/ABCP varyantına ilişkin detaylar aşağıda yer almaktadır.
Bayi siparişleri, (SD'den oluşan siparişler) çalışma şekli standart ve satış organizasyonu 601A/ 601B/ 601C /601P, üretim yeri
601U olan açık siparişler için teslimatlar otomatik oluşur.
Seçim ekranında bulunan "AATP üst kalemle aynı depo yeri" seçeneği ile siparişteki kalemin depo yeri ve AATP'nin türettiği
kalemdeki ikame depo yeri aynı olan siparişler otomatik oluşur.
WEB, Marketplace ve Personel dağıtım kanallarında teslimatlar manuel oluşturulacağı için varyanttan hariç tutulmuştur.
Mağaza Flextra sürecinde teslimatlar manuel oluşturulur, BDZF/ICTF/ES3F/ANSF/ÇAYF sevkiyat noktaları varyanttan hariç
tutulmuştur.
Migros, ŞOK, BİM, A101,Vatan muhatapları için manuel teslimat oluşması talep edilmiştir. Bu müşteriler varyanttan hariç
tutulmuştur.

2- Teslimatlar manuel oluşur.


<<< SAYFA 6 >>>
ZSD_0023 ekranı çalıştırılır, sipariş seçilir ve teslimat yaratılır.
Bilişim depo teslimatları manuel oluşur. Bu teslimatlar kargoyla sevk edileceği için belirli tutar altındaki siparişler birleştirilerek
teslimat oluşturulur.
ZSD_0023 filtre ekranında aşağıdaki görselde işaretli olan radio butonlar bilişim depo-ICT için kullanılmaktadır.

ZSD_0023 sevkiyat kokpiti ALV aşağıdaki gibidir.
Satış organizasyon verileri, malzeme ve müşteri ana verisindeki alanlar ve siparişe ilişkin detaylar ALV'de bulunmaktadır. Kullanıcı
ihtiyaç duyduğu alanlar için varyant kaydedebilmektedir.
Alan detayları aşağıda bulunmaktadır:
Sipariş miktarı: Siparişte girilen adet
Teslim edilmiş miktar: Daha önce teslimata dönüşen adet
Teyit alan miktar: Stokta olan ve teyit almış adet
Teslim edilebilir miktar: Teslimat oluşturulacak adet
Emanet: Sipariş kalemi üzerindeki emanet bilgisi
Müşteri/Malzeme emanet göstergesi: Ana veride bulunan emanet/fiktife alınabilir bilgisi. Özellikle ay sonu fiktif işlemlerinde
deponun fiktife alabileceği teslimatlar için bu filtreye ihiiyaç duyulmaktadır.
Tüketici teslim: Siparişteki "Z3-yetkili servis" bilgisi
Açıklama: Hata mesajlarının eklendiği alan

4.3.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070010-02 Sevkiyat planlama Sevkiyat Kokpiti Üzerinden
SD070010-02 Sevkiyat planlama Sevkiyat Kokpiti Üzerinden Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 7 >>>
4.3.3.

Süreç Adımları

Sevkiyat kokpitinden yürütülen işlemlerin süreç adımları aşağıdaki gibidir:
1. Sevkiyat kokpitinde teyitli açık siparişler listelenir.
2. Teslimat belgeleri otomatik (job) veya manuel olarak oluşturulur.

4.4. OTC-070-010-040 Teslimat Belgesinin Door to Door Kokpitinden (ZSD_0014) Yaratılması
Perakende kanala bağlı su arıtma Door to Door süreci için SAP ECC sisteminde kokpit tasarlanmıştır.
ZSD2D işlem koduna bağlı D2D kokpiti üzerinden teslimat belgesi yaratılmaktadır. Bu yapı SAP S/4 HANA sisteminde de ZSD_0014
ekranı olarak geliştirilmiştir.

4.4.1.

Sürece Genel Bakış

Door to Door kanalında mevcut durumda SAP ECC sisteminde geliştirilen ZSD2D kokpitinde teslimat belgeleri oluşturulmaktadır.
SAP S/4 HANA sisteminde de bu yapı aynı çalışacak şekilde korunacaktır.
Su arıtma D2D platformunda sözleşme oluşturulduktan sonra, Sales Force üzerinde fırsat oluşturuluyor. S4HANA üzerinde sipariş
oluşur. Sevkiyat için ZSD_0014 ekranından teslimat belgesi oluşturulur.
Mal hareketi esnasında yapılan okutmadaki seri numarası ile S4HANA sisteminde ekipman otomatik oluşacaktır.
D2D teslimatları Ortec-Lotus ilişkisiz olacaktır. Genellikle kargoyla ürünler gönderilir.

4.4.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070010-04 Door to Door Sevkiyat Planlama
SD070010-04 Door to Door Sevkiyat Planlama Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 8 >>>
4.4.3.

Süreç Adımları

Door to Door kokpitinden teslimat yaratma süreç adımları aşağıdaki gibidir :
1. SAP S/4 HANA sisteminde ZSD_0014 - D2D kokpiti üzerinde teslimat belgeleri yaratılacaktır.

4.5.

OTC-070-010-050 Müşteri Hizmetleri Yedek Parça Teslimat Belgesinin Yaratılması

Müşteri hizmetleri süreçleri mevcuttaki SAP ECC sisteminde benzer çalışacak şekilde SAP S/4 HANA sisteminde geliştirilecektir.
Otomatik teslimat yaratma programları mevcuttaki yapı korunacak şekilde SAP S/4 HANA sisteminde geliştirilecektir.

4.5.1.

Sürece Genel Bakış

Müşteri hizmetleri kanalından yapılan yedek parça satışlarının teslimatları iki şekilde olmaktadır:
Web Yedek Parça: Web yedek parça sürecinde sepet içindeki kalem/miktar adedi kadar SAP S/4 HANA sisteminde sipariş
yaratılır. Bu siparişlerin teslimat belgeleri yaratılırken adrese göre birleştirme yapılır.
Web yedek parça siparişleri 1006 Ewm'li depo yerinden karşılanır. Teslimat belgesini yaratan ZASD:601S WEB YP DELIVERY jobı ile
teslimat belgeleri oluşturulur.

Servis yedek parça : Yedek parça teslimatlarında teslimat birleştirme göstergesi işaretli olarak yaratılacak.
Yedek parça teslimatları kargo teslimatı olduğu durumda EWM'siz depolarda gönderi numarası teslimatlarda bulunmayacaktır.
Servislerden yedek parça siparişleri, sipariş türüne göre önceliklendirilerek teslimat belgesi yaratılır.
Teslimat önceliği alanı mevcuttaki gibi doldurulacak. Bu alan teslimat yaratan program ile doldurulacaktır.
ZSD_P_SATISSTOKNAKLIBELGETERMN (ZSD_0033) sipariş yeniden terminleme programı çalışır siparişlerin önceliklerine göre yeniden
terminleme yapılır.
Sipariş türlerinin teslimat öncelikleri aşağıdaki gibidir:
1.
2.
3.
4.
5.

HF siparişler (bozuk ürün için oluşturulan ve hizmet fişi ile gelen sipariş)
İhracat Urgent order
Servis siparişleri
İhracat
Bölgelere gönderilen nakil siparişleri

4.5.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070010-05 Sevkiyat planlama Müşteri Hizmetleri Yedek Parça
SD070010-05 Sevkiyat planlama Müşteri Hizmetleri Yedek Parça Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 9 >>>
4.5.3.

Süreç Adımları

Müşteri hizmetleri yedek parça sevkiyat süreç akışı aşağıdaki gibidir:
Servis yedek parça;
1. Servis tarafından yapılan yedek parça açık siparişlerinin önceliklendiren ZSD_P_SATISSTOKNAKLIBELGETERMN programı çalışır.
2. Teslimat belgeleri VL10C arkasında çalışan ZASD:601S YP ATP + DELIVERY/ ZBSD:6018 YP ATP + DELIVERY jobları ile
otomatik oluşur.
3. Nakliye planlama süreci başlar
Web kanalı yedek parça,
1. Web üzerinden yapılan yedek parça satışlarında teslimat belgesi VL10C arkasına kurulan ZASD:601S WEB YP DELIVERY jobı ile
otomatik olarak oluşur.

4.6. OTC-070-010-060 Müşteri Hizmetleri Ürün Değişimi Teslimat Belgesinin Yaratılması
Müşteri hizmetleri süreçleri mevcuttaki SAP ECC sisteminde benzer çalışacak şekilde SAP S/4 HANA sisteminde geliştirilecektir.

4.6.1.

Sürece Genel Bakış

Teslimat belgeleri manuel olarak SAP standart ekranlarından (VL10C) yaratılmaktadır.

4.6.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070010-06 Sevkiyat planlama Müşteri Hizmetleri Ürün Değişimi
SD070010-06 Sevkiyat planlama Müşteri Hizmetleri Ürün Değişimi Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 10 >>>
4.6.3.

Süreç Adımları

Müşteri hizmetleri ürün değişimi sevkiyat süreç akışı aşağıdaki gibidir:
1. Arızalı ürünün alındı kontrolü yapılır.
2. Yeni ürün için teslimat belgesi manuel yaratılır.
3. Nakliye ilişkisi belirlenir.
4. Nakliye planlama süreci başlar.

5.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

6.

İlişkili Olan Diğer Süreç Dokümanları

No UPM Süreç Adı

Referans Doküman Linki

Açıklama

1

Nakliye planlama (Ortec-Lotus sistemi
entegrasyonu)

Final_Completed_OTC-070-020
Nakliye planlama

Sevkiyatın nakliyesinin planlandığı Ortec-Lotus sisteminin
detayları bulunmaktadır.

2

Çekme İşlemleri (EWM/Total Depo
/Arbarkod Entegrasyonu)

Final_Completed_OTC-070-030
Çekme İşlemleri

Sevkiyatın sonraki adımı olan çekme süreci
detaylandırılmıştır.

3

Mal çıkış süreçleri (EWM/Total Depo
/Arbarkod Entegrasyonu)

Final_Completed_OTC-070-040 Mal
çıkış süreçleri

Sevkiyat planlamanın son aşaması olan mal çıkış süreçleri
detaylandırılmıştır.

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF Tipi

WRICEF Sorumlusu (Arçelik/SAP)

CR

SATH-1221

Sevkiyat kokpiti

Geliştirme

Aslıhan Türkmen

X

SATH-2133

Yedek parça sevkiyat planı için özel sevkiyat yaratma geliştirmesi - N/A

Geliştirme

Aslıhan Türkmen

X

SATH-2128

Door to door süreç kokpitinin tasarlanması (T-Code: ZSD2D) - N/A

Geliştirme

Aslıhan Türkmen

X

SATH-2109

Genel Teslimat Görüntüleme Servisi

Entegrasyon

Aslıhan Türkmen

SATH-2108

Genel Teslimat Listeleme Servisi

Entegrasyon

Aslıhan Türkmen

SATH-2107

Genel Teslimat Değişiklik Servisi

Entegrasyon

Aslıhan Türkmen

SATH-2106

Genel Teslimat Yaratma Servisi

Entegrasyon

Aslıhan Türkmen

SATH-1996

Sevkiyat İşlemleri Raporlama - SD096

Geliştirme, Rapor

Aslıhan Türkmen


<<< SAYFA 11 >>>
SATH-1989

Kamyon Etiket Dökümü WRICEF No: N/A

Geliştirme

Aslıhan Türkmen

X
