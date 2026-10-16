---
kaynak_dokuman: "Final_OTC-060-010_Satış_Siparişi_Alım_Süreçleri.pdf"
konu: "OTC-060-010 Satış Siparişi Alım Süreçleri (kanal bazlı sipariş alma, ZSD_0031 onay vb.)"
bicim: pdf
---

# Final_OTC-060-010_Satış_Siparişi_Alım_Süreçleri.pdf


<<< SAYFA 1 >>>
Final_OTC-060-010 Satış Siparişi Alım Süreçleri

Teknik ve Süreç Dokümanı
Süreç kodu

Süreç Adı

OTC-060-010

Satış Siparişi Alım Süreçleri

Arçelik IT Sorumlusu

SAP Danışmanı

Mehmet Ercan, Ayşegül Doğar Gürbüz, Yağmur Kucur

Onur Türkeş, Meltem Komur, Aslıhan Türkmen, Gökmen Altınel

Süreç Detayı (UPM)
L1 Kodu

L1 Süreç Adı

OTC

Order To Cash

L2 Kodu

L2 Süreç Adı

OTC-060

Entegre Sipariş Yönetimi

L3 Kodu

L3 Süreç Adı

OTC-060-010

Satış Siparişi Alım Süreçleri

L4 Kodu

L4 Süreç Adı

OTC-060-010010

Yetkili Satıcı Kanalı Bayi Standart Sipariş
Yetkili Satıcı Kanalı Ay Başı Öneri Sipariş

OTC-060-010020
OTC-060-010030

Yetkili Satıcı Kanalı Skala Süreci
Yetkili Satıcı Kanalı Ön Ödemeli Sipariş
Yetkili Satıcı Kanalı Hakediş Sipariş


<<< SAYFA 2 >>>
OTC-060-010040

Altus Sipariş Süreçleri
Grundig Sipariş Süreçleri

OTC-060-010050
OTC-060-010060

VSRM Sipariş Süreçleri
İklimlendirme Sipariş Süreçleri
Solar Sipariş Süreçleri

OTC-060-010070
OTC-060-010080
OTC-060-010090
OTC-060-010100
OTC-060-010110
OTC-060-010120
OTC-060-010130
OTC-060-010140
OTC-060-010150
OTC-060-010160
OTC-060-010170
OTC-060-010180
OTC-060-010190

Bayiye yapılan Kurumsal Satışlar
Direkt kurumsal kanala yapılan satışlar
BİM Market Satış Süreçleri - Discount
ŞOK Market Satış Süreçleri - Discount
A101 Market Satış Süreçleri - Discount
H2O Satış Süreçleri
D2D Satış Süreçleri
OLIZ Satış Süreci
Marketplace Satış Süreci
Web Satış Süreci
Arçelik Mağaza Satış Süreci
Web Tamamlayıcı ürün- Aksesuar Satış Süreci
Yetkili Servis Yedek Parça Satış Süreci
Personel Yedek Parça Satış Süreci
Müşteri Hizmetleri İhracat Amaçlı Yedek Parça Satış
Servis işçilik Satış Süreci
Bayi Ek Garanti Satış Süreci
Yetkili Servis / Çağrı Merkezi Ek Garanti Satış Süreci
Dropshipment Satış Süreci
Arçelik Pazarlama Personeline Satış Süreci

OTC-060-010200
OTC-060-010210

VIP Satış Süreci
Hurda Satış Süreci
ÖKC Devir Satış Süreci

OTC-060-010220
OTC-060-010230

Bakım Satış Süreci
Yetkili Servis Konsinye Süreci
Tüketici Teslim Sipariş Süreci DOKÜMANIN ALT BAŞLIKLARINDA YOK

OTC-060-010240
OTC-060-010250
OTC-060-010260
OTC-060-010270

Flextra Sipariş Süreci DOKÜMANIN ALT BAŞLIKLARINDA YOK. Arçelik Mağaza Satış Süreci başlığı altında
bahsedilmiştir.
Mağaza Yapı Kredi ÖKC Sipariş Süreci DOKÜMANIN ALT BAŞLIKLARINDA YOK. Arçelik Mağaza Satış Süreci başlığı
altında bahsedilmiştir.
Arçelik TR Beko Global YP Sipariş Süreci DOKÜMANIN ALT BAŞLIKLARINDA YOK
Ek Garanti Web Sipariş Süreci
Ürün Değişim Sipariş Süreci Şevket Taşpınar DOKÜMANIN ALT BAŞLIKLARINDA YOK

OTC-060-010280

Koç Grubu Satış Süreci


<<< SAYFA 3 >>>
OTC-060-010290
OTC-060-010300
OTC-060-010310
OTC-060-010320
OTC-060-010330
OTC-060-010340
OTC-060-010350
OTC-060-010360
OTC-060-010370
OTC-060-010380
OTC-060-010390
OTC-060-010400
OTC-060-010410
OTC-060-010420

Doküman Detayı
Hazırlayan

SAP Çözüm Mimarı

Meltem KOMUR
Onur Türkeş
SAP Proje Yöneticisi

Arçelik Proje Yöneticisi

Tasarım Dokümanının Tanımı
1.

Amaç

Bu doküman Satış siparişi alım süreçleri kapsamında ortaya çıkan Arçelik iş süreçlerinin tasarımını, SAP En İyi Uygulamalar, Model
Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları halinde içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı


<<< SAYFA 4 >>>
Tüm satış ve dağıtım alanlarında sipariş alım süreçleri kullanılacaktır. Aşağıdaki satış ve dağıtım alanlarıında hangi belge türleri
kullanıldığı listelenmektedir.
Satış Organizasyonu

Dağıtım Kanalı

Bölüm

Belge Türü

Belge Türü Tanımı

601A

BY

01

ZS01

Standart Satış Sip.

601A

BY

01

ZS02

Emanet/Fiktif Sevk

601A

BY

01

ZS03

Aybaşı Öneri Sipariş

601A

BY

01

ZS04

Bayi yeni açılış skl

601A

BY

01

ZS13

Bayi Hakediş Sipariş

601A

BY

01

ZS15

Emnt İade 601E Çıkış

601A

BY

01

ZS16

Skala Siparişleri

601A

BY

01

ZS19

Fiktif->Emanet Dönüş

601A

BY

01

ZSPG

Yİ Garanti Sat.Sip

601A

KS

01

ZS02

Emanet/Fiktif Sevk

601A

KS

01

ZS05

Alternatif Knl Satış

601A

KS

01

ZS15

Emnt İade 601E Çıkış

601A

KS

01

ZS19

Fiktif->Emanet Dönüş

601B

BY

01

ZS01

Standart Satış Sip.

601B

BY

01

ZS02

Emanet/Fiktif Sevk

601B

BY

01

ZS03

Aybaşı Öneri Sipariş

601B

BY

01

ZS04

Bayi yeni açılış skl

601B

BY

01

ZS13

Bayi Hakediş Sipariş

601B

BY

01

ZS15

Emnt İade 601E Çıkış

601B

BY

01

ZS16

Skala Siparişleri

601B

BY

01

ZS19

Fiktif->Emanet Dönüş

601B

BY

01

ZSPG

Yİ Garanti Sat.Sip

601B

KS

01

ZS02

Emanet/Fiktif Sevk

601B

KS

01

ZS05

Alternatif Knl Satış

601B

KS

01

ZS15

Emnt İade 601E Çıkış

601B

KS

01

ZS19

Fiktif->Emanet Dönüş

601C

AS

01

ZS02

Emanet/Fiktif Sevk

601C

AS

01

ZS05

Alternatif Knl Satış

601C

AS

01

ZS15

Emnt İade 601E Çıkış

601C

AS

01

ZS19

Fiktif->Emanet Dönüş

601C

ES

01

ZS02

Emanet/Fiktif Sevk

601C

ES

01

ZS05

Alternatif Knl Satış

601C

ES

01

ZS15

Emnt İade 601E Çıkış

601C

ES

01

ZS19

Fiktif->Emanet Dönüş

601C

GR

01

ZS02

Emanet/Fiktif Sevk

601C

GR

01

ZS05

Alternatif Knl Satış

601C

GR

01

ZS15

Emnt İade 601E Çıkış

601C

GR

01

ZS19

Fiktif->Emanet Dönüş

601C

HV

01

ZS02

Emanet/Fiktif Sevk

601C

HV

01

ZS05

Alternatif Knl Satış

601C

HV

01

ZS15

Emnt İade 601E Çıkış

601C

HV

01

ZS19

Fiktif->Emanet Dönüş


<<< SAYFA 5 >>>
601C

KS

01

ZS02

Emanet/Fiktif Sevk

601C

KS

01

ZS05

Alternatif Knl Satış

601C

KS

01

ZS15

Emnt İade 601E Çıkış

601C

KS

01

ZS19

Fiktif->Emanet Dönüş

601N

SN

01

ZS06

Masrafyerine Zimmet

601P

MG

01

ZS01

Standart Satış Sip.

601P

MG

01

ZS02

Emanet/Fiktif Sevk

601P

MG

01

ZS08

Mağaza Satış Sip.

601P

MG

01

ZS15

Emnt İade 601E Çıkış

601P

MG

01

ZS19

Fiktif->Emanet Dönüş

601P

MP

01

ZS07

İnternet Satış Sip.

601P

PS

01

ZS12

Personel Satış Sip.

601P

VP

01

ZS11

VIP Satışlar

601P

WK

01

ZS07

İnternet Satış Sip.

601S

CM

01

ZSPG

Yİ Garanti Sat.Sip

601S

VP

01

ZS10

Montaj Yedek P. Satş

601S

VP

01

ZS11

VIP Satışlar

601S

VP

01

ZS18

Hurda Satış Siparişi

601S

YS

01

ZSDS

MH Bakım

601S

YS

01

ZSPG

Yİ Garanti Sat.Sip

601S

YS

01

ZSPR

Yİ YP Personel Sip.

2.2

Ana Veri

Satış siparişi alım sürecinde müşteri ana verileri, malzeme ana verileri ve fiyatlandırma ana verileri kullanılacaktır.
Mediamarkt, Teknosa ve Koçtaş için entegrasyonda kullanılmak üzere müşteri-malzeme bilgi kaydı kullanılacaktır.
Adresler il, ilçe, mahalle bazında Saris sisteminden SAP sistemine alınacaktır.
Yeni açılan müşteri kartları için henüz teminat ve kredi limitleri tanımlanmadığından siparişin teyit almasının engellenmesi için müşteri
ana verisi üzerindeki sipariş/teslimat blokaj alanı kullanılacaktır. Bu alan entegrasyonla diğer sistemlere bilgi olarak iletilecektir.
MARS sisteminde müşteri kodu bazında sipariş verilebilecek ürünlerin listelenmesi için malzeme listeleme verisi kullanılacaktır. VB01
işlemkodundan standart SAP fonkisyonu olan malzeme listesi tanımlanacaktır. Z001 erişim sırasından erişilebilecektir.
Siparişlerin hangi sistemden yartıldığı bilgisi SOURCE alanından takip edilmektedir. Bu SOURCE alanı SAP başlık verilerinde VBKDBSARK alanından takip edilmektedir.SOURCE listesi aşağıdaki gibidir.

A001

Cutover

A100

MARS

A101

MARS-İade

A110

SALESFORCE

A120

GATEWAY (Personel)

A130

RAPİD - Mağazacılık

A131

RAPİD - Bayi

A140

SARIS Ürün Değişimi

A141

SARIS Yedek Parça

A142

SARIS Ek Garanti


<<< SAYFA 6 >>>
A143

TH Portal

A144

ZZBAPI_SALESORDER_GE

A145

ZSD_RFC_SALESDOCUMEN

A146

Beko UD Hurda Satışı

A150

VSRM

A151

VSRM - EDI

A160

ECC Satıcı

A161

ECC YP Ihracat

A170

DIA

A180

Connecta

A190

SAP Excelle Aktarım

A200

H2O

A210

D2D (SF)

A220

SAP İade Kokpiti

A230

Arbarcode

A240

Total

A250

ORTEC (LOTUS)

A260

Manusoft

A270

BOD

A280

IPSOS

A290

Agilone

A300

arcelik.com.tr

A301

beko.com.tr

A302

grundig.com.tr

A303

altus.com.tr

A304

OLIZ ek garanti

A305

Hepsiburada-Grundig

A306

Hepsiburada- Altus

A307

Trendyol-Altus

A308

Trendyol-Grundig

A309

Amazon-Altus

A310

Amazon-Grundig

A311

N11-Altus

A312

N11-Grundig

A313

DROP:arcelik.com.tr

A314

DROP:beko.com.tr

A315

OLIZ plus üyelik

A320

ECC Müşteri

A350

COSMOS


<<< SAYFA 7 >>>
A360

ABS

A400

Fiktif Çözme

A401

Fiktif->Emanet Dönüş

A410

RPA

A420

Koçdiligence

A430

SRM

A440

QLIK

A900

ECC Malz.Blokaj

A999

Manuel

Z002

havuz kodu

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Sales From Stock

4. Arçelik Senaryolara Genel Bakış
4.1.

Yetkili Satıcı Satış Sipariş Süreçleri

Yetkili Satıcı yani bayilerin ürün siparişi süreçleri bu başlık altında toplanmıştır.

4.1.1.

OTC-060-010-010 - Yetkili Satıcı Kanalı Bayi Standart Sipariş

4.1.1.1.Sürece Genel Bakış
Yetkili satıcı siparişleri Mars Sistemi aracılığı ile SAP sistemine aktarılacaktır. Bu entegrasyon aracılığı ile ZS01 bayi standart sipariş
türü oluşturulacaktır.
Standart siparişler ilgili ayın 5 inden sonra girilen siparişlerdir.
MARS Sisteminde sipariş girişinde yapılacak kontroller S4HANA da da uygulanacaktır. Siparişler manuel de girilebileceği için aynı
kontrollere S4Hana da da takılması gerekecektir. Bu kontroller;
1) Sipariş girişinde ilk hafta bayi alokasyonu, ikinci hafta hat, 3.hafta bölge ve son hafta şube alokasyonuna bakılarak S4'da da sipariş
girişi yapılmalıdır. Buradaki haftalık olarak bakılan alokasyon aAtp tarafında yönetilmektedir. S4 da oradaki yönetime göre çalışmalıdır.
2) Mevcut durumdaki karar M ayına sipariş geçilmesidir. İleri tarihli sipariş girişi S4'da da yapılamamalıdır. İleride M+1 için de sipariş
geçilmesi istenebilir, buradaki yönetim konfiguratif olmalıdır.
3) Fiyatı tanımlı olmayan ürünler MARS ta sepete eklenemeyecek ve siparişoluşturulamayacaktır.
4)Sipariş blokajı olan müşteriler içinsipariş geçilemeyecektir.
5)Duplike sipariş olmaması adına her bir MARS sepet ID ile tek bir sipariş oluşturulabilecektir. (SepetID bilgisi,S4 da malı teslim alan
referans alanından takip edilecektir. )
6)Tüketici Teslim siparişlerde girilen Adres bilgisinin SARIS teki adres verisiyle uyumlu olmasıbeklenmektedir. Uyumlu değilse sipariş
kaydedilememektedir.(İl-ilçe-mahalle bilgisi)
7)Sipariş miktarı arttırılamaz, azaltılabilir.

Yukarıdaki kontrolleri (1-2) sağlamak için ATP'den bilgileri alacak ve hata dönmemiz sağlayacak veriler elde edilmelidir. Bu veriler FTD
tarafından sağlanacaktır.
Perakende destek malzemeleri (aksesuar) bayi yönetmeni ve bayiler tarafından sipariş girilecektir.


<<< SAYFA 8 >>>
Kompakt Paket kampanya uygulaması yapılmayacak, ilgili kampanyalar malzeme üzerinde iskontolar ile yönetilecektir. Kampanyalar
satış belgesi bazında çalışacaktır.
Tüketici teslim siparişleri ;
Bayilerin siparişleri son müşteriye gönderdiği senaryodur.
Her ürün için tüketici teslim yapılamamaktadır, ürün ana verisinde bu bilgi tutulacaktır. Hem S4 hem Marsta sipariş girerken bu ürünler
için tüketici teslim seçeneği çıkmayacaktır. Ürün ana verisinde aşağıdaki alanlardan tüketiciteslim edilebilir bilgisi kontrol edilmektedir.
Ürün montajlı ve/veya nakliye hizmeti var ise tüketici teslim edilebilir , değilse tüketici teslim edilemez işareti otomatikolarak tikleniyor.

Her bayi de tüketici teslim sipraiş geçemeyecektir. BP anaverisinde aşağıdaki alandan tüketici teslim sipariş verip veremeceği takip
edilebilecektir.

Bayi ana verisi üzerinde bayinin müşterilerinin adresi tutulacaktır. Eğer bayinin müşterileri arasında teslim edilmek istenen adres yok
ise; MARS ekranlarından bayi üzerine yeni müşteri adresi eklenebilecektir. Varolan adresler MARS aentegrasyon ile gönderilecektir.


<<< SAYFA 9 >>>
Bayi Mars ekranından tüketici teslim siparişi açabilecektir. Bu süreç öneri miktarlarından bağımsız olarak Mars ekranından ayrıca
girilecektir. Sistemde açılan tüketici teslim kesin siparişinin önceliği olacaktır. Tüketici teslimlerde, Sevk siparişi bayi yönetmeni
tarafından isterse silinebiliyor(iptal edilebiliyor) olacaktır. Bayiler ve satış ekibi alokasyon varsa tüketici teslim siparişi girebilmelidir.
Alokasyon tükenmiş ise tüketici teslim siparişi girişi için bir sonraki ay beklenmeli veya hak transferi ile sipariş alınması yoluna
gidilmelidir.
Sipariş üzerinde Tüketici teslim bilgisi sipariş başlığı bazında tutulmaktadır. BAşlık verilerinde sevkiyat tabında; SEVK TÜRÜ alanı 20 ise
tüketici teslim siparişi anlamına gelmektedir. Tüketici teslim siparişlerinde teslim edilecek adres bilgisi yine sipariş başlığı bazında
tutulan muhataplarda WE ve Z4 muhatap rolü içerisinde güncellenmektedir.
Bayi tüketici teslim siparişlerini RAPID sistemi üzerinde takip etmek isterse; Önce RAPID sisteminden tüketici teslim ön siparişi
yaratacaktır. Ön sipariş S4 sisteminde teklif belgesi olarak yaratılacak ve ZT01 belge türünden takip edilebilecektir. Bu ön siparişler
MARS sistemine S4 dan gönderilecektir. MARS ta listelenen ön siparişleri arasından bayi bu siparişleri gerçek siparişe
dönüştürebilecektir. Teklif belgesi referansı ile gerçek sipariş oluşmayacaktır. Ön sipariş üzerindeki detaylar yeni bir siparişe MARS
tarafından kopyalanacaktır. Sipariş üzerinde ön sipariş bilgisi (VBAP-ZZ1_ONSIPARIS_SDI) Z li alanda tutulacaktır. Bir ön sipariş
parçalı olarak gerçek siparişe dönüşemeyecektir.
Tüketici teslim siparişlerinde; montajlı ve ya nakliye hizmeti bulunan ürünler var ise bu siparişler için yetkili servis ataması yapılması
gereklidir. Yetkili servis ataması SARIS sistemi tarafından gerçekleştirilmektedir. S4 da tasarlanan bir program aracılığı ile S4 ile SARIS
arasında entegrasyon sağlanarak, bu siparişler için SARIS sistemine iş emri açılması sağlanmakta ve entegrasyon karşılığında SARIS
ten ilgili ürün kodu ve teslim edilecek adres bilgisine göre (il- ilçe-mahalle tutarlılığı) yetkili servis bilgisi alınmaktadır.
Bu yetkili servis bilgisi sipariş başlık verilerinde Z3 muhatabında takip edilecektir. Bu siparişler için (montajlı veya nakliye hizmeti ürünü
içeren tüketici teslim siparişleri) Z3 muhatabı olmadan sevk işlemleri başlatılamamaktadır.
Henüz sevk adımları başlatılmamışsiparişler için tüketici teslim iş emri yaratma entegrasyonu çalışacaktır. Sevk adımına kadar ise
atanan yetkili serviste iptal değişiklik varsa iş emri sorgula programı jobı çalıştırılacaktır.

Mars Checkout ekranında; Adres, seçimi yapılacaktır. Nihai Müşteri seçilebilecek yoksa yaratılabilecektir. Ödeme planı seçimi
yapılacaktır. Ödeme yöntemi belirlenecektir. Vade bazında fiyat alternatifleri SAP sisteminden Mars sistemine checkout ekranına
gönderebilecek, bayi bu fiyatlardan birini seçecektir. Vade farkı ve kampanya koşulları ayrı olarak her satır bazında SAP sisteminden
Mars sistemine gönderilecektir. Fiyatlar satır bazında tek tek SAP sisteminde işlenecektir.

4.1.1.2. Süreç Adımları

Süreç
Adım
No

Süreç Adımı

İşlem Kodu /
Fonksiyon Adı

Entegrasyon
Kaynak
Sistem

Job


<<< SAYFA 10 >>>
1

Ay kapanışı ve stok durumuna göre bayiler bazında alokasyon adetleri belirlenir. Bayiler
alokasyon adetleri kadar Mars Sisteminden sipariş geçebileceklerdir. Sonrasında SAP ‘ye sipariş olarak
aktarılır.

ZAATP_FM_MARS_01 S4

S4 da
tetikle
nen
bir job
bulun
muyor.
MARS
istenile
n
sıklıkta
ilgili
servisi
çağırar
ak
bilgileri
alıyor.

2

Mars sistemine öncelikle anaverilerin gönderimi sağlanacaktır. Müşteri, malzeme, liste fiyatı, stok bilgisi,
ürün hiyerarşisi ,ürün listeleme Mars Sisteminde de görüntülenebilecektir.

Müşteri :

S4

S4 da
tetikle
nen
bir job
bulun
muyor.
MARS
istenile
n
sıklıkta
ilgili
servisi
çağırar
ak
bilgileri
alıyor.

S4

S4 da
tetikle
nen
bir job
bulun
muyor.
MARS
istenile
n
sıklıkta
ilgili
servisi
çağırar
ak
bilgileri
alıyor.

ZSD_FM_RFC_BP_C
REATE
Malzeme:
ZMM_FM_MATERIAL
_DATA
Ürün hiyerarşisi
: ZSD_FM_PRODUC
T_HIERARCHY
Bayi ürün eşleşmesi
gönderimi:
ZSD_FM_CUST_MAT
ERIAL_LIST
Ürün fiyat
gönderimi:
ZSD_FM_GET_PRICE
_LIST
ZX01 -toptan fiyat
ve ZX02 -perakende
fiyat bilgileri
gönderilmektedir.
Silinmiş fiyatlar
gönderilmemektedir.

3

Mars Checkout ekranında; Adres, seçimi yapılacaktır. Nihai Müşteri seçilebilecek yoksa yaratılabilecektir.

Bayi müşterileri
yarat RFC :
ZSD_FM_RFC_BP_C
REATE
Bayimüşterileri
listeleme RFC :
ZSD_FM_RFC_BP_C
UST_LIST

4

Mars Checkout ekranında;Vade bazında fiyat alternatifleri SAP sisteminden Mars sistemine checkout
ekranına gönderebilecek, bayi bu fiyatlardan birini seçecektir. Vade farkı ve kampanya koşulları ayrı
olarak her satır bazında SAP sisteminden Mars sistemine gönderilecektir. Fiyatlar satır bazında tek tek
SAP sisteminde işlenecektir.

ZSD_FM_SALESDOC
UMENT_SIMULATE

S4

S4 da
tetikle
nen
bir job
bulun
muyor.
MARS
istenile
n
sıklıkta
ilgili
servisi
çağırar
ak
bilgileri
alıyor.

5

RAPID Ön sipariş yaratılma adımı

ZSD_FM_SALESDOC
UMENT_CREATE

S4

RAPID
tetikliy
or.


<<< SAYFA 11 >>>
6

RAPID Ön siparişlerin MARS a gönderilmesi

ZSD_FM_SALESDOC
UMENT_LIST_OFFR

S4

S4 da
tetikle
nen
bir job
bulun
muyor.
MARS
istenile
n
sıklıkta
ilgili
servisi
çağırar
ak
bilgileri
alıyor.

7

Tüketici teslim siparişlerinde; montajlı ve ya nakliye hizmeti bulunan ürünler var ise bu siparişler için
yetkili servis ataması yapılması gereklidir. Yetkili servis ataması SARIS sistemi tarafından
gerçekleştirilmektedir. S4 da tasarlanan bir program aracılığı ile S4 ile SARIS arasında entegrasyon
sağlanarak, bu siparişler için SARIS sistemine iş emri açılması sağlanmakta ve entegrasyon karşılığında
SARIS ten ilgili ürün kodu ve teslim edilecek adres bilgisine göre (il- ilçe-mahalle tutarlılığı) yetkili servis
bilgisi alınmaktadır.

Program adı :
ZSD_0032

S4- SARIS

ZSD_J
OB_VA
RY_1
varyan
tı
ileçalış
makta
dır.

S4-SARIS

ZSD_J
OB_VA
RY_1
JOB:
Montaj
Talebi
Sorgula

Servis: ZSD_FM_TU
KETICI_TESLIM_OLU
STUR
Oluşan iş emri
numarası : VBAKZZ1_THWORKORDE
R_SDH alanından
takip edilir.
Atanan servis
bilgisi başlık Z3
muhatabından takip
edilir.

8

Henüz sevk adımları başlatılmamış siparişler için tüketici teslim iş emri yaratma entegrasyonu
çalışacaktır. Sevk adımına kadar ise atanan yetkili serviste iptal değişiklik varsa iş emri sorgula programı
jobı çalıştırılacaktır.

Program adı:
ZSD_046
Servis : ZSD_FM_T
UKETICI_TESLIM_S
ORGULA

ZSD_J
OB_VA
R_BY
JOB:
Montaj
Talebi
Sorgul
a BY
ZSD_J
OB_VA
R_KS
JOB:
Montaj
Talebi
Sorgul
a KS
ZSD_J
OB_VA
R_OT
JOB:
Montaj
Talebi
Diğer


<<< SAYFA 12 >>>
9

Sipariş kalemi iptal ediliği durumda açılan iş emri var ise SARIS e iptal bilgisinin gönderilmesi

Program adı
: ZSD_0052

S4-SARIS

ZSD_J
OB_VA
RY_1
JOB:
Montaj
Talebi
İptal
ZSD_J
OB_VA
R_BY
JOB:
Montaj
Talebi
İptal
BY
ZSD_J
OB_VA
R_KS
JOB:
Montaj
Talebi
İptal
KS
ZSD_J
OB_VA
R_OT
JOB:
Montaj
Talebi
İptal
Diğer

Servis: ZSD_FM_TU
KETICI_TESLIM_IPT
AL

10

MARS ekranlarından sepete eklenen ürünlerin fiyat, adres, malı teslim alan, vade, emanet, tüketici teslim
gibi detayları kontrol edildikten sonra sipariş kaydedilecektir.

ZSD_FM_SALESDOC
UMENT_CREATE

S4

MARS
tetikliy
or.

11

MARS ekranlarında ilgili bayi önceden oluşturduğu siparişleri açık/teyitlenmiş/faturalanmış siparişlerlistesi
ekranında listeleyebilecektir.

ZSD_FM_SALESDOC
UMENT_LIST_STAT

S4

MARS
tetikliy
or.

12

Listeleme servisinden dönen siparişler arasından bayi açık siparişlerini ve teyitlenmiş ama henüz
teslimatbelgesi yaratılmamış siparişlerini güncelleyebilir olacaktır. Güncelleme adımı :

ZSD_FM_SALESDOC
UMENT_CHANGE

S4

MARS
tetikliy
or.

13

Oluşturulan ve güncellenen siparişler VA03 ekranından görüntülenip kontrol edilecektir.

VA03

S4

14

MARS ekranlarından görüntülenen ve değiştirilebilen her sipariş S4ekranlarında VA02 den de
güncellenebilir.

VA02

S4

4.1.1.3. Süreç Akışları


<<< SAYFA 13 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/a22d1f71-c211-40ea-9474-539c817c2d12/SPFID/41736402-5db2-489f-85a0-6635e7980cba/?
tab=SPF

4.1.2. OTC-060-010-020 - Yetkli Satıcı Kanalı Ay Başı Öneri Sipariş
4.1.2.1.Sürece Genel Bakış
Ay başı öneri siparişleri de Mars Sistemi entegrasyonu ile SAP sistemine alınacaktır.
Ay başı öneri siparişleri ilgili ayın ilk 5 gününde gerçekleşen siparişlerdir.

4.1.2.2. Süreç Adımları
Ay başı öneri siparişleri, standart siparişleri ile aynı entegrasyon ile alınacaktır. Süreç akışı aynı olacaktır. Raporlaması ve takibi
açısından ayrı bir belge türü ile yürütülecektir. Belge türü ZS03 kullanılacaktır. Herhangi bir onay süreci olmayacak. Bayi kendi sipariş
geçmek (onaylamak) istediği durumda ayrı ayrı sipariş olarak ayın 5 ine kadar iletebilir.

Lansman ürün satışları
Lansman ürün satışları 3 aşamada gerçekleşecek.
Öncelik FISO bayilerine verilecek. FISO bayiler siparişlerini geçtikten sonra kalan ürünler arasında öncelik Promotör bayilere
tanınacaktır.
Promotör bayilerin siparişlerinden sonra ise kalan ürünler normal bayilere satışa açılacaktır.
Bu öncelik sırasına göre bu bayilere ayrılacak miktarları Pazarlama ekibi belirlemektedir.
FISO bayilerine ve Promotör bayilere Pazarlama birimi tarafından ayrılan miktarlar için S4 Hana sisteminde sözleşme belgesi
oluşturulacaktır. Bu sözleşmeler toplu sipariş/sözleşme yaratma programı ile S4 hana sisteminde toplu yaratılabilecektir.
FISO bayileri siparişleri aynı program ile sözleşme referanslı olarak oluşturulacaktır.
Promotör bayiler için siparişler Mars öneri sipariş ekranından girilebilecektir. Promotör bayiler için ayrılan miktarları takip edebilmemiz
için Pazarlama birimi tarafından açılan sözleşmelere referans ile yaratılacaktır.
FISO ve promotör bayiler siparişlerini geçtikten sonra kalan miktarlar diğer bayilere siparişe açılacaktır.
Bayi-ürün listeleme ile bu ürünler bayilere belirli geçerlilik günlerinde Mars sisteminde listelenecektir.
S4Hana sistemine yansıyan siparişlerde, standart bayiler için açılan lansman ürün siparişlerinde sözleşme referansı yok ise ve bayiürün listelemesinde yok ise sipariş açılamasın şeklinde kontrol koyulup süreç yönetilecektir.
Süreç
Adım
No

Süreç Adımı

İşlem Kodu /
Fonksiyon Adı

1

MARS sistemine S4 dan ürün öneri miktarlarını
gönderme servisi kullanılacaktır.

ZSD_FM_SALESDO S4
CUMENT_SUGGEST

2

Bayi standart satış sürecindeki süreç adımları
2. adımdanitibaren birebir devam etmektedir.

4.1.2.3. Süreç Akışları

Entegrasyon
Kaynak
Sistem

Job

S4 da tetiklenen bir job bulunmuyor. MARS
istenilen sıklıkta ilgili servisi çağırarak bilgileri
alıyor.


<<< SAYFA 14 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/da0342e7-f0e1-4d8b-ae20-5f7bd8ff8b52/SPFID/c33841f9-acce-4466-a3da-e588982a3f17/?tab=SPF

4.1.3. OTC-060-010-030 - Yetkili Satıcı Kanalı Skala Süreci
4.1.3.1.Sürece Genel Bakış
Yeni bayiler, eski bayilerin yeni mağazaları ve kadın bayilerin yeni mağazaları için oluşturulan teklif siparişleri ''skala siparişler'' olarak
adlandırılmaktadır. Aynı zamanda doğal afet, Anadolu’ya dönüş projeleri, Hedef Bayi gibi durumlarda istisnai skala süreci
uygulanmaktadır. Bayiler için oluşturulan skala siparişleri belirli bir grup ürünün teşhir amaçlı bayilere indirimli olarak gönderilmesidir.
Skala ürünleri Pazarlama ekipleri tarafından manuel belirlenmektedir. Sistem üzerinde ana veri açısından takip edilen birparametre
bulunmamaktadır.

4.1.3.2.Süreç Adımları

Skala onay süreci S4/HANA sisteminde workflow ile yürütülecektir. Skala indirimleri içeren siparişler bayi yönetmenleri tarafından SAP
sisteminden manuel girilecektir.
Mars sisteminden bu tip siparişler gelmeyecektir.

Kadın bayi özelliği için müşteri anaverilerinde bu bilgi tutulacaktır.
Süreç
Adım
No

1

Süreç Adımı

İşlem
Kodu /
Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Skala siparişlerinde bayinin mağazasının büyüklüğüne M2 ne göre ürün bazında kaçar adet sipariş
girilebileceği ile ilgili bir ön çalışma "Pazarlama" ekipleri tarafından yapılacaktır. Bu çalışma bir excel
dökümanında takip edilecektir. Bu dökümandaki ürün kodları ve sipariş adetlerine göre sipariş öncesinde
S4HANA'da satış sözleşme belgesi pazarlama birimleri tarafından yaratılacaktır.

ZSD_0013 Excel
Upload
Programı

S4

ZSD_0013 Excel
Upload
Programı

S4

Skala Sözleşme Belge Türü: ZQ02

2

Skala siparişleri, bayi yönetmenleri tarafından bu sözleşmelere referans ile yaratılacaktır. Böylelikle
miktar kontrolü sağlanabilecektir.
Skala Sipariş Türleri iki farklı türde raporlama amaçlı takip edilecektir. Sistemsel olarak iki sipariş türünde
de aynı yapı ve kontroller işlemektedir.
ZS04

Bayi yeni açılış skala

ZS16

Skala Siparişleri


<<< SAYFA 15 >>>
3

Skala siparişleri oluşturulduktan sonra onay süreci başlar. Siparişin onaya gittiği bilgisi sipariş teslimat
blokajı alanından takip edilecektir.
ZT teslimat blokajı - ZS04
ZS teslimat blokajı - ZS16

4

Skala siparişlerinde 3 adımlı onay süreci vardır. Onaycılar bayi yönetmenine(hat) göre belirlenir.
ZFL_0002 işlem kodundan onay adımları görüntülenebilir. bu işlem kodunun detayları OTC-060-010-090
- İklimlendirme Sipariş Süreçleri - Süreç adımları 8 kısmında bahsedilmiştir.
Siparişin üzerindeki hat bilgisinden ZSD_V_HAT_DETAIL tablosuyla personel kodu bulunur. Bu personel
koduyla HR tablolarından onaycılar bulunur.
Onay prosedürler: SD_SKALA1(ZS16) ve SD_SKALA2(ZS04)
Satış Bölge yöneticisi
Satış Şube direktörü
Satış Kıdemli Direktör


<<< SAYFA 16 >>>
5

Toplu onay/ret zsd_0031 işlem kodundan yapılmaktadır. Skala siparişleri onayı için aşağıda işaretli olan
radyo buton seçilmelidir.

Onaycı sadece kendi onayında bekleyen belgeleri listeleyebilir.
Onaylamak istediği satırı seçmelidir ya da tüm satırları seçebilir.
İşlem yapmak istediği satırı seçtikten sonra belgeyi onaylar ya da ret eder.
Başlık bazından onay vardır.
Bir siparişte birden fazla kalem varsa sadece tek bir satırı seçip onaylaması/reddetmesi mümkündür.

Belge onaylandıktan sonra belgenin başlığındaki teslimat blokajı kaldırılır.
Belge ret edildikten sonra belgenin kalemlerine ret nedeni(ZW) koyulur.
6

Onaylar SAP Inbox veya Fiori Inbox'tan münferit olarak da verilebilmektedir.

4.1.3.3. Süreç Akışları


<<< SAYFA 17 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/e44387d9-d664-4307-a280-52516effa81e/SPFID/64f5f1f6-d9d2-4f5d-8abf-dad70b8d7b33/?tab=SPF

4.1.4. OTC-060-010-040 - Yetkili Satıcı Kanalı Ön Ödemeli Sipariş
4.1.4.1.Sürece Genel Bakış
Yetkili satıcı standart satış siparişinden farklı olarak ön ödeme alınma işlemi vardır.

4.1.4.2.Süreç Adımları
Yetkili satıcı Mars sisteminden sipariş girerken ön ödemeli seçeneği ile ilerleyecek.
Sipariş SAP sistemine geldiğinde sisteme ödemenin yansıyıp yansımadığı kontrol edilecek.
Bu kontrol için kredi yönetimi/finans birimiyle konuşulacak. Eğer ödeme gelmediyse siparişe teslimat blokajı konulacak. Ödeme
geldiyse bayi standart satış sürecindeki gibi standart süreç devam edecek.
Projenin canlı geçişi ile beraber kullanılması beklenmemektedir. Sonraki fazlarda kullanılacaktır.

4.1.4.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/e8e7bdd6-3b7c-4c8a-9e3a-e9fb42541938/SPFID/f7827aa2-0a71-4f2a-b0d7-491b019c6d54/?
tab=SPF

4.1.5. OTC-060-010-050 - Bayi (Yetkili Satıcı) Kanalı Hakediş Sipariş
4.1.5.1.Sürece Genel Bakış
Yetkili satıcıların ürünleri normal fiyatından değil de ek indirim uygulanarak almasına olanak sağlayan sipariş türü olarak
kullanılmaktadır. Belge türü ZS13 olarak sistemde tanımlıdır.
Sipariş girişleri sadece VA01 den manuel olarak ilerleyecektir, Mars ya da herhangi bir 3RD uygulama ile entegrasyonu yoktur, Satış
İşlemlerini Pazarlama ekibi girecektir.
Normal süreçlerdeki indirim haricinde bu sipariş türünde doğrudan bayinin Oliz indirim hakediş faturası kesmesi yerine faturaya karşılık
olacak şekilde ekstra indirim tanımlaması yapılarak fatura yerine indirimli ürün satışı hedeflenmektedir.
Burada ayri belge türü olarak konumlandırılmasının sebebi perakende indirim kampanyalarına istinaden indirim uygulayarak hem ürün
satışını arttırmak hem de Yetkili satıcıya hakettiği indirimi vermek iki taraflı katkı sağlamasından dolayı.

4.1.5.2.Süreç Adımları


<<< SAYFA 18 >>>
Bu sipariş türüne özel indirim koşul türü tanımlanacaktır.
İndirim türü olarak ZD04 koşul türü kullanılacaktır. Hakediş tutarına göre uygulanacak indirim oranı/tutarı SAP dışında hesaplanacak.

Hesaplanan oran/tutarlarla beraber Pazarlama birimi tarafından manuel bir şekilde SAP sisteminde oluşturulacaktır.
Sonraki adımlar bayi standart satış sipariş süreci ile aynı olacaktır.
Hakediş siparişleri yetkilendirme ile sadece pazarlama ekibi tarafından ret nedeni ile kapatılabilecektir. ( Geliştirme planlanıp
yapılacaktır )

4.1.5.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-ui-app-id-hint=com.sap.calm.imp.pmge.
authoring&/SI/742bb5d0-8f03-47af-ae8c-e8dda68420d6/SPFID/344df89c-03bd-48a7-8d90-f6fc3735cc5e/?tab=SPF

4.2. Alternatif Kanal Satış Süreçleri
Alternatif kanal satışları bu başlık altında konumlandırılmıştır. 601C satış organizasyonnu altından yapılan satışlardır.

4.2.1. OTC-060-010-060 - Altus Sipariş Süreçleri
4.2.1.1.Sürece Genel Bakış
AS Dağıtım kanalından yapılan satışlardır. Altus satış siparişleri SAP ye aktarımı MARS sistem entegrasyonu, VSRM Sistem
entegrasyonu ve ya excel ile sağlanacaktır.


<<< SAYFA 19 >>>
4.2.1.2.Süreç Adımları

Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon
Kaynak
Sistem

Altus siparişleri S4 da manuel VA01 veya excel upload ile
oluşturulabilecektir.

VA01

S4

Job

ZSD_0013 - Excel Upload Programı
BelgeTürü : ZS05

2

Altus toptancıları (Mediamarkt, Teknosa, Koçtaş) MARS Sistemine
erişebilecek ve sipariş oluşturabileceklerdir.

ZSD_FM_SALESDOCUMENT_CREATE

S4

ZSD_FM_SALESDOCUMENT_CREATE

S4

Belge Türü : ZS05
3

Altus bayileri ve zincir (A101,BİM,ŞOK) EDI ile sipariş
oluşturabileceklerdir. Hem standart hem tüketici teslim siparişi
oluşturabilirler.

4

Sipariş birleştirme Altus siparişlerinde kullanılmamaktadır. Bir siparişbir teslimat olarak süreç ilerlemektedir.

5

Sipariş referans alanında müşteri sipariş numarası takip edilmektedir.
Bu sipariş numarasının unique olması kontrolü bulunmaktadır. Müşteri
sipariş numarası, satış faturası üzerinde de zorunlu olarak yer
almaktadır.

6

Bu sipariş sürecinde teklif ve Skala süreci bulunmamaktadır.

Müşteri sipariş numarası kontrolü SD
alanı ve belge türü bazında aşağıdaki
bakım tablosundan sağlanmaktadır.
ZSD_T_SA_CUST

4.2.1.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/4909804e-94d2-4deb-97e3-6d8281731e8c/SPFID/c27685e4-d31d-4ed9-963e-3bfd7ee5e783/?
tab=SPF

4.2.2. OTC-060-010-070 - Grundig Sipariş Süreçleri
4.2.2.1.Sürece Genel Bakış
GR Dağıtım kanalından yapılan satışlardır.Grundig satış siparişleri SAP ye aktarımı MARS sistem entegrasyonu VSRM Sistem
entegrasyonu ve ya excel ile sağlanacaktır.

4.2.2.2.Süreç Adımları

MARS
tetikli
yor.


<<< SAYFA 20 >>>
Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon
Kaynak
Sistem

Grundig siparişleri S4 da manuel VA01 veya excel upload ile
oluşturulabilecektir.

VA01

S4

Job

ZSD_0013 - Excel Upload Programı
BelgeTürü : ZS05

2

Grundig toptancıları (GİZPA,GÜRSES) MARS Sistemine erişebilecek ve
sipariş oluşturabileceklerdir.

ZSD_FM_SALESDOCUMENT_CREATE

S4

ZSD_FM_SALESDOCUMENT_CREATE

S4

MARS
tetikli
yor.

Belge Türü : ZS05
3

Grundig bayileri ve zincir (A101,BİM,ŞOK) EDI ile sipariş
oluşturabileceklerdir. Hem standart hem tüketici teslim siparişi
oluşturabilirler.

4

Sipariş birleştirme Grundig siparişlerinde kullanılmamaktadır. Bir
sipariş- bir teslimat olarak süreç ilerlemektedir.

5

Sipariş referans alanında müşteri sipariş numarası takip edilmektedir.
Bu sipariş numarasının unique olması kontrolü bulunmaktadır. Müşteri
sipariş numarası, satış faturası üzerinde de zorunlu olarak yer
almaktadır.

Müşteri sipariş numarası kontrolü SD
alanı ve belge türü bazında aşağıdaki
bakım tablosundan sağlanmaktadır.
ZSD_T_SA_CUST

6

Bu sipariş sürecinde teklif ve Skala süreci bulunmamaktadır.

4.2.2.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/540cd686-c22d-4eb0-a158-5b63109524e5/SPFID/3dbc8379-3663-4844-bd3d-8b11ccaca2b4/?
tab=SPF

4.2.3.OTC-060-010-080 - VSRM Sipariş Süreçleri
4.2.3.1.Sürece Genel Bakış
Koçtaş, Mediamarkt, BIM ve ŞOK siparişleri VSRM entegrasyonu ile SAP ‘ye aktarım sağlanacaktır. Manuel ya da excel ile de
girilebilecektir.

4.2.3.2.Süreç Adımları
Koçtaş Grundig siparişleri VSRM sisteminden SAP sistemine entegrasyonla gelecektir. VSRM ürün kodları ve bayi kodlarını eşleştirme
servisleri olacaktır.
Koçtaş Altus siparişleri manuel ya da excel ile kontrollü bir şekilde SAP sisteminde girilecektir.


<<< SAYFA 21 >>>
SAP’de yeni malzeme tanımlandığında sadece KOÇTAŞ larda satılacak olan ürünler için VSRM sisteminde ürün kodu, tanımı vb. manuel
olarak açılacak. Burada VSRM deki ürün kodu ile SAP’deki ürün kodu eşlemesi entegratör firma tarafında yapılacak. Ayrıca Koçtaş ürün
numarasının SAP’de Müşteri-Malzeme Bilgi kaydı alanında tutulacaktır.
Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Koçtaş müşterisi entegrasyon ile sipariş oluşturabileceklerdir. Hem standart hem
tüketici teslim siparişi oluşturabilirler. Koçtaş'a özel olarak bir sipariş bir kalemdir.
Bunun sebebi bir siparişte farklı prim gruplarına ait ürünler olabilmektedir. Bu
durumda prim hesabı karışmaktadır. Bu karışıklığı önlemek için bir sipariş bir
kalem yoluyla ilerlenmektedir.

FM:
ZSD_FM_SLSDOC_CREATE
_WITH_ITEM

S4

Job

Koçtaş entegrasyonunda sevk müşteri kodu gönderilmektedir. Sipariş veren
kodunu müşteri-malzeme bilgi kaydı (KNMT) tablosundan biz bulmaktayız.
Mevcutta sipariş evren bayi kodları şu üçüdür: 20401, 20402 ve 20403.
Koçtaş'a satılan malzeme başka hiçbir müşteriye satılmamaktadır.
Koçtaş'a sadece Grundig ürünleri satılmaktadır.
Koçtaş'ta tüketici teslim süreci yoktur.
2

BİM,ŞOK ve Medimarkt satışları yapılmaktadır. Bim ve Şok da tüketici teslim
süreci vardır.

FM:
ZSD_FM_SALESDOCUMEN
T_CREATE
Include: zsd_i_salesdoc_c
re_vsrm_01

3

Sipariş referans alanında müşteri sipariş numarası takip edilmektedir. Bu sipariş
numarasının unique olması kontrolü bulunmaktadır. Müşteri sipariş numarası, satış
faturası üzerinde de zorunlu olarak yer almaktadır.

Müşteri sipariş numarası
kontrolü SD alanı ve belge
türü bazında aşağıdaki
bakım tablosundan
sağlanmaktadır.
ZSD_T_SA_CUST

4

Bu sipariş sürecinde teklif ve Skala süreci bulunmamaktadır.

5

Siparişler ZS05 belge türüyle oluşmaktadır.

6

Fiyat S/4 da belirlenmektedir.

7

Dağıtım kanalı S/4 da mal grubu ve alt marka ile belirlenmektedir.

4.2.3.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/ef85e75a-f646-4f09-b797-75d8feac53b0/SPFID/1c5c519e-6c7a-4c15-97c9-78ddbb8e0191/?tab=SPF


<<< SAYFA 22 >>>
4.2.4. OTC-060-010-090 - İklimlendirme Sipariş Süreçleri
4.2.4.1.Sürece Genel Bakış
2 türlü sipariş alımı mevcuttur:
İklimlendirme siparişleri bayi tarafından gelecekse MARS sistemi üzerinden teklif talebi- Sales Force teklifi(SF) – SAP teklif(ZT02 belge
türü) akışıyla yönetilecektir.
İklimlendirme siparişleri bayi yönetmenleri tarafından Salesforce sistemi üzerinden Sales Force teklifi(SF) – SAP teklif(ZT02 belge
türü) akışıyla yönetilecektir.

4.2.4.2.Süreç Adımları
İklimlendirme siparişleri bayi tarafından gelecekse MARS sistemi üzerinden teklif talebi- Sales Force teklifi – SAP teklif(ZT02 belge türü)
akışıyla yönetilecektir.
Bayi kanalı dışında kalan sipariş sürecinde teklif talepleri direkt olarak Sales Force sisteminde oluşturulacaktır. Salesforce sisteminde
girilen teklif talebi onay alındıktan sonra teklife dönüştürülecektir. Salesforce sisteminde teklif onaylandıktan sonra SAP sisteminde
teklif olarak yaratılacaktır. SAP sisteminde teklif belgeleri jobla satış siparişine dönüştürülecektir.
Teşvik kapsamında yapılan satışlar için katma değer vergisi 0 ve buna bağlı e-fatura istisna kodu seçimi ile ilerlenecek sipariş
belgelerinde tutulacak alanlar aşağıdaki gibidir:Teşvik belge numarası ve kalem numaraları, teşvik belge tarihi, her kalem için gtip
numarası, açıklama alanı(e-faturaya yazılacaktır.) Bu bilgiler entegrasyonla S4 a akacaktır.
Teklif PDF olarak sorumlu müşteri temsilcisine iletilecektir.Teklif kabul edildiği durumda bayiden kabul yazısı ve bazı dökümanlar talep
edilir ve bu dökümanlar SalesForce sisteminde teklif belgesi üzerine eklenecektir. SAP sistemine teklif belgesi olarak aktarılacaktır.
(istenilen dökümanlar ; bayinin fırsatı sunduğu firmanın kaşesi (vergi numarası yazılı), adresi kaşe bulunmuyorsa vergi levhası, adi
ortaklık ise; iki ortağın vergi levhası ve ortaklık yazısı, müşterinin fırsatı hangi montaj adresine ve hangi tarihte istediğine dair adet ve
fiyat yazılı imzalı kaşeli kağıt)

1

Teklif talebi Mars'tan Salesforce'a yansır.

Sal
esf
orce

2

Teklif talebi Salesforce'da düzenlenir.

Sal
esf
orce

3

Teklif talebi S/4 a yansır.

FM:
ZSD_FM_SALE
SDOCUMENT_
Create

S
/4

INC:
zsd_i_salesdoc
_cre_sf
4

S/4 da ZT02 belge türü ile (VA23 işlem koduyla)belge görüntülenir.
SF'den tetiklenen tüm teklifler S/4 da ret nedeni(ZT) ile oluşur ve belge oluşur oluşmaz Workflow(WF) tetiklenir.

S
/4


<<< SAYFA 23 >>>
5

Teklif belgeleri zsd_0056 işlem kodundan toplu olarak, SAP Inbox veya Fiori Inbox'tan onaylanır/reddedilir.

zsd_0056

S
/4

zsd_0056 işlem kodundan teklif kalemleri aşağıdaki gibi toplu veya münferit onaylanabilir:

Onay devam eden belgeler seçimi çalıştırılınca sadece onay süreci devam eden belgeler listelenir. Sadece ilgili onaycı kendi onay
verebileceği/reddebileceği kalemleri listeleyebilir.

Seçilen kalemler onaylanır veya ret edilir. Onaylanan kalemler Onay Tamamlanmış Belgeler seçimi çalıştırılınca listelenmektedir.
Listelenen kalemler jobla siparişe dönüşmektedir veya ilgili satır seçilerek sipariş oluştur butonuna basılarak sipariş belgesi
oluşturulmaktadır.

6

Teklif belgeleri için WF kalem bazında yürütülmektedir. Kalemler onaylandıktan sonra kalem bazında ret nedeni kaldırılmaktadır.
Reddedilirse ret nedeni(ZW) değiştirilmektedir.

S
/4

7

Onaycılar kalem bazında önce ZSD_T_TEKLIF_EK((işlem kodu: ZSD_T0080) tablosundan belirlenmektedir. Eğer bu tabloda kayıt
bulunmazsa ZSD_T_TEKLIF_ONY(işlem kodu: ZSD_T0040) tablosundan belirlenmektedir.

S
/4

8

Onaycılar bu 2 custom tablodan belirlendiği gibi ayrıca ZFL_0002 işlem kodunda da belirlenmektedir. Bu işlem koduna gidilir.
SD_TEKLIF onay prosedürü seçilip enter a basılır. Aşağıda bulunan ekran görüntüsündeki ikona basılır. Onay sürecine dahil olan satış
alanları ve belge türleri ZSD_IADE_SKL_SLS tablosundan belirlenmektedir.

S
/4

Manuel olarak da onaycı(lar) bu şekilde eklenir.


<<< SAYFA 24 >>>
Vekalet süreci de onay adımlarında mevcuttur ama vekil belge oluşturulmadan önce tanımlanmalıdır.. Belge oluşturulduktan sonra
tanımlananan vekaletler geçerli değildir. Vekiller ancak tanımlamadan sonra olulşan belgeleri onaylayabilir/reddedebilir.
Vekil aşağıdaki gibi tanımlanır:
1-SAP Business Workplace e gidilir.

2-Aşağıdaki adımlar takip edilir:

3- İkonu seçip Vekil yarat'a basılır.


<<< SAYFA 25 >>>
4- Ad göre arama yapılır.

5-Vekalet verilmek istenen kişi seçilir.

6- İstenilen period seçilir ve vekalet etkin'e basılır ve kaydedilir.


<<< SAYFA 26 >>>
7-Vakelet silinmek istenirse aşağıdaki adım takip edilir.

8- Vekil silindi.

Workflow tetiklendiğinde onaycıya ilgili belgenin kendi onayında beklediğine dair mail gitmektedir(bilgilendirme maili).
Aynı zamanda hat sahibine workflowun ilk tetiklendiğinde ve sona erdiğinde mail gitmektedir.Workflow ilk tetiklendiğinde onay
sürecinin başladığına dair mail gitmektedir. Belge onaylandığında/ret edildiğinde bu bilgi hat sahibine gimektedir.
ZFL_0004 raporunda belgenin onay durumu görülebilmektedir.
Onay durumu raporlanmak istenen belge no *1100632936* şeklinde arasına belge no yazılarak görüntülenebilir.


<<< SAYFA 27 >>>
ALV deki kritik alanlar aşağıdaki gibidir.

9

Jobla teklif siparişe dönmektedir.

10 Fiyatlar manuel koşul olarak SF den gelmektedir.
11 Döviz para birimi olarak fiyat girilse bile belge para birimi TRY dir.
12 Vergi muaf süreçleri siapriş nedeni alanıyla yönetilmektedir.
13 S/4 daki müşteri ve malzeme bilgileriyle sipariş açılmaktadır.
14 Sipariş veren ve malı teslim alan kodları aynı olup adresleri farklılaşabilmektedir.
15 Sevk adresleri kalem bazında değişebilmektedir.
16 Siparişlerde(ürün ağacı) parçalı ürün olabilmektedir. Fiyat sadece ana kalem için girilir. Alt kalemlere dağıtılır.

4.2.4.3. Süreç Akışları

Program:
ZSD_P_WF_SF
_TEKLIF_ONAY

S
/4

ZSD:
WF
TEKL
IF


<<< SAYFA 28 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/2c917e13-d71f-408e-ad16-a5dbe70c819d/SPFID/e5a4944d-f4b8-40c7-a78f-143c46d831cb/?
tab=SPF

4.2.5 OTC-060-010-100 - Solar Sipariş Süreçleri
4.2.5.1.Sürece Genel Bakış
2 türlü sipariş alımı mevcuttur:
Solar siparişleri bayi tarafından gelecekse MARS sistemi üzerinden teklif talebi- Sales Force teklifi(SF) – SAP teklif(ZT02 belge türü)
akışıyla yönetilecektir.
Solar siparişleri bayi yönetmenleri tarafından Salesforce sistemi üzerinden Sales Force teklifi(SF) – SAP teklif(ZT02 belge türü) akışıyla
yönetilecektir.

4.2.5.2.Süreç Adımları
Solar panel satış sürecinde; Salesforce sisteminde teklif çalışmasından sonra mutabık kalınan tutar üzerinden ön ödeme
alınabilmektedir.
Alınan ödeme Salesforce teklif numarası referansı ile SAP sistemine muhasebe belgesi olarak girilecektir.
Ödemenin alınmasına bağlı olarak salesforce sisteminden SAP sistemine teklif belgesi alınacaktır.
SAP sistemindeki teklif belgesinde Salesforce sistemindeki teklif belge numarası bulundurulacaktır.
Solar panel satış süreçlerinde döviz birimi cinsinden fatura kesilebilmektedir.
Teklif PDF olarak sorumlu müşteri temsilcisine iletilecektir.Teklif kabul edildiği durumda bayiden kabul yazısı ve bazı dökümanlar talep
edilir ve bu dökümanlar SalesForce sisteminde teklif belgesi üzerine eklenecektir. SAP sistemine teklif belgesi olarak aktarılacaktır.
(istenilen dökümanlar ; bayinin fırsatı sunduğu firmanın kaşesi (vergi numarası yazılı), adresi kaşe bulunmuyorsa vergi levhası, adi
ortaklık ise; iki ortağın vergi levhası ve ortaklık yazısı, müşterinin fırsatı hangi montaj adresine ve hangi tarihte istediğine dair adet ve
fiyat yazılı imzalı kaşeli kağıt)
Solar siparişlerinde; sipariş alamasında istenilen teslim tarihi manuel değiştirilebilir olacaktır. Parçalı teslimler için termin satırı bazında
istenilen teslim tarihi değiştirilebilecektir. Örneğin 10000 adetli bir siparişte 3000 adedi Kasım ayında, 5000 adedi aralık ayında, 2000
adedi Ocak ayında şeklinde parçalanabilecektir.
Süreç
Adım No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Solar panel satışlarındaki süreçler iklimlendirme ile aynıdır. Tek
bir fark vardır:

FM:
ZSD_FM_SALESDOCUMENT_Cre
ate

SF

Solar panel satışlarında döviz cinsinden fatura kesilebilmektedir.
INC: zsd_i_salesdoc_cre_sf

4.2.5.3. Süreç Akışları

Job


<<< SAYFA 29 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/9dddf08b-5939-4497-acd3-ac4e4e8a86ec/SPFID/b12b1644-f364-43c4-b060-78c6b836f231/?
tab=SPF

4.3. Alternatif Kanal Kurumsal Standart Satış Teklif Referanslı
Kurumsal kanal; bayi kanalı ve direkt satış olarak ikiye ayrılmaktadır. Direkt satış DMO, B2C ve direkt satışlar olarak ayrılmaktadır.
Kurumsal kanal siparişleri TRY/USD/EUR olarak açılabilir ve döviz cinsindeki siparişler için fatura kesilirken faturalama tarihindeki
merkez bankası güncel kurundan çevrim yapılır. (Merkez bankası döviz kur tipi müşteri bazında farklı olabilir.)
Sipariş, valörü bozulmadan 60/90 gün sistemde kalmaktadır. Açık miktarlar 60/90 gün sonunda otomatik olarak kapatılmaktadır. Gün
bilgisi ürün bazında değişkenlik gösterebilmektedir.
Mutfak ve PGS (Profesyonel Görüntüleme Sistemleri) Kurumsal Kanal kapsamında benzer sipariş giriş süreçleri ve fiyatlandırma
mekanizmasıyla yönetilecektir.
Salesforce üzerinden teklif oluşturulurken emanet göstergesi de SAP S/4 HANA sistemine gönderilecektir.

4.3.1. OTC-060-010-110 - Bayiye yapılan Kurumsal Satışlar
4.3.1.1.Sürece Genel Bakış
Bayi kanalına yapılan kurumsal satışlardır.
Bayi kanalı tarafından alınmış Kurumsal siparişler bayi kanalı tarafından yönetilecektir. Bayi kanalı müşteri yönetmenleri SAP kokpit
ekranı üzerinden sipariş teslimat süreçlerini ilerletecektir. Stok alokasyonu kurumsal kanal üzerinden olacak ve stok yönetimi Kurumsal
Satışlar Direktörlüğü tarafından yapılacaktır.
Sipariş, valörü bozulmadan 60/90 gün sistemde kalmaktadır. Açık miktarlar 60/90 gün sonunda otomatik olarak kapatılmaktadır. Gün
bilgisi ürün bazında değişkenlik gösterebilmektedir.
Teklif belgesinde emanete alınabilirlik belge bazında takip edilecektir.

4.3.1.2.Süreç Adımları
Bayi kanalı için sipariş giriş akışı aşağıdaki gibi olacaktır :
-MARS sisteminden teklif talebi girilecektir. Teklif talebi MARS sisteminden Salesforce sistemine aktarılacaktır. Mevcut entegrasyonda
Sales Force'tan onaylanan teklif belgeleri otomatik yaratılmaktadır. Sevkiyat işlemlerini başlatabilmek için sipariş yaratılamadığı
durumda teklifin kesin satış siparişine dönüştürülmesi adımı job ya da manuel gerçekleştirilmelidir.
-Teklif talebi (fırsat) Salesforce sisteminde bölge yöneticisinin onayına gidecektir. Salesforce sistemindeki onay sürecine göre belgenin
durumu güncellenecektir.
-MARS sisteminde teklif taleplerinde (fırsat) değişiklik yapılamayacaktır.
-Salesforce sisteminde teklif talepleri (fırsat) teklif belgesine dönüştürülecektir.
-Teklif PDF olarak sorumlu müşteri temsilcisine iletilecektir.Teklif kabul edildiği durumda bayiden kabul yazısı ve bazı dökümanlar talep
edilir ve bu dökümanlar SalesForce sisteminde teklif belgesi üzerine eklenecektir. SAP sistemine teklif belgesi olarak aktarılacaktır.
(istenilen dökümanlar ; bayinin fırsatı sunduğu firmanın kaşesi (vergi numarası yazılı), adresi kaşe bulunmuyorsa vergi levhası, adi
ortaklık ise; iki ortağın vergi levhası ve ortaklık yazısı, müşterinin fırsatı hangi montaj adresine ve hangi tarihte istediğine dair adet ve
fiyat yazılı imzalı kaşeli kağıt)
Süreç Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Kurumsal kanal satışlarındaki süreçler iklimlendirme ile
aynıdır.

FM:
ZSD_FM_SALESDOCUMENT_Create

SF

INC: zsd_i_salesdoc_cre_sf

Job


<<< SAYFA 30 >>>
4.3.1.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/742707f9-b853-41f7-bfab-b3ca25b3a7a6/SPFID/df78832b-f30c-422f-875c-c3f36fb3a640/?tab=SPF

4.3.2. OTC-060-010-120 - Direkt kurumsal kanala yapılan satışlar
4.3.2.1.Sürece Genel Bakış
DMO, Proje ve Holding satışları bu kanal üzerinden gerçekleşecektir.

4.3.2.2.Süreç Adımları
Direkt Satış DMO satış süreçleri için sipariş akışı aşağıdaki gibi olacaktır:
-Salesforce sisteminde teklif belgesi oluşturulacaktır.
-SAP sistemine teklif belgeleri iletilecektir.
-Sonraki aşamalar bayi kanal süreci ile aynı olacaktır.
-Sevk adresleri ayrıca belirlenecektir.
-Fiyatlar manuel olarak değiştirilemeyecektir.
DMO klima satışları kurumsal kanal satış tarafında yürütülecektir.

Direkt Satış B2C kanalı satış süreçleri için sipariş akışı aşağıdaki gibi olacaktır :
-Ay başında ilgili müşterilerle fiyat paylaşımı yapılacaktır. Müşterilerden gelen bilgiye göre üretim planlaması yapılacaktır.
-Salesforce sisteminde teklif belgesi oluşturulacaktır.
-SAP sistemine teklif belgeleri iletilecektir.
-Sevkiyat işlemlerini başlatabilmek için yaratılamadığı durumda teklifin kesin satış siparişine dönüştürülmesi adımı job ya da manuel
gerçekleştirilmelidir.
Süreç Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Kurumsal kanal satışlarındaki süreçler iklimlendirme ile
aynıdır.

FM:
ZSD_FM_SALESDOCUMENT_Create

SF

INC: zsd_i_salesdoc_cre_sf

Job


<<< SAYFA 31 >>>
4.3.2.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/f828cdfa-9d76-4c87-ae7e-e8029af0cb92/SPFID/d82cc31e-50a7-4594-8a32-078e2417e958/?
tab=SPF

4.4. Alternatif Kanal Discount Market Satış
BİM, ŞOK, A101 discount marketlere yapılan satışlar bu başlık altında takip edilecektir.
Alternatif kanalların sipariş süreçlerinde A101, BİM vb. müşterilerden gelen siparişlerin sisteme alımı konusunda Mars'a müşterilerin
siparişi girişi veya entegrasyon ile SAP'ye aktarımları olacaktır. Bu süreçte Bayi yönetmenleri giriş yapması durumunda da Mars Portal
ekranlarından yapılacaktır.
Discount marketler için otomatik servis ataması SAP sisteminden yapılacaktır.
Discount market siparişlerinde tüketici teslim sipariş girişi yapılıp yapılmayacağı hedef grup bazında yönetilecektir.

4.4.1. OTC-060-010-130 - BİM Market Satış Süreçleri
4.4.1.1. Sürece Genel Bakış
BİM siparişleri SAP sistemine entegrasyon ile gelecektir.
Entegrasyon ile Mars veya VSRM den gelecektir.

4.4.1.2. Süreç Adımları
Kasiyer tarafından sipariş BIM uygulamasından girilecek. BİM’in kendi uygulaması ile entegrasyon sağlanacaktır.
Siparişler entegrasyon ile SAP sistemine gelecektir.

4.4.1.3. Süreç Akışları


<<< SAYFA 32 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/c08a9b6c-c17f-45cb-ad4f-7c0a5c50c82f/SPFID/e1c6d766-5620-4428-9342-75c5b4c92604/?tab=SPF

4.4.2. OTC-060-010-140 - ŞOK Market Satış Süreçleri
4.4.2.1. Sürece Genel Bakış
ŞOK siparişleri SAP sistemine entegrasyon ile gelecektir.
Entegrasyon ile Mars veya VSRM den gelecektir.

4.4.2.2. Süreç Adımları
Kasiyer tarafından sipariş ŞOK uygulamasından girilecek. ŞOK'un kendi uygulaması ile entegrasyon sağlanacaktır.
Siparişler entegrasyon ile SAP sistemine gelecektir.

4.4.2.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/c1b49d5d-5a10-4ae7-9eda-93ae38fd991b/SPFID/3190d989-b468-4a95-8771-b5f0d404ac2a/?
tab=SPF

4.4.3. OTC-060-010-150 - A101 Market Satış Süreçleri


<<< SAYFA 33 >>>
4.4.3.1. Sürece Genel Bakış
A101 siparişleri SAP sistemine entegrasyon ile gelecektir. Sipariş akışı bayi kanalı ile aynıdır.

4.4.3.2. Süreç Adımları
A101market siparişleri bölge bazında toplanır ve Mars sistemi entegrasyonu ile SAP sistemine gelecektir.

4.4.3.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/1d66d7e8-b564-4bc3-8ea7-1253d6a17d0c/SPFID/0c07097d-f926-444c-b1f8-0b600e3eff00/?tab=SPF

4.5. Alternatif Kanal Su arıtma abonelik satış süreçleri
Su arıtma süreci Su arıtma kiralama şeklinde yönetilmektedir. İki farklı sistemden bu işlem gerçekleştirilecektir.
Müşteri anaverisi SAP üzerinde yok ise servis ile SAP'de müşteri oluşturulacaktır. Müşteri duplike kontrolü D2D kanalında TCKN ile
yapılacaktır. H20 için kontrolün nasıl yapıldığı entegrasyon toplantılarında netleştirilecektir..Müşteri oluştuktan sonra 24 aylık sözleşme
Sales Force ve H2O sistemlerinde oluşturulacaktır. Sipariş veren ile sevk adresi farklı ise arızi müşteri numarası içine adres bilgileri
girilecektir.
H2O fiyatları SAP üzerinde tanımlanmakta ve servis ile suaritma.arcelik.com.tr web sitesine gönderilecektir.
D2D fiyatları SAP üzerinde tanımlanmaktadır. Ancak başka bir sisteme gönderilmiyor.
Su artıma cihazı tek bir ürün kodundan oluşmaktadır.

4.5.1. OTC-060-010-160 - H2O Satış Süreçleri
4.5.1.1. Sürece Genel Bakış
H2O sistemi ile entegrasyon mevcuttaki gibi sağlanacaktır.

4.5.1.2. Süreç Adımları
H2O satış sürecinde; arcelik.com.tr den abonelik sayfasına yönlendirme ile veya suaritma.arcelik.com.tr altında ayrı bir platformdan
satış yapılacaktır. Sözleşmeler müşteriler tarafından oluşturulacaktır.
H2O'daki sözleşme numarası SAP'de sipariş içerisinde SAS No alanında tutulacaktır. SAS tarihi alanında deneme başlangıç tarihi takip
edilecektir.


<<< SAYFA 34 >>>
H2O'da montaj kaydı kapatıldıktan sonra 14 günlük deneme süresi verilecek.
Deneme süresinden sonra her ay faturalanacak tutar SAP sistemine servis ile Borç Dekontu oluşturulacak.
Dekonta ait fatura H2O sisteminden servis ile SAP'e yansıtılacak.
Fiyat yönetimi:
Fiyatlar SAP üzerinden girilir.
Girilen fiyatları H2O sistemi kendi portalinde kullanmak üzere SAP'den sorgular.
Müşteri bazlı olarak bir fiyat bilgisini H2O portali üzerinde tutar.
Müşterinin faturası kesileceği dönem, siparişin içindeki fiyat bilgisini H2O gönderir.
H2O sistemlerinden ödeme alındığında SAP üzerinde de servis ile ödeme belgesi oluşturulacak.

Satış siparişi içerisinde bir tane ana kalem bulunur.
Su arıtma ürünü (stoksuz - hizmet)
Üyelik bedeli
- (ECC'de kalem iken S4'da fiyat koşulu olarak tanımlandı.)
Fatura kargo bedeli - (ECC'de kalem iken S4'da fiyat koşulu olarak tanımlandı.)
Hasar bedeli
- (ECC'de kalem iken S4'da fiyat koşulu olarak tanımlandı.)
Demontaj bedeli
- (ECC'de kalem iken S4'da fiyat koşulu olarak tanımlandı.)

Süreç Adım No

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak Sistem

1

BP yaratma aşaması

ZBP_FM_BP_MAINTAIN

H2O

2

Sipariş yaratma

ZSD_FM_SALESDOCUMENT_CREATE

H2O

3

Fatura yaratma

4

Tahsilat fonksiyonu

4.5.1.3. Süreç Akışları

ZFI_FM_H2O_POSTING

Job


<<< SAYFA 35 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/142eaab8-83c7-4352-952a-f85ce8c5e58c/SPFID/8e461a65-84d2-4384-8193-6700db33976e/?
tab=SPF

4.5.2. OTC-060-010-170 - D2D Satış Süreçleri
4.5.2.1. Sürece Genel Bakış
D2D sistemi ile entegrasyon mevcuttaki gibi sağlanacaktır.
DV satışı yapılmayacak kararı alındı.

4.5.2.2. Süreç Adımları
Sales Force sistemi üzerinden entegrasyon hizmet danışmanlarının BP Yaratılmasını tetiklemesiyle başlayacaktır.
BP'si yaratılan müşterinin, kurulum istediği senaryoda SAP'ye sipariş yaratılması da entegrasyon ile devam edecektir.
Sipariş yaratılırken;
1 adetlik bir ürün olarak yaratılarak SAP'ye gönderilir.
Salesforce sözleşme numarası Müşteri referansı alanına yazılır.
Sas türü : A210
Sipariş türü : ZPR1
Sipariş veren her zaman caridir.
Malı teslim alan her zaman ARIZI müşteridir.
Salesforce'un gönderdiği sözleşme bilgilerine göre, fiyat SAP üzerinden belirlenir.
12+12 şeklinde bir fiyatlandırma yönetimi var. (Örn: ilk 12 ay 100 tl, ikinci 12 ay 150 tl)
ZKR0 istatistiksel olarak belirlendi. ZNTT fiyatın yürüdüğü ana koşul.
13. ayda ZKR0*ZKA1 + ZDFF yapılarak ZNTT belirlenir.


<<< SAYFA 36 >>>
Sipariş yaratılması bittikten sonra süreç tamamen SAP üzerinden, kokpit ekranları üzerinden devam eder.
Süreç kokpiti: ZSD_0014
Stok kokpiti: ZMM_0078

Teslimat yaratma butonu = süreçteki siparişin teslimatını yaratır.
MÇ ve Ekipman Güncelle = Seri numarası girilmiş teslimatın kontrollerini yapar.
Eğer ürün sıfırsa
; Tahditsiz stoktan 1 adet tüketip, Satış siparişine 1 adet giriş yapar. 411-E ve seri numarasının
arkasında yaratılmış ekipmanın statüsünü günceller
Eğer ürün reworklü ürün ise; İlgili seri numarasının arkasında yaratılmış ekipmanın statüsünü günceller. Ekstra bir mal hareketi
vb yoktur.


<<< SAYFA 37 >>>
Yazdır butonu
Faturalama planı başlat&DV Yarat/İşle
Eğer ürün sıfırsa
:
Satış siparişindeki stoğu tahditsize geri alır (413-e). Hemen arkasında tahditsizden 1 adet tüketip, duran varlık kartı
yaratan mal hareketini yapar. (241).
Mal hareketleri bittikten sonra siparişin üzerindeki faturalama blokajını kaldırır
Faturalama planı başlangıç ve bitiş tarihini seçtirir.
Eğer ürün reworklü ise :
Herhangi bir mal hareketi yapmaz. Statü günceller.
Mal hareketleri bittikten sonra siparişin üzerindeki faturalama blokajını kaldırır
Faturalama planı başlangıç ve bitiş tarihini seçtirir.
Faturalama Planı detayları: Seçilen satırların kesilmiş tüm faturalarını gösterir.
Ekipman/Seri/DV = İlgili satırlardaki seri numaralarının ekipman-seri-dv kart ilişkisini gösterir.
Seri no atama: Terminaldeki okutmanın muadili. Kriz anında kullanılabilir.
Ekipman güncelle: Ekipman güncellenmek istenirse kullanılır.
İade süreci başlat: Seçili siparişin, iade siparişini oluşturur.
Faturalama : VF04 ekranını seçili siparişlerle çağırır.

Hizmet danışmanları S4/HANA üzerinde müşteri olarak açılacak ve su arıtma siparişleri içerisinde muhatap olarak takip edilecek.
Hizmet danışmanları için bir prim hesaplamasında bu bilgi kullanılacaktır. Son müşteri için prim hesaplaması yapılmayacaktır.

Süreç Adım No

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak Sistem

1

BP yaratma

ZBP_FM_BP_MAINTAIN

D2D

2

Sipariş yaratma

ZSD_FM_D2D_ORDER

D2D

4.5.2.3. Süreç Akışları

Job


<<< SAYFA 38 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/298700d3-b282-4573-8c75-2f99bf18f42d/SPFID/e1d2a28c-1da8-4678-90eb-399c89f02a92/?
tab=SPF

4.6. Perakende Kanallar Satış Süreçleri
4.6.1. OTC-060-010-180 - OLIZ Satış Süreci
4.6.1.1. Sürece Genel Bakış
Oliz'den ürün satılmayacaktır. Oliz'den yapılan satışlar stoksuz hizmet satışlarıdır. Ek garanti, Oliz Plus(üyelik uygulaması) satışı
yapılmaktadır.

4.6.1.2. Süreç Adımları
Oliz'den yapılan ek garanti ve Oliz Plus satışları Hybris sistemine gönderilecektir. Hybris sisteminde oluşan sipariş SAP sistemine
entegrasyon ile gönderilecektir.
Oliz üzerinden kayıt olan tüm üyeler Hybris tarafında tutulmuyor. Mevcut yapıda yalnızca sipariş oluşturup müşteri kaydı olanlar
tutuluyor. Bu şekilde entegrasyon devam edecek. Bu siparişler arızi müşteriler üzerinden yaratılacak. Üyelik satışı için ayrı bir arızi
müşteri, ek garanti satışı için ayrı bir arızi müşteri numarası kullanılacaktır.
Oliz üzerinden Arçelik ürün ve hizmetlerini satın alan kullanıcılar SAP S4/HANA sisteminde müşteri olarak oluşturulacaktır.
Satış faturaları manuel veya haftanın belli günlerde job ile otomatik oluşturulacaktır.
Ek garanti satışları KDV dahil tavsiye edilen satış fiyatı olarak satılacaktır.
Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu /
Fonksiyon Adı

Entegrasyon
Kaynak Sistem

Job

Hybris üzerinden OLIZ entegrasyonu S4 ile sağlanacaktır.

ZSD_FM_SALESDOCUME
NT_CREATE

S4

Hybris
tetikliyor.

Sipariş türü: ZS07
Kalem tipi : ZS04-Hizmet kalemi
2

Arızi müşteri kod ile sipariş oluşturulacak.

3

Ek garanti satışlarında, hangi ürün için ek garanti satıldığı bilgisi Müşteri Malzeme Numarası alanında tutulacaktır.

4

Web sipariş-Hybris kanalından açılan siparişler ile aynı hesaplama şeması
kullanılacak.

5

Kesilen satış faturası muhasebeblokajlı oluşacakvemuhasebe tarafından
VFX3 ten release edilecek.

4.6.1.3. Süreç Akışları


<<< SAYFA 39 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/f581ba36-2bc5-4284-9912-a859b3334258/SPFID/fb343a88-4adc-4aab-8ba7-94db851a05cf/?
tab=SPF

4.6.2. OTC-060-010-190 - Marketplace Satış Süreci
4.6.2.1. Sürece Genel Bakış
Marketplace satış Süreçleri için COSMOS sistemi ile entegrasyon yapılacaktır.

4.6.2.2. Süreç Adımları
Malzemeler ilgili marketplacelere Ayensoft üzerinden gönderilmektedir. SAP sisteminden gelen fiyat ve marketplace satışa açık bilgisi
Ayensoft paneli üzerinden de değiştirilebilecektir.
Ayensoft marketplacelerden periyodik olarak siparişleri toplayacak, oluşan siparişleri databaseine alacak. Siparişlerdeki her bir kalem
ayrı bir sipariş olarak oluşacak ve COSMOS sistemine gönderilecek. Siparişler COSMOS sisteminden SAP sistemine aktarılacaktır.
Marketplace satışlarında Arçelik Pazarlama depolarındaki stok kullanılacaktır. Marketplace satışları arizi müşteri numarası ile siparişler
alınır.
Süreç
Adım
No

1

Süreç Adımı

İşlem
Kodu /
Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Cosmos sistemi fiyat entegrasyonu

ZSD_FM_GE S4
T_PRICE_LIST

ZX02 koşul türü göndeirliyor.
KDV dahil, hari fiyatlar da gönderiliyor.
2

COSMOS sistemi sipariş entegrasyonu
601P-MP satışkanalından sipariş alınmaktadır.

3

Siparişler Arızi müşteri kodundan yaratılmaktadır.

4

Her bir sipariş birkalemden oluşmaktadır.

ZSD_FM_SA
LESDOCUME
NT_CREATE

S4


<<< SAYFA 40 >>>
5

Marketplace Kargo takipnumarası metin alanında tutulmaktadır.

6

Sipariş içerisinde montajlı ürün var ise yetkili servis ataması S4 tarafından değil sipariş S4 a
gönderilemden önce COSMOS tarafından yapılıyor. COSMOS S4'a siparişi iletirken Z3 muhatabı ile
iletiyor. Eğer momtajlıürün değilse siparişler kargo ile gönderiliyor.Kargo entegrasyonu da COSMOS
tarafından sağlanıyor. S4 'a ZK muhatabı ile iletiliyor.

7

S4 tarafında sipariş sevk adımları tamamlanıp e-irsaliye düzenledikten sonra Cosmos sistemine IDOC
aracılığı ile e-irsaliye bilgileri gönderiliyor ve Cosmos tarafında siparişin statüsü bu bilgi ile güncelleniyor.

IDOC:
DELVRY03
/DESADV

8

S4 tarafındasatış faturası düzenlenip e-fatura GİB e gönderim gerçekleştikten sonra Cosmos sistemine
IDOC aracılığı ile e-fatura bilgileri gönderiliyor ve Cosmos tarafında siparişin statüsü bu bilgi ile
güncelleniyor.

IDOC :
INVOIC02
/INVOIC

4.6.2.3. Süreç Akışları


<<< SAYFA 41 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/a44e1845-33d9-4a25-9010-be1a866ab5cf/SPFID/e3be1b5e-f0b5-4870-9d25-286a1c8b5d24/?
tab=SPF

4.6.3. OTC-060-010-200 - Web Satış Süreci
4.6.3.1. Sürece Genel Bakış
arcelik.com.tr, beko.com.tr, grundig.com.tr web sitelerinden ve çağrı merkezinden alınan sipariş sürecidir.

4.6.3.2. Süreç Adımları
Müşteri, web sitelerinden üye olduğunda Hybris sisteminde müşteri kodu yaratılacaktır.
Müşteri arcelik.com.tr, beko.com.tr, grundig.com.tr web sitelerinden sipariş oluşturacaktır. Çağrı merkezinden SMS le alınan siparişler
de bu kanaldan gelecektir.
Web sitesinde satışı yapılan ürünler SAP ECC sisteminden PCM katologlarına sonrasında da Hybris sistemine akmaktadır. Web sitesinde
satışı yapılan yedek parçalar SAP sisteminden doğrudan Hybris sistemine akmaktadır. Ürün DC(Distribution center) depolarında var ise
online siparişe açık olarak belirlenecektir.
Ürünler sepete eklendikten sonra Oliz, koç ailem no, indirim kodu, ve CRM(size özel) gibi indirim kodları Tanı sisteminde tanımlanarak
kullanılabilecektir. Free gift ve Bundle kampanyaları Hybris sisteminde tanımlanacaktır.
Teslimat yöntemleri, mağazadan teslim ve ya adrese teslim olabilecektir.
Web sitelerimizde Sepete Ekle butonunun aktif olabilmesi için Arçelik'in kendi depolarında ilgili SKU'dan en az 2 adet stok bulunmalıdır
(bayi stoklarından bağımsız olarak).
Teslimat yöntemleri, mağazadan teslim ve ya adrese teslim olabilecektir.
Mağazadan teslim seçeneğinde yalnızca montajsız ürünler için ilgili bayide stok bulunması durumunda müşteri seçtiği bayiden ürünü
teslim alabilecektir.
Adrese teslim yönteminde direkt müşteri adresine teslim ve "hızlı teslimat" olmak üzere iki farklı teslimat seçeneği bulunmaktadır.
Müşteri "hızlı teslimat" seçeneğiyle (OSAS tan seçilen bayiye atanması ile) adresine en yakın lokasyondaki bayiyi seçer ve seçili bayi
ürünü müşteriye teslim eder. Sepette montajlı ürün varsa yalnızca adrese teslim seçeneği aktif olacaktır, mağazadan teslim seçeneği
aktif olmaz.

Web sitelerinden siparişler öncelikli olarak bayilere yönlendirilerek satışının bayiler üzerinden yapılması sağlanmaya çalışılacaktır. Bu
yönlendirme Hybris sistemindeki OSAS(Online Sipariş Atama Sistemi) üzerinden otomatik olarak yapılacaktır. 2025 itibarıyla atama
algoritmasının yönetimi COSMOS altyapısı üzerinden yapılacaktır.
OSAS sisteminde yönlendirilen siparişi bayi kabul eder ise;
Sipariş SAP sisteminde SD sipariş kaydı oluşturmayacaktır .Direkt olarak bayinin Rapid sisteminde bir siparişi olarak oluşturulacak ve
faturayı bayi kesecektir. (Mevcutta ödeme Arçelik tarafında alınır ve bankanın belirttiği vade tarihinde bayiye ödeme yapılır.)
OSAS sisteminde yönlendirilen siparişi bayi kabul etmez ise;


<<< SAYFA 42 >>>
Sipariş SAP sistemine gelecektir. Ürün siparişleri için DC depolardan sevkiyat sağlanacak ve müşteriye SAP sisteminden fatura
kesilecektir.
Web siparişlerinde sepet oluşturulurken Hybris sisteminde sepet numarası oluşur. Sipariş kaydedildiğinde bir sipariş numarası oluşur ve
bu bilgi SAP sisteminde sipariş üzerinde bir alanda tutulacaktır. Ödeme yöntemleri olarak kredi kartı(masterpass-garanti pay
entegrasyonları), havale/eft, alışveriş kredisi, hediye çeki kullanılabilir. Ödeme alınmadan sipariş oluşmayacaktır.
Süreç
Adım
No

1

Süreç Adımı

İşlem
Kodu /
Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Hybris sistemi fiyat entegrasyonu

ZSD_FM_GE S4
T_PRICE_LIST

ZX02 koşul türü göndeirliyor.
KDV dahil, hari fiyatlar da gönderiliyor.
2

Hybris sistemi sipariş entegrasyonu
601P-WK satışkanalından sipariş alınmaktadır.

3

Siparişler Arızi müşteri kodundan yaratılmaktadır.

4

Her bir sipariş birkalemden oluşmaktadır.

5

OSAS sisteminde yönlendirilen siparişi bayi kabul etmez ise;

ZSD_FM_SA
LESDOCUME
NT_CREATE

Sipariş SAP sistemine gelecektir. Ürün siparişleri için DC depolardan sevkiyat sağlanacak ve müşteriye
SAP sisteminden fatura kesilecektir.
6

Sipariş içerisinde montajlı ürün var ise yetkili servis ataması S4 tarafından değil sipariş S4 a
gönderilemden önce Hybris tarafından yapılıyor. Hybris S4'a siparişi iletirken Z3 muhatabı ile iletiyor.
Eğer momtajlıürün değilse siparişler kargo ile gönderiliyor.Kargo entegrasyonu da Hybris tarafından
sağlanıyor. S4 'a ZK muhatabı ile iletiliyor.

7

S4 tarafında sipariş sevk adımları tamamlanıp e-irsaliye düzenledikten sonra Hybris sistemine IDOC
aracılığı ile e-irsaliye bilgileri gönderiliyor ve Hybris tarafında siparişin statüsü bu bilgi ile güncelleniyor.

IDOC:
DELVRY03
/DESADV

8

S4 tarafındasatış faturası düzenlenip e-fatura GİB e gönderim gerçekleştikten sonra Hybris sistemine
IDOC aracılığı ile e-fatura bilgileri gönderiliyor ve Hybris tarafında siparişin statüsü bu bilgi ile
güncelleniyor.

IDOC :
INVOIC02
/INVOIC

4.6.3.3. Süreç Akışları

S4


<<< SAYFA 43 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/af83dd61-5e92-4c50-bfcb-40979215e635/SPFID/cf129bba-5d8e-4dd7-add2-c1384656519f/?tab=SPF

4.6.4. OTC-060-010-210 - Arçelik Mağaza Satış Süreci
4.6.4.1. Sürece Genel Bakış
Arçelik Pazarlama’nın kendi Mağazalarından yapılan satışlar bu kanalda takip edilecektir.

4.6.4.2. Süreç Adımları
Arçelik Pazarlama bünyesinde 2 adet mağaza vardır. Kadıköy ve Yenibosna mağazaları Arçelik Pazarlama’ya aittir.
4 farklı satış yöntemi vardır. Siparişler Rapid360 sistemi üzerinden alınır, mağaza çalışanlarının tetiklemesi ile entegrasyon aracılığıyla
SAP sistemine gönderilir.
Hızlı Satış : Mağaza depolarından(6068 ve 6502 SAP depo kodundan) yapılan satışlar. Müşteri mağazadan talep ettiği ürünü alır
ve sevkkiyat işlemleri Arçelik tarafından yürütülmez.
Depodan sevkiyat : Genelde montajlı ürünlerin satışı olup, mağazada ürün bulunmaması veya müşteri talebiyle montajsız
ürünler de depodan sevk edilebilmektedir. Rapid360 sistemi üzerinden alınan sipariş, mağaza çalışanlarının tetiklemesi ile
entegrasyon aracılığıyla SAP sistemine gönderilir.
Emanet Satış : Ürünler satın alındıktan sonra belli bir süre depoda emanette bırakılması sonrasında sevkedilmesi sürecidir. Bu
ürünler için sistemdeki “emanet süreci” işletilecektir. Emanetteki ürünün sevkiyat süreci Rapid360 sistemi üzerinden
yürütülecektir
Flextra Satış: Diğer koç grubu şirketlerinde çalışan personele yapılan satışlardır. Yılda bir kere yapılır.
Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu /
Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Sipariş Rapidden tetiklenir

ZSD_FM_SALES
DOCUMENT_Cre
ate

Rapid

zsd_i_salesdoc_
cre_rapid_01
2

Mağaza depodan çıkışlı ise sipariş-teslimat-mal çıkışı ve fatura otomatik oluşur.

3

Fiyatlar Rapidden gönderilir. KDV dahil fiyat tetiklenir.

4

Her 2 mağaza için de 2 arızi müşteri koduyla siparişler oluşur.

5

Ürün ağaçı satışı vardır. Dış ve iç ünite için ayrı ayrı fiyat girilir. Diğer entegrasyonlardan
farklı olarak üst kalem ve alt kalem birlikte gönderilir. Yani sadece dış ünite gönderilmez. İç
ve dış ünite birlikte gönderilir.

6

İade siparişleri de Rapid'den tetiklenir.

Rapid

Job


<<< SAYFA 44 >>>
7

Sadece servis bilgisini değişiklik olarak gönderirler.

ZSD_FM_SALES
DOCUMENT_CH
ANGE

Rapid

zsd_i_salesdoc_
chng_rapid_01
8

Emanet siparişleri de Rapid'den tetiklenir.

9

Montajlı ürünse montaj ataması Rapid'de(servis bilgisi Rapid'den geliyor) yapılır.

10

ÖKC gibi ürünlerin satışında seri no Rapid'den gönderilir.

Rapid

Rapid

Mağaza Yapı Kredi ÖKC Sipariş Rapid'den tetiklenmektedir.

4.6.4.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/daf1be6c-2990-4cc7-8a11-854d5d837bd1/SPFID/afdf6a17-b892-47af-ba13-803807cce32f/?tab=SPF

4.7. Müşteri Hizmetleri Yedek Parça Satış
4.7.1. OTC-060-010-220 - Web Tamamlayıcı ürün- Aksesuar Satış Süreci
4.7.1.1. Sürece Genel Bakış
Web üzerinden Yedek parça satış sürecidir. OTC-060-010-200 başlığı altındaki iş akışı ile birebir aynıdır.

4.7.1.2. Süreç Adımları
-Satış verileri Hybris sisteminden gelecektir.
-Üretim yeri bilgisi Hybris tarafından 601S olarak gönderilecektir.
-Yedek parça fiyatları S/4HANA tarafında fiyatlandırma kokpitinden tanımlanacaktır. Bu fiyat ilgili kanallara gönderilecektir. Sipariş
oluşturma esnasında servisten fiyat bilgisi gönderilecektir.
-Müşteri için kanal bazlı 3 arizi müşteri (arcelik.com / beko.com / oliz ) vardır. Arizi müşteri kodu altında adres verileri gelecektir.
-Ödeme web üzerinde alındıktan sonra bu bilgi S/4HANA sistemine gönderilir ve sipariş yaratılır.
-Sipariş belgesinde otomatik depo yeri belirlemesi yapılacaktır.
-Siparişler SAP sistemine geldikten sonra teslimat belgeleri VL10C işlem koduna kurulacak job ile otomatik yaratılacaktır.


<<< SAYFA 45 >>>
-Web'de oluşturulan sepet içindeki kalem/miktar adedi kadar SAP sisteminde sipariş yaratılır. Teslimat yaratılırken adrese göre
birleştirme yapılır. AS-IS'de faturalama her bir kalem için ayrı ayrı yapılır. TO-BE'de fatura birleştirme yapılacaktır.
-Fatura birleştirme Hybris sisteminden gelen Hybris sipariş numara ve consignment numarası (depo yerine göre verilen bir numara) ve
sevkiyat noktası bazında uygun bir şekilde yapılacaktır.

Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu /
Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Job

Hybris sistemi fiyat entegrasyonu

ZSD_FM_GET_P
RICE_LIST

HYBRIS

Hybri
s
tetikli
yor.

ZSD_FM_SALES
DOCUMENT_CR
EATE

HYBRIS

Hybri
s
tetikli
yor.

ZX02 koşul türü gönderiliyor.
KDV dahil, hariç fiyatlar da gönderiliyor.
2

Hybris sistemi sipariş entegrasyonu
601P-WK satış kanalı, 601S üretim yerinden sipariş alınmaktadır.

3

Siparişler arızi müşteri kodundan yaratılmaktadır.

4

Her bir sipariş bir kalemden oluşmaktadır.

7

S4 tarafında sipariş sevk adımları tamamlanıp e-irsaliye düzenledikten sonra Hybris
sistemine IDOC aracılığı ile e-irsaliye bilgileri gönderiliyor ve Hybris tarafında siparişin
statüsü bu bilgi ile güncelleniyor.

IDOC:
DELVRY03
/DESADV

8

S4 tarafında satış faturası düzenlenip e-fatura GİB'e gönderim gerçekleştikten sonra Hybris
sistemine IDOC aracılığı ile e-fatura bilgileri gönderiliyor ve Hybris tarafında siparişin statüsü
bu bilgi ile güncelleniyor.

IDOC :
INVOIC02
/INVOIC

4.7.1.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/836fe876-8ef1-4a3e-bf4f-b28d15348855/SPFID/30bf343f-646b-4bfa-80b6-af9e44449d51/?tab=SPF

4.7.2. OTC-060-010-230 - Yetkili Servis Yedek Parça Satış Süreci
4.7.2.1. Sürece Genel Bakış
Yetkili servisler tarafından OASIS sisteminde yaratılan sipariş sürecidir.

4.7.2.2. Süreç Adımları
-SARIS platformunda yetkili servisler tarafından siparişler yaratılacaktır.


<<< SAYFA 46 >>>
-Müşteri, malzeme ve fiyat ana verileri SAP'den SARIS'e gönderilecektir.
-Entegrasyonla OASIS sisteminde oluşturulan siparişler SAP sistemine alınacaktır. Belge türü ZYİS'tir.
-Siparişte otomatik depo yeri belirlemesi yapılacaktır.
-Bölge ve merkez depolardan sipariş stokları karşılanmaktadır. Bölge deposunda stok yoksa stoğun merkez depodan karşılanması için
stok aktarım jobları çalışır. Bu stok aktarımı için SAP sisteminde mevcut yapı kullanılacaktır.
-Ürünlerin fiyatları ve servis iskontoları S/4HANA sisteminde kullanıcı tarafından manuel tanımlanacaktır. Bu fiyatlar SARIS'e
entegrasyonla gönderilecektir.
-Yedek parça satış siparişlerinde muhatap türü kontrolü merkez (tepe) cari kodu üzerinden yapılacaktır.
-Yedek parça teslimatlarında kargo teslimatı olduğu durumda EWM'siz depolarda gönderi numarası teslimatlarda bulunmayacaktır.

Süreç
Adım
No

Süreç Adımı

İşlem Kodu / Fonksiyon
Adı

Entegrasyon
Kaynak
Sistem

Job

1

PR00 fiyat koşul türü gönderiliyor.

ZSD_MONO

Manusoft

Sche
dule
Job

2

Belge türü: ZYİS

ZSD_FM_SALESDOCUMEN
T_CREATE (Entegrasyon
fonksiyonu)

SARIS

Saris
tetikli
yor.

SARIS

Saris
tetikli
yor.

Organizasyon: 601S-YS
Sipariş veren: Ana servis
Malı teslim alan: Ana/şube servis
Ödeyen: Merkez (tepe) muhatap

ZSD_0013 (Excel ile
sipariş oluşturma işlem
kodu)

Fatura alıcısı: Merkez (tepe) muhatap
Fiyat ve iskonto belgede otomatik belirleniyor.
Üretim yeri ana veriden otomatik belirleniyor. Depo yeri geliştirme aracılığıyla
üretim yerine göre otomatik belirleniyor.
3

Kredi blokajlı siparişler entegrasyon ile Artemis sistemine gönderilir. Bu sistemde
onaylanan siparişler için SAP'ye bilgi gönderilir ve siparişin kredi blokajı kaldırılır.

VA01 (Standart sipariş
oluşturma işlem kodu)

ZCR_FM_WS_MOBILE_AP
PROVE_LIST (Blokajlı
siparişlerin gönderildiği
entegrasyon fonksiyonu)

ZCR_FM_WS_MOBILE_AP
PROVE (Onaylanan
siparişlerin alındığı
entegrasyon fonksiyonu)
4

Belirli periyotlarla sipariş detayı, teslimat (EWM) ve fatura detayları sorgulanır.

ZSD_FM_EWM_STATUS_Q
UERY (Entegrasyon
fonksiyonu)

SARIS

Saris
tetikli
yor.

5

Belirli periyotlarla sipariş detayı, teslimat detayları sorgulanır. Yedek parça
teminsizliği kaynaklı ürün değişim algoritması için kullanılır.

ZSD_FM_SARIS_SALES_O
RDER_LIST

SARIS

Saris
tetikli
yor.

6

Belirli periyotlarla fatura detayları sorgulanır.

ZSD_FM_SATISCIRO

Saris
tetikli
yor.

ZSD_FM_WEBINVOICE_G
ETDETAIL
7
Merkez depoda (601S) stoğu bulunmayan malzemelerin bölge depolarda (6011(İstisna
6019) stoğu bulunması durumunda; sipariş güncelleme servisiyle kalemlerdeki
Süreçler) üretim yeri bilgisi güncellenir.

ZAATP_SPAREPARTAVAILA
BILITY - Stok Uygunluk
ZSD_RET_YP - Red
nedeni ekliyor satıra
ZSD_FM_SALESDOCUMEN
T_CREATE - Yedek Parça
Siparişi Oluşturma

SARIS

Saris
tetikli
yor.


<<< SAYFA 47 >>>
8
Temin edilemeyen ve muadili olan malzemeler için SARIS'teki muadil aktarma
(İstisna
kokpitinden kullanıcı ya da RPA aracılığıyla talimat girilir. Bu talimat sonrasında
Süreçler) SAP'deki temin edilemeyen malzemeye ait açık sipariş kalemlerine ret koyulur,
aynı bilgiler ve yeni (muadil) malzeme ile yeni sipariş oluşturulur.

9

Teslimat ve mal çıkışı yapılır.

10

Manuel faturalanır.

ZSD_RET_YP - Red
nedeni ekliyor satıra

SARIS

Saris
tetikli
yor.

ZSD_FM_SALESDOCUMEN
T_CREATE - Yedek Parça
Siparişi Oluşturma.
SAP
VF04

SAP

4.7.2.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-ui-app-id-hint=com.sap.calm.imp.pmge.
authoring&/SI/836fe876-8ef1-4a3e-bf4f-b28d15348855/SPFID/a82c38c8-cf06-4d13-9613-46e79567e807/?tab=SPF

4.7.3. OTC-060-010-240 - Personel Yedek Parça Satış Süreci
4.7.3.1. Sürece Genel Bakış
Personele yapılan yedek parça satış sürecidir.

4.7.3.2. Süreç Adımları
-Personel yedek parça satışı yapılırken manuel sipariş, teslimat ve faturalama yapılacaktır.
-EWM'li depodan sevkiyat yapılmayacaktır.
-Müşteri olarak arizi müşteri kullanılır. ( Mevcut kod: 1029)

Süreç
Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon
Adı

Belge türü: ZSPR
Organizasyon: 601S-YS

Entegrasyon
Kaynak Sistem

S/4HANA
VA01 (Standart sipariş
oluşturma işlem kodu)

Sipariş veren: 1029 arizi cari
Fiyat PR00 koşulu ile belgede otomatik belirleniyor.
Üretim yeri ana veriden otomatik belirleniyor. Depo yeri geliştirme
aracılığıyla üretim yerine göre otomatik belirleniyor.
2

Teslimat ve mal çıkışı

VL10C

S/4HANA

3

Faturalama yapılır.

VF04

S/4HANA

Job


<<< SAYFA 48 >>>
4.7.3.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/baeaa0d4-1e4b-4e2e-9fa6-6193e8aa9e96/SPFID/a3ae48a9-2f70-416d-bea1-a85480518aae/?
tab=SPF

4.7.4 OTC-060-010-250 - Müşteri Hizmetleri İhracat Amaçlı Yedek Parça Satış
4.7.4.1. Sürece Genel Bakış
Arçelik A.ş.' nin ihracat amacıyla Arçelik Pazarlama'dan yedek parça satın alması- Arçelik Pazarlama'nın yedek parça satışı sürecidir.

4.7.4.2. Süreç Adımları

1

ECC tarafında İhracat siparişi oluşması ve Ecc siparişine istinaden oluşan SAT- SAS işlemleri sonrasında ECC
Satınalma Siparişi sonrasında ECC Satınalma Sipariş Bilgileri IDOC ile s4H'a gönderilir.

ZSD_FM_IDOC
_INPUT_ORDE
RS_01

2

SAS a istinaden gelen veriler içinde ek olarak olarak ECC Satış Sipariş bilgileri muhatapları ve Sipariş no bilgisi
gelmektedir.

S
/4
HA
NA

3

Gelen Idoc bilgileri arasında s4H da

S
/4
HA
NA

ZYDS İhracat Satış Siparişi

ID
OC

Ecc
tetikl
iyor

ZBDZ Bedelsiz İhracat Satış siparişi
Olmak üzere iki farklı belge türü oluşumu yapılmaktadır. Bu bilgi yine IDOC üzerinden alınmaktadır.

4

Ecc sistemine kullanılabilir stok bilgileri görmeleri için ayrı bir RFC verilmiş durumda, sipariş geçmeden önce hangi
ürünlerde ne kadar stok var kontrol edilebilir.

ZAATP_SPAREP
ARTAVAILABILI
TY

RFC Ecc
tetikl
iyor


<<< SAYFA 49 >>>
5

IDOC içinde yer alan muhatap bilgilerinden hangileri s4H siparişinde kullanılacak bakım tablosu ile yönetilmektedir.

S
/4
HA
NA

Tablo özelliklerinde ECC muhatap türüne karşılık s4H da hangisi kullanılacak bu bilgiler ve Arizi kullanım mı olacak
normal müşterimi bu verilerin girişi ile beraber, arizi tiki olduğunda hangi arizi muhatap kullanılacak tabloda bakım
ile yönetilmektedir.

6

Sipariş türlerindeki farklılıklar ;
Gelen siparişlerde fiyatlar ECC den gelmektedir.

ZSD_FM_PURC
HASE_PRICE_E
CC

RFC Ecc
tetikl
iyor

Fakat bu veri öncesinde ECC ye s4H da yer alan stok maliyetleri RFC ile iletilmektedir.
Ecc ye verilen RFC ile ECC anlık olarak s4H stok maliyetlerini almaktadır.
Kural seti olarak
ZYDS: YD Yedek Parça Sip. siparişlerinde stok maliyeti * 0,56
ZBDZ: YD YS Bedelsiz Sip. siparişlerinde stok maliyeti * 0,02 olarak fiyatlanarak malzeme fiyatlarının bize bu
şekilde gelmesi beklenmektedir.
7

Siparişler oluştuktan sonra V_V2 programı çalışarak oluşan siparişlere teyit verildikten sonra ZID3 çıktı türü ile
teyit alan miktarlar ECC sistemine aktarılır.

ZID3

ID
OC

s4H
tetikl
iyor

8

Siparişlere ait teslimatlar oluşup EWM e aktarılır, EWM dönüşü sonrasında ZZVC Çıktı türü ile Teslimat mal çıkış
miktarları IDOC ile Ecc sistemine aktarılmaktadır.

ZZVC

ID
OC

s4H
tetikl
iyor

9

s4H da yer alan teslimatlar Ecc tarafından tetiklenerek fatura edilir.

ZSD_FM_INVO
ICE_CREATE

RFC Ecc
tetikl
iyor

ZSD_FM_ECC_
SALESORDER

RFC Ecc
tetikl
iyor

10 Süreç sonunda Ecc de oluşan SAS a istinaden s4H da oluşmuş sipariş teslimat fatura bilgilerini toplu olarak
raporlama amaçlı çekebilecekleri RFC s4H tarafından verilmiştir.

4.7.4.3. Süreç Akışları


<<< SAYFA 50 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-ui-app-id-hint=com.sap.calm.imp.pmge.
authoring&/SI/94a6cd1a-459e-4aa9-9185-d8a21f6f0b52/SPFID/6ca3fdb0-538d-4f4c-a7df-6baa7fe0a204/?tab=SPF

4.8. Servis İşçilik Satış Süreci
4.8.1. OTC-060-010-260 - Servis işçilik Satış Süreci
4.8.1.1. Sürece Genel Bakış
Servis işçilik faturalandırma adımlarının takip edildiği süreçtir.

4.8.1.2. Süreç Adımları
Aron ve Artemis sistemlerine servis tarafından işçilik verileri girilecektir.
Saris TH portal sisteminden mali işlem departmanı haftalık olarak fiş paketi oluşturulacak ve otomatik olarak SAP sistemine
aktarılacaktır.
SAP sistemine aktarılan verilerden alacak dekontu otomatik olarak istenilen kümulasyonlarla yaratılacaktır.
Servis işçilik bedelleri mevcut sistemde olduğu gibi FI belgesi ile yürütülecektir.

4.8.1.3. Süreç Akışları

4.9. Ek Garanti Satış Süreci
Bayi, yetkili servis ve çağrı merkezi satış kanallarından ek garanti satışı yapılacaktır.
Bayi & Yetkili satıcı
Yetkili servis
Oliz (4.6.1.2. süreç adımındaki gibi süreç ilerleyecektir.)
Çağrı merkezi (4.6.1.2. süreç adımındaki gibi süreç ilerleyecektir.)
Web (4.6.1.2. süreç adımındaki gibi süreç ilerleyecektir.)
Web'den yapılan ek garanti satışının süreç adımları Oliz'den yapılan ek garanti satışı ile aynı olacaktır. (4.6.1.2 başlığında
detaylandırılmıştır.)


<<< SAYFA 51 >>>
SD060010-30 Perakende Kanal - WEB Ek Garanti Sipariş Alım Süreci

Ek garanti satışları ürün ile birlikte yapılabilir ya da sadece ek garanti satışı (Oliz, web, çağrı merkezi) yapılabilecektir.
Ürün ile birlikte yapılan satışlar süreç olarak sıfır ürün için yapılan ek garantiler ve mevcut ürün için yapılan ek garantiler olarak ayrılır.
Sıfır ürün için alınan ek garanti için yeni montaj talebi (Ek garanti için ayrı bir iş emri açılmıyor. Montajlı ürün ile birlikte hareket ediyor)
açılır. Montaj talebi yetkili servise iletilir. Montaj talebi onaylandıktan sonra ek garanti aktif olur.
Oliz'de montajı yapılmış ürünün seri numarası ile eşleştirilerek ek garanti satışı yapılır.
Ek garanti malzemesi ürünle birlikte satıldığı durumda teslimat ve mal çıkış ilişkili olacaktır.
Ek garanti ürün dışında münferiden satıldığında teslimat ve mal çıkış ilişkisiz olacaktır.
Web ve Oliz kanalları, tüketici hizmetleri sistemi üzerinden ürün/ek garanti satış eşleştirme sorgusu yapabilecektir.
Mars sisteminden ürün ile birlikte veya sadece ek garanti satışı yapılmayacaktır.

4.9.1. OTC-060-010-270 - Bayi Ek Garanti Satış Süreci
4.9.1.1. Sürece Genel Bakış
Bayinin son müşteriye kestiği ek garanti satış sürecidir.

4.9.1.2. Süreç Adımları
Bayi, Rapid sisteminden ek garanti siparişi açar ve Saris sistemine iletilir. Saris sistemine iletilen siparişler otomatik olarak SAP
sistemine iletilir.
Ek garanti ürün kodları ECC'de bayi için farklılaştırılmış durumdadır. S/4HANA sistemi ile malzeme kodları ortaklaştırılacaktır.
Müşteri, malzeme ve fiyat ana verileri SAP'den SARIS'e gönderilecektir.

Süreç
Adım No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Job

Belge türü: ZSPG

ZSD_FM_SALESDOCUMENT_CREATE
(Entegrasyon fonksiyonu)

SARIS

Saris
tetikler.

VF04

S/4HANA

Organizasyon: 601A-BY / 601B-BY
Sipariş veren: Bayi kodu
Fiyat ZX01 koşulu ile belgede otomatik
belirleniyor.
Üretim yeri ana veriden otomatik
belirleniyor.
2

Job ile faturalama yapılır.


<<< SAYFA 52 >>>
4.9.1.3. Süreç Akışları
Aşağıdaki akış yeni satılan ürünlere ek garanti sürecini göstermektedir. Daha önce satılmış ve montajı yapılmış ürünlerin süreci proje
yönetimi tarafından netleştirilecektir.

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/a58e63cf-8566-44b6-ba49-7874801c5341/SPFID/0f6ab604-7afc-42dc-9fe4-43538cec1eaa/?tab=SPF

4.9.2. OTC-060-010-280 - Yetkili Servis / Çağrı Merkezi Ek Garanti Satış Süreci
4.9.2.1. Sürece Genel Bakış
Yetkili servis ve çağrı merkezi kanalları aracılığıyla müşteriye yapılan ek garanti satış sürecidir.

4.9.2.2. Süreç Adımları
Yetkili servisteki iş talebine istinaden (daha önce sevk edilen ve montaj kaydı olan ürünler) için ek garanti satışı yapılır. SARIS ile
entegrasyon olacaktır.
Müşteri hizmetleri sistemine sorgu yapılır ve yetkili servis tarafından müşteri üzerindeki kayıtlı olan ürünler seçildikten sonra ek garanti
satışı yapılır ve bu bilgi Saris sisteminden SAP sistemine gelir.
Ürün ile birlikte yapılan satışlar süreç olarak sıfır ürün için yapılan ek garantiler ve mevcut ürün için yapılan ek garantiler olarak ayrılır.
Sıfır ürün için alınan ek garanti için yeni montaj talebi açılır. Montaj talebi yetkili servise iletilir. Montaj talebi onaylandıktan sonra ek
garanti aktif olur.
Oliz'de montajı yapılmış ürünün seri numarası ile eşleştirilerek ek garanti satışı yapılır.
Ek garanti malzemesi ürünle birlikte satıldığı durumda teslimat ve mal çıkış ilişkili olacaktır.
Ek garanti ürün dışında münferiden satıldığında teslimat ve mal çıkış ilişkisiz olacaktır.
Her türlü ek garanti satışı ve iade için ek garantinin bağlı olduğu ürün kodu bulunacaktır.
Müşteri hizmetleri sisteminden SAP sistemine seri no bilgisi alınacaktır.
Müşteri, malzeme ve fiyat ana verileri SAP'den SARIS'e gönderilecektir.

Süreç
Adım No

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon
Kaynak Sistem

Job


<<< SAYFA 53 >>>
1

Belge türü: ZSPG

ZSD_FM_SALESDOCUMENT_CREATE
(Entegrasyon fonksiyonu)

SARIS

VF04

S/4HANA

Saris
tetikler.

Organizasyon: 601S-YS / 601S-CM
Sipariş veren: YS kanalı için servis kodu, CM kanalı
için 2013 arızi cari kodu
Fiyat PR00 koşulu ile belgede otomatik belirleniyor.
2

Job ile faturalama yapılır.

4.9.2.3. Süreç Akışları

https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/32ae733a-a504-44fc-be83-9fc080b89bef/SPFID/c3f32c9a-5106-4baa-a0a3-2ec1f935a52e/?tab=SPF

4.10. Dropshipment Satış Süreci
4.10.1. OTC-060-010-290 - Dropshipment Satış Süreci
4.10.1.1. Sürece Genel Bakış
Dropshipment siparişleri sadece arçelik.com.tr ve beko.com.tr üzerinden Hybris sistemine gelecektir. Dropshipment ürünleri Arçelik'in
anlaşmalı olduğu yetkili satıcılar üzerinden siparişi veren kişiye teslim edilir. Yetkili satıcı teslimatı gerçekleştirdikten sonra S4 daki
sipariş süreçleri başlar. Dropshipment ürünleri malzeme anaverisi üzerinde kalem tipi grubundan ayrıştırılır. Kalem tipi grubu : ZS02
olan ürünler tedarikçiler aracılığı ile teslima dresine gönderilir fakat sipariş Arçelik'e açıldığı için sanal olarak ürün Arçelik depolarına
satın alınır ve sanal olarak Arçelik depolarından çıkışı yapılarak müşteriye teslim gerçekleştirilir.

4.10.1.2. Süreç Adımları
-Hybris sistemine gelen siparişler tedarikçi portali olan Cosmos sistemine iletilecektir.
-Cosmos sisteminde tedarikçiler kendilerine düşen sipariş bilgilerini görebilecektir.
-Tedarikçiler ürünleri gönderdikten sonra Cosmos sistemi üzerinden mal çıkışı yapacaktır. Mal çıkışı statüsü, irsaliye no, irsaliye tarihi
ve seri numarası Cosmos sisteminden Hybris sistemine iletilecektir.
-Her bir kalem bir siparişe denk gelecektir.
-Sipariş bilgileri Hybris sisteminde SAP sistemine iletilecek ve SAP sisteminde aşağıdaki belgeler oluşacaktır:
Müşteriye satış siparişi (Mevcuttaki yapı gibi Hybris teki sipariş numarası SAP deki sipariş numarasının SAS alanında tutulacak)
Tedarikçiye satınalma siparişi (satınalma siparişindeki fiyat satınalma sözleşmesindeki fiyattan gelmektedir.)
Mal girişi işlemi (Satınalma siparişinde sanal depoya mal girişi yapılır.)


<<< SAYFA 54 >>>
Satış teslimat belgesi oluşturulacak ve mal çıkışı yapılacaktır.
Satış faturası oluşturulacaktır.
Müşteri web sitesi üzerinden iptal ya da iade işlemlerini yapabilmektedir.
Dropshipment sürecinde alacak/borç dekontu ve prim süreçleri olmayacaktır.
Dropshipment fiyatlandırma sürecinde ürünlerin perakende fiyatları SAP sisteminde toplu olarak tanımlanıp Hybris sistemine
gönderilecektir. Kampanyalar ve indirimler Hybris sistemi üzerinde yönetilecektir.
Süreç
Adım
No

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

1

Hybristen Dropshipment siparişi alınır.

Fonskiyon :
ZSD_FM_SALESDOCUMENT_CREATE

Satış siparişi arkasında tüm belgeler otomatik olarak bu include içerisinde oluşturulur.
Include:
zsd_i_salesdoc_cre_hybris_02
2

MM adımlarının yürütülebilmesi için ; ilgili tedarikçi ve ürün için sistemde satınalma sözleşmesi
tanımlanmalıdır.
Bir malzemenin birden fazla sözleşmesi olursa hata verilecektir.

3

Satış siparişi üzerinde VBKD-VSART=30 alanında dropshipment göstergesi takipedilmektedir.

4

İlgili tedarikçi bilgisi Muhatap bilgilerinde ZK muhatabında takip edilmektedir.


<<< SAYFA 55 >>>
5

Sipariş başlık metin alanlarında tedarikçiden alınan sipariş tarihi, e-irsalite bilgisi ve tarihi ve seri no
bilgisi takip edilmektedir.

6

Satış siparişinde 6600 depoyeri ,DROP sevk noktası ve ZS05 kalem tipi kullanılmaktadır.
ZS05 kalem tipi 3rd Party kalem tipidir. Bu kalem arkasında Satınalma Talebi otomatik oluşmaktadır.

7

Bu satınalma talebine referans ile CREATE fonksiyonu içerisinde satınalma siparişi oluşmaktadır.
Satınalma siparişi üzerinde, siipariş metinlerinde yer alan belge tarihi ve Dropshipment bilgisi yer
almaktadır.


<<< SAYFA 56 >>>
8

Satınalma siparişine istinaden mal giriş işlemi otomatik gerçekleştirilir.

9

Mal girişi ardından teslimat-mal çıkışı ve faturalama adımları da otomatik gerçekleştirilir.

10

Otomatik yaratılacak belgeler arasında hata alan belgeler Dropshipment Kokpitine düşer ve kkokpitte
hata görüntülebilir. Hata giderildikten sonra yine dropshipment kokpitinden belgeler ardarda yaratılsın
diye tetiklenir.

4.10.1.3. Süreç Akışları

İşlem kodu: ZSD_0024


<<< SAYFA 57 >>>
https://arcelik-a-s-cloudalm.eu10.alm.cloud.sap/launchpad#processAuthoring-display?sap-app-origin-hint=&sap-calm-apptimestamp=1730293067788&/SI/604827d6-eb86-4f56-8684-b80501c0fb85/SPFID/796b73a7-e5e5-4629-9005-12ebe23d3549/?
tab=SPF

4.11. Personele Satış Süreci
4.11.1. OTC-060-010-300 - Arçelik Pazarlama Personeline Satış Süreci
4.11.1.1. Sürece Genel Bakış
Arçelik Pazarlama A.Ş. ve Beko Global personeline yapılan satış işlemleri bu başlık altında takip edilecektir. Diğer iştirak şirketlerin
personellerine de bu entegrasyon ile sipariş alınabilecektir.

4.11.1.2. Süreç Adımları
Beko Global, Arçelik Pazarlama personelleri ve iştirakleri (WAT, WAT Mobilite, Token, Arçelik LG) kendi şirket personel koduyla personel
.arcelik.com.tr ve dukkan.arcelik.com.tr web sitelerinden siparişlerini oluşturmaktadırlar.
Beko Global ve Arçelik Pazarlama personellerinin satış süreçleri Arçelik Pazarlama şirketi altında SAP S/4 HANA sisteminden
yürütülecektir.
Sipariş stokları 601U depo yerinden karşılanır.
Fatura Arçelik Pazarlama tarafından nihai müşteriye kesilecektir. Arçelik Pazarlama personelleri S4 Hana sisteminde personel ana
verisi Business partner olarak yaratılacaktır. Diğer şirketlerin personelleri S4 Hana sisteminde BP olarak yaratılmayacak. Siparişler arızi
müşteri üzerinden takip edilecektir.
Montajlı ürün gönderimi pesonelin ev adresine montajsız ürünler ise personelin iş adresine gönderilecektir.
Sipariş üzerindeki muhataplar aşağıdaki gibi olacaktır.
Sipariş veren

Personel No / Arızi

Malı Teslim
alan

Adres bilgisi Gateway tarafından doldurulacak. Personel farklı adrese gönderebilir.

Kod: Personel No

Müşteri Servis kodu

Montajlı ürünler
için

Ödeyen
Yetkili Servis


<<< SAYFA 58 >>>
Lokasyon

Personelin firma içinde çalıştığı adres (LTR_3401 gibi..) (Sistemde Bp olarak bu lokasyonlar da
yaratılacaktır.

Montajsız ürünler
için

Personel Satışı Fiyatlandırma:
Personel fiyatlarının girişi için SAP S/4 sisteminde tasarlanacak olan fiyat giriş kokpitinden yapılacaktır dağıtım kanalı "personel satış"
bazında bazında yapılacaktır ve bu fiyatlar EMOS sistemine gönderilecektir. Fiyat giriş kokpitinin detayları OTC-075-010 Fiyat ve Koşul
Ana Veri Yönetimi dokümanında yer almaktadır.
Revizyonlu Ürün Satışı:
Beko Global şirketinde revizyonlu ürün satışı yapılmamaktadır. Beko Global'den şirketler arası satış süreciyle benzer bir yapıda olacak
şekilde (PTP - Ürün - Satınalma Yönetimi & Depo Yönetimi & Fatura Yönetimi) revizyonlu ürünler Arçelik Pazarlama A.Ş. mülkiyetine
alınır.
Revizyonlu ürünlerde alokasyon yapılmadığı için SAS belgesine ihtiyaç yoktur. Beko Global ECC sisteminde mal hareketi ile revizyonlu
ürünler müşteri konsinyesine alınacak ve bu bilgi S4 HANA sistemine gönderilecektir bunun için SAP ECC sisteminde geliştirme
yapılacaktır. Revizyonlu ürünler S/4 HANA sisteminden tetiklendikten sonra satıcı konsinyesine alınacaktır. Sürecin devamı şirketler
arası ürün satışında olduğu gibi devam edecektir.

Sipariş akışı aşağıdaki gibi olacaktır.
1- Dükkan üzerinden(EMOS) girilen siparişler Gateway arayüzünde işlenecek ve eksik bilgiler tamamlanacaktır.
2- Kredi kartlı - peşin satışlar için tahsilat bilgisi Gateway sisteminden S4 Hana sistemine mevcuttaki gibi aktarılacaktır.
3- Bordrodan kesinti yapılarak gerçekleşen siparişler için Gateway sistemi genel HCM sistemine kesinti bilgilerine iletecektir.
4- S4 sisteminde siparişler blokajlı olarak oluşur.
5- HR sisteminde kesinti kaydı yaratıldığı zaman (bordro çalıştığı zaman) Gateway sistemi S4 sisteminde satış siparişinin blokajını
kaldıracaktır.
6- Blokaj kaldırıldıktan sonra sevkiyat- faturalama işlemleri S4 sisteminde gerçekleşir.
7- Bordroya yansıtılan işlemler için faturalama işleminden sonra senkron olarak, eğer satış yapılan personel Arpaz personeli değilse
arızi müşteriyse ilgili şirketin sistemine fatura detay bilgilerin taksitler bazında iletilecektir.
8- İlgili şirketlerde bordro çalıştırılıp kesintiler yapıldıkça şirketler arası mutabakat yapıalcaktır. Bu detaylar RTR süreç dokümanlarında
detaylandırılacaktır.

Süreç
Adım
No

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

1

Gateway den S4 sistemine Personel satış siparişi entegrasyonu çalışır.

Fonskiyon :
ZSD_FM_SALESDOCUMENT_CREATE

Sipariş türü: ZS12
601P- PS kanalından satışlar takip edilmektedir.
2

Satış siparişleri teslimat blokajlı oluşturulur. Sipariş geçen personel Bordro dan ve ya kredi kartından
ödeme yaptığından bu ödeme alındı bilgisi gelene kadar sipariş teslimat blokajlıkalır ve sevk adımları
başlatılmaz.
Teslimat Blokajı : ZP

3

Ödeme tamamlandı bilgisi Gatewayden alındıktan sonra Sipariş güncelleme servisi ile S4 daki sipariş
üzerindeki teslimat blokajı kaldırılır.
Eğer ödeme alınmadıysa siparişe yine sipariş güncelleme servisi ile iptal bilgisi eklenir.

Fonskiyon :
ZSD_FM_SALESDOCUMENT_CHANGE


<<< SAYFA 59 >>>
4

Siparişin kredi kartı veya bordro ile ödendiği bilgisi ödeme biçimi alanından takip edilir.

5

Kredi kartına 5 taksit veya peşin ödeme ise ödeme koşulu alanından takip edilir.

6

Montajlı ürünler için yetkili servis atamasını Gateway SARIS entegraysonu ile siparişi S4 a göndermeden
önce sağlamaktadır. Siparişe Z3 muhatabı Gateway entegrasyonu ile gelmektedir.
Sipariş verilen ürün montajsız ise sipariş personelin iş yeri adresine gönderilir. Personelin iş yeri adresi
bilgisi ZL (personel location) alanından takip edilir.


<<< SAYFA 60 >>>
4.11.1.3. Süreç Akışları

4.12. İstisna Satış Süreci
4.12.1. OTC-060-010-310 - VIP Satış Süreci
4.12.1.1. Sürece Genel Bakış
VIP satış siparişi oluşturma işlemi, SAP S/4HANA üzerinde ilgili SD satış alanı ve sipariş türü kullanılarak manuel olarak gerçekleştirilir.
VIP Satış süreci genel olarak Koç Ailesi ve İKoç Holding iştiraklerine satışların gerçekleştirilmesi için tasarlanmıştır.
Bu süreçte kullanılacak satış organizasyon bilgisi
Satış Organizasyonu: 601P / Dağıtım Kanalı: VP / Bölüm: 01) olup,
Sipariş oluşturulurken belge türü olarak ZS11 seçilir.
Kullanıcı, komut alanına VA01 yazarak veya menü yolunu izleyerek manuel sipariş giriş ekranına ulaşır. Bu ekranda, belirlenen satış
alanına ait bilgiler sisteme girilir ve VIP satışlara özel sipariş türü olan ZS11 ile işlem başlatılır. Bu adım, siparişin doğru kategori altında
oluşturulması ve süreçte ilgili koşulların doğru çalışması açısından kritik önem taşır.

İlerleyen adımlarda, müşteri bilgileri, malzeme detayları, teslimat ve fiyatlandırma verileri girilerek sipariş oluşturma süreci
tamamlanacaktır.
Şekil 1’de ilgili ekran görüntüsü yer almaktadır ve sipariş giriş ekranının temel alanları gösterilmektedir. Veriler girildikten sonra enter
tuşuna basılarak sipariş giriş aşamasına geçilebilir.
Süreç
Adım
No

Süreç Adımı

İşlem
Kodu /
Fonksiyon
Adı

1

Siparişler Sap sistemi üzerinden manuel olarak açılmaktadır.

T-Code :
VA01

VIP satış siparişi oluşturma işlemi, SAP S/4HANA üzerinde ilgili SD satış alanı ve sipariş türü kullanılarak manuel olarak
gerçekleştirilir. Bu süreçte kullanılacak satış organizasyon bilgisi
Satış Organizasyonu: 601P / Dağıtım Kanalı: VP / Bölüm: 01) olup,
Sipariş oluşturulurken belge türü olarak ZS11 seçilir.

Entegrasyon
Kaynak
Sistem


<<< SAYFA 61 >>>
2

Sipariş veren ve malı teslim alan seçiminde, özellikle arizi muhatap kullanımıyla ilgili bilgiler doğru şekilde girilmelidir.
1150 / 1151 müşteri seçimi sonrası açılan popup ekranında adres, isim ve soyisim alanlarının eksiksiz ve doğru
doldurulması gerekir.
Arizi muhatap seçiminde bireysel ve kurumsal seçimine göre arizi muhatap no değişmektedir.
Faturalarda VKN ve TCKN için bu seçim kritiktir.
1150 : ÖZEL SATIŞLAR - BİREYSEL MÜŞTERİ
1151: ÖZEL SATIŞLAR - KURUMSAL MÜŞTERİ
Ayrıca, il, ilçe ve mahalle seçimlerinin doğruluğu siparişin teslimat sürecinde kritik önem taşımaktadır. Yanlış veya
eksik seçimler, siparişin hatalı sevkiyatına veya gecikmelere neden olabilir.
Vergi ile ilgili işlemler için VKN/TCKN bilgileri, özellikle eÇözümler entegrasyonları açısından zorunlu ve kritik bir
alandır. Bu nedenle bu alanların doğru ve eksiksiz şekilde girildiğinden emin olunmalıdır.
Arizi muhatap verileri doldurumu sırasında TCKN ve VKN girilmesi işlemleri unutulmamalıdır.
Sipariş kayıt sırasında İl İlçe Mahalle uyumsuzluğu olursa eFat gönderiminde problem yaşanmaktadır.


<<< SAYFA 62 >>>
3

VIP Satış sürecinde sitemde fiyat bilgisi olarak default ZX03 Personel fiyatı gelmektedir.
Süreç içerisinde farklı fiyat girilmesi talep edildiğinde ZMAN koşulu ile yeni bir fiyat girişi Manuel olarak yapılmaktadır.

4

VIP Satış sreüçlerinde aATP etkin değildir. Stokta ürün olduğu takdirde, sipariş giriş anında stok teyidi alıp teslimat ve
sevkiyat adımları ile süreç devam etmektedir.

4.12.1.2. Süreç Adımları
İstisna satış süreçleri Arpaz'ın Koç ailesine veya anlık olarak bir müşterisine göndermek üzere yaptığı satışlardır. Süreç içerisinde bir
entegrasyon, kontrol ve benzeri bir uygulama mevcut değildir. Sipariş S/4 HANA sisteminde standart sipariş, teslimat ve fatura
işlemleri ile tamamlanır.

4.12.1.3. Süreç Akışları

4.13. Müşteri Hizmetleri Hurda Satış Süreci
4.13.1. OTC-060-010-320 - Hurda Satış Süreci
4.13.1.1. Sürece Genel Bakış
MH tarafındaki hurda satış süreci bu başlık altında ele alınmıştır.

4.13.1.2. Süreç Adımları
Hurda siparişleri ZS18 belge türü ile takip edilecektir. Mevcutta finans tarafında fatura kesilmektedir. S4HANA ile birlikte hurda
siparişleri için de SD tarafından satış siparişi açılarak satış işlemi gerçekleşecektir.
Hurda siparişlerinde herhangi bir 3rd entegrasyon yoktur, Siparişler manuel VA01 üzerinden oluşturulacaktır.
İlgili müşteriye ilgili hurda malzemesinden satış siparişi açılacak. Hurda malzemesine KG bazında satış fiyatı belirlenecek. Bu fiyat
satınalma tarafından belirlenecek.


<<< SAYFA 63 >>>
Sipariş giriş aşamasında kritik tek nokta vardır,
Ana kalem Sipariş ilişkili faturalama ile faturalanacak,
Alt kalemler teslimat ilişkili olacak ve fatura edilmeyecek.
ilgili müşteriye teslimat arkasından mal çıkışı yapıldığında SMM çalışacak.
Bu işlemler manuel yürütülecektir.

4.13.1.3. Süreç Akışları

4.14. Müşteri hizmetleri Hizmet Satış Süreci
4.14.1. OTC-060-010-330 - ÖKC Devir Satış Süreci
4.14.1.1. Sürece Genel Bakış
ÖKC devir işlemi için yapılan hizmet satışı bu başlık altında takip edilecektir.

4.14.1.2. Süreç Adımları
Mevcutta tasarlanan yapıyla birebir aynı yapı tasarlanacaktır. SARIS sisteminden SAP sistemine entegrasyonla ÖKC devir siparişi
gönderilecektir. Stoksuz takip edilen malzeme kullanılacak ve teslimat ilişkisiz olacaktır. Sipariş arkasından fatura kesilerek süreç
tamamlanacak.

Süreç
Adım No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon
Kaynak Sistem

Job

Belge türü: ZOKC

ZSD_FM_SALESDOCUMENT_CREATE
(Entegrasyon fonksiyonu)

SARIS

Saris
tetikler.

VF04

S/4HANA

Organizasyon: 601S-YS
Sipariş veren: Servis kodu
Fiyat PR00 koşulu ile belgede otomatik
belirleniyor.
Üretim yeri entegrasyonda sabit 601S
olarak gönderiliyor.
2

Job ile fatura oluşturulur.

4.14.1.3. Süreç Akışları

4.14.2. OTC-060-010-340 - Bakım Satış Süreci
4.14.2.1. Sürece Genel Bakış
Müşteri ürününe yapılan bakım işlemlerinin satışı bu başlık altında takip edilecektir.

4.14.2.2. Süreç Adımları
Mevcutta tasarlanan yapıyla birebir aynı yapı tasarlanacaktır. SARIS sisteminden SAP sistemine entegrasyonla bakım siparişi
gönderilecektir. Stoksuz takip edilen malzeme kullanılacak ve teslimat ilişkisiz olacaktır. Sipariş arkasından fatura kesilerek süreç
tamamlanacak.

Süreç
Adım No

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Job


<<< SAYFA 64 >>>
1

Belge türü: ZSDS

ZSD_FM_SALESDOCUMENT_CREATE
(Entegrasyon fonksiyonu)

SARIS

VF04

S/4HANA

Saris
tetikler.

Organizasyon: 601S-YS
Sipariş veren: Servis kodu
Fiyat PR00 koşulu ile belgede otomatik
belirleniyor.
Üretim yeri müşteri ana verisinden
otomatik belirleniyor.
2

Job ile fatura oluşturulur.

4.14.1.3. Süreç Akışları

4.14. Yetkili Servis Konsinye Süreci
4.14.1. OTC-060-010-350 - Yetkili Servis Konsinye Süreci
4.14.1.1. Sürece Genel Bakış
Müşteri ürününün tamir sürecinin uzaması durumunda; mağduriyet yaşanmaması adına müşteriye geçici ürün temin edilmektedir. Bu
ürünler servislere konsinye süreciyle gönderilmektedir. Bu başlık altında konsinye stok ikmali, stok iadesi ve kayıp faturalaması
süreçleri yürütülecektir.

4.14.1.2. Süreç Adımları
1.Servislere stok ikmali için ZK01 türünde sipariş oluşturulur ve teslimat ile mal çıkışı yapılır. Bu işlem sonrasında tahditsiz stok
düşerek müşteri konsinye stoğuna transfer yapılır. Bu belge fatura ilişkisizdir.

Süreç Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Belge türü: ZK01

VA01 (Standart sipariş oluşturma işlem
kodu)

S/4HANA

Job

Organizasyon: 601S-YS
Sipariş veren: Servis kodu
Sipariş bedelsizdir.
Üretim yeri müşteri ana verisinden otomatik
belirleniyor.
2

Teslimat ve mal çıkışı

S/4HANA

2. Konsinyedeki stoklar ZK03 sipariş türü ile iade alınır. Bunun için ZK03 siparişi oluşturulur, ardından teslimat ve mal giriş işlemi
yapılır. Bu işlem sonrasında müşteri konsinyesindeki stok tahditsiz stoğa aktarılır. Bu belge fatura ilişkisizdir.

Süreç Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Belge türü: ZK03

VA01 (Standart sipariş oluşturma işlem
kodu)

S/4HANA

Organizasyon: 601S-YS
Sipariş veren: Servis kodu
Sipariş bedelsizdir.
Üretim yeri müşteri ana verisinden otomatik
belirleniyor.
2

Teslimat ve mal girişi

S/4HANA

Job


<<< SAYFA 65 >>>
3. Servisin ürünü kaybetmesi/zarar vermesi durumunda 2. adımdaki konsinye iade süreci yerine bu adımdaki konsinye faturalama
süreci yürütülür. Bunun için ZK02 siparişi oluşturulur, ardından teslimat, mal çıkışı ve faturalama adımları yürütülerek servis
borçlandırılır.

Süreç Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Belge türü: ZK02

VA01 (Standart sipariş oluşturma işlem
kodu)

S/4HANA

Job

Organizasyon: 601S-YS
Sipariş veren: Servis kodu
Fiyat ZMAN koşulu ile belgede manuel giriliyor.
Üretim yeri müşteri ana verisinden otomatik
belirleniyor.
2

Teslimat ve mal çıkışı

S/4HANA

3

Faturalama

S/4HANA

4.14.1.3. Süreç Akışları

4.15. Koç Grubu Satış Süreci
4.15.1. OTC-060-010-420 - Koç Grubu Satış Süreci
4.15.1.1. Sürece Genel Bakış
Koç grubu personeline yapılan satışlar Mağaza kanalıyla(601P-MG-01) yapılmaktadır. Bu satış süreci S/4 da VA01 den manuel
yönetilmektedir. Belge türü ZS01 dir. Fiyatlar elle girilmektedir. Her Koç Grubu şirketi için ayrı birer müşteri kodu oluşturulmaktadır.

4.15.1.2. Süreç Adımları

Süreç Adım
No
1

Süreç Adımı

İşlem Kodu / Fonksiyon Adı

Entegrasyon Kaynak
Sistem

Belge türü: ZS01

VA01 (Standart sipariş oluşturma
işlem kodu)

S/4HANA

Organizasyon: 601P-Mg
Sipariş veren: Koç Grubu Şirketi
2

Fiyat manuel elle girilmektedir.

3

Sipariş veren ve sevk adresi elle girilmektedir.

4

Emanete alınacaksa elle sipariş üzerindeki alan
doldurulacaktır.

5

Tüketici teslim alanı elle doldurulacaktır.

4.16. Ek Garanti Web Sipariş Süreci
4.16.1. OTC-060-010-400- Ek Garanti Web Sipariş Süreci
Web (4.6.1.2. süreç adımındaki gibi süreç ilerleyecektir.)
Web'den yapılan ek garanti satışının süreç adımları Oliz'den yapılan ek garanti satışı ile aynı olacaktır. (4.6.1.2 başlığında
detaylandırılmıştır.)

Job


<<< SAYFA 66 >>>
SD060010-30 Perakende Kanal - WEB Ek Garanti Sipariş Alım Süreci

Ek garanti satışları ürün ile birlikte yapılabilir ya da sadece ek garanti satışı (Oliz, web, çağrı merkezi) yapılabilecektir.
Oliz'de montajı yapılmış ürünün seri numarası ile eşleştirilerek ek garanti satışı yapılır.S4 a yalnızca ek garantinin hangi ürün için
satıldığı bilgisi tutulur. Müşteri malzeme numarası alanından takip edilir.
Ek garanti malzemesi siparişte ZS04 hizmet malzemesi (teslimat ilişkisiz ) takip edilecektir.

5.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

6.

İlişkili Olan Diğer Süreç Dokümanları

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF
Tipi

WRICEF Sorumlusu
(Arçelik/SAP)

SATH2124

Genel Satış Teklif Belgesi Yaratma Servisi

Entegras
yon

Meltem Komur Akan

SATH2114

Genel Satış Sipariş Detay Bilgileri Servisi

Entegras
yon

Meltem Komur Akan

SATH2112

Genel Satış Siparişi Listeleme Servisi

Entegras
yon

Meltem Komur Akan

SATH2110

Genel Satış Siparişi Değişikliği Servisi

Entegras
yon

Meltem Komur Akan

SATH2105

Genel Satış Siparişi Yaratma Servisi

Entegras
yon

Meltem Komur Akan

CR


<<< SAYFA 67 >>>
SATH1300

Dropshipment SD siparişine karşılık PO belgesi oluşturma süreci - SD074

Program

Meltem Komur Akan

SATH1299

Dropshipment süreci için entegrasyondan gelen bilgiye istinaden SAS oluşturulması - MM095

Program

Meltem Komur Akan

SATH1298

Dropshipment süreci için entegrasyondan gelen bilgiye istinaden mal girişi yapılması - MM096

Program

Meltem Komur Akan

SATH1297

Dropshipment süreci için entegrasyondan gelen bilgiye istinaden tedarikçi fatura kaydı(MIRO)
oluşturulması - MM097

Program

Meltem Komur Akan

SATH1214

Satış siparişlerinin excel ile toplu aktarımı - WRICEF No: N/A

Program

Meltem Komur Akan

SATH1151

Satış siparişleri için depo yerinin belirlenmesi - SD041

Program

Meltem Komur Akan

SATH1994

Sipariş Raporu - SD110

Rapor

Meltem Komur Akan

SATH2654

Fiyatlandırma kurunun alış veya satış kurundan devralınması için satış sipariş belgesin alan
eklenecektir WRICEF No: N/A

Geliştir
me

SATH2125

Teşvik kapsamında yapılan satışlar için sipariş belgesinde ek alanların açılması- WRICEF No: N/A

Geliştir
me

SATH1537

S/4HANA Skala onay mekanizması Workflow - SD168

Geliştir
me

Meltem Komur Akan

SATH2139

aATP amacıyla Satış siparişi satırında İlçe grubu ve ürün grubu bilgilerinin tutulması WRICEF No:
N/A

Geliştir
me

Meltem Komur Akan

SATH1984

Yedek Parça İhracat : ECC sisteminden gelen entegrasyonla satış siparişi açılması - MM048

SATH2134

Müşteri Hizmetleri: Yedek Parça sipariş stoklarının karşılanması için Merkez depodan Bölge
depoya stok aktarımının yapılması - N/A

SATH2137

Müşteri Karşılama Oranları Raporu (ZML2) - N/A

SATH2138

Seyahat Hakkı veya bağlantı kapsamında bulunan satışların ve iadelerin toplu referanslı olarak
raporlanması WRICEF No: N/A

SATH2141

Toplu Değişiklik: Satış sipariş bilgileri değiştir - N/A

SATH2143

Yedek Parça İhracat : Entegrasyon belge kontrol raporu - N/A

SATH2142

Yedek Parça İhracat : Arçelik Pazarlama S4/HANA sisteminde teslimat mal çıkışının ardından ECC
Mal giriş entegrasyonu IDoc - N/A

SATH2144

Teklif Raporu - N/A

SATH2282

Bir üründen tek seferde birden çok bayi için toplu sipariş girilmesi - N/A

SATH2820

Ek garanti satış sürecinin Rapid sistemi üzerinden Saris sistemi ve SAP sistemi ile entegrasyonu

SATH2822

Adresler il, ilçe, mahalle bazında Saris sisteminden SAP sistemine alınacaktır.
