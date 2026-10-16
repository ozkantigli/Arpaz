---
kaynak_dokuman: "Final_Completed_OTC-070-070_Emanet_Çözme.pdf"
konu: "OTC-070-070 Emanet Çözme (Emanetten Sevk)"
bicim: pdf
---

# Final_Completed_OTC-070-070_Emanet_Çözme.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-070 Emanet Çözme
(Emanetten Sevk)

Teknik ve Süreç Dokümanı
Süreç Kodu

Süreç Adı

OTC-070

Sevk ve Teslimat Yönetimi

Arçelik IT Sorumlusu

SAP Danışmanı

Mehmet Ercan, Ayşegül Doğar Gürbüz, Yağmur Kucur

Onur Türkeş, Meltem Komur, Aslıhan Türkmen, Gökmen Altınel

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

OTC-070-070

Emanet/Fiktif Çözme (Emanetten Sevk)

L4 Kodu

L4 Süreç Adı

OTC-070-070-010

Emanet Çözme (Emanetten Sevk)

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

Bu doküman sevkiyat ve teslimat yönetimi kapsamında ortaya çıkan emanet çözme (emanetten sevk) sürecinin Arçelik iş süreçlerinin
tasarımını, SAP En İyi Uygulamalar, Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve
süreç adımları halinde içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Emanet Çözme (emanetten sevk) sürecinin kullanılacağı organizasyonel yapı aşağıdaki gibidir:
Satış organizasyonu “Arçelik” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Beko” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Alternatif” olacaktır ve bu satış organizasyonu altında “Kurumsal”, “HVAC & Energy Solutions
(İklimlendirme)”, “Altus”, “Grundig” dağıtım kanalları bulunacaktır.

2.2

Ana Veri

Emanet Çözme (emanetten sevk) sürecinde malzeme ve müşteri ana veri yapısı kullanılacaktır.

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Emanet çözme (emanetten sevk) süreci SAP standart süreci olmadığı için Best Practice detayı bulunmamaktadır.

4. Arçelik Senaryolara Genel Bakış
4.1. OTC-070-070-010 Emanet Çözme (Emanetten Sevk) Süreci
Emanette bulunan ürünlerin müşteriye gönderilmesi sürecidir.

4.1.1.

Sürece Genel Bakış

Emanet çözme süreci için bir onay yapısı akışı olacaktır.
Bayi veya müşteri temsilcisi emanet çözme talebinde bulunacaktır. Bayi, Mars sisteminden müşteri temsilcileri ise Mars ve SAP S/4
HANA sistemlerinden emanet çözme talebinde bulunacaktır.
Mars sistemindeki emanet çözme talebi SAP S/4 HANA sistemine gönderilecektir.
Bayinin emanet çözme talepleri müşteri temsilcisi tarafından onaylanacak ya da reddedilecektir.
Onaylanan taleplerin satış siparişleri sevkiyat adımlarıyla devam edecektir.
Emanet çözme talepleri toplu bir şekilde de onaylanabilecektir. Onaylama yetkilendirmesi bölge bazında olacaktır.
Emanetten sevk sürecinde irsaliye emanetten çıkış yapılana kadar kesilmemektedir. Emanet ve Fiktif fatura türlerinde fatura üzerinde
not olarak "FATURA MUHTEVİYATI EMTEA EMANETE ALINMIŞ OLUP SONRA SEVK EDİLECEKTİR." açıklaması yazılacaktır. Emanete
istinaden irsaliye kesildiği durumda müşteriye kesilen satış fatura numarası irsaliye üzerinde yer almaktadır.

4.1.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070070-01 Emanet Çözme Süreci
SD070070-01 Emanet Çözme Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 3 >>>
Draft

4.1.3.

Süreç Adımları

Emanet çözme (emanetten sevk) süreç adımları aşağıdaki gibidir:
Süreç
Adım
No

Süreç Adımı

İşlem
Kodu

Entegrasyon
Kaynak
Sistem

Fonksiyon

1

Emanet çözme siparişi açılır

1.1

Mars sisteminde emanet çözme talebi için satış siparişi açılır.

MARS

1.1.1

Emanet faturaları MARS sisteminde faturalama tarihi en eskiden en yeniye olacak şekilde listelenir.

MARS

ZSD_FM_EM
ANET_LIST

1.1.2

MARS'tan bayi/bayi yönetmeni tarafından emanet çözme siparişi oluşturulur. Bayiye ya da tüketiciye çözme yapılabilir.

MARS

ZSD_FM_SA
LESDOCUME
NT_CREATE

1.1.3

Emanet çözme işlemini bayi yaparsa SAP S/4 HANA sisteminde onay süreci işletilir.

MARS

ZSD_FM_EM
ANET_ONAY
_LIST

MARS

ZSD_FM_SA
LESDOCUME
NT_LIST_ST
AT

Bayi yönetmeni tarafından emanet çözme siparişi oluşturulursa sipariş onaya düşmez.
Onay durumu MARS sisteminde "emanet sevk durum" ekranından takip edilir.
1.1.4

Çözülen emanetlerin durumu MARS sisteminde "emanet/fiktif sipariş yönetim" ekranından takip edilir.

1.2

SAP S/4 HANA sisteminden emanet çözme siparişi oluşturulur.

ZSD_002
2Emanet
çözme
kokpiti
ZSD_003
7 - Ana
menü Emanet
/Fiktif
Kokpiti

1.2.1

Emanet faturaları, faturalama tarihi en eskiden en yeniye olacak şekilde listelenir.

ZSD_002
2Emanet
çözme
kokpiti
ZSD_003
7 - Ana
menü Emanet
/Fiktif
Kokpiti

ZSD_FM_EM
ANET_LIST


<<< SAYFA 4 >>>
1.2.2

Emanet çözme ekranında malzeme/müşteri bazında çözme işlemi yapılır. "Çöz" butonuna tıklanınca çıkan pop-up
ekrana ilişkin detaylar aşağıdaki gibidir;
Bayi yönetmeni tarafından emanet çözme siparişi oluşturulur. Bayiye, tüketiciye ve arızi muhataba çözme
yapılabilir.
Emanet çözme belgesi yetkili servis üzerinden gönderilecek ise ekrandaki "servis istemiyorum" alanı boş bırakılır.
Böylelikle siparişte başlık verilerinde "sevkiyat türü=20-Tüketici T.Yetki.Srv" belirlenir. Saris sisteminden yetkili
servis ataması beklenir.
Kurumsal kanallarda emanetten çözülen ürünler inşaat, proje vb. lokasyonlarına gönderim yapıldığı süreçte
emanet çözme belgesinde yetkili servis seçtikleri sürece "sevkiyat türü=10-Tüketici T.Doğrudan" belirlenir ve
yetkili servis ataması beklenmeden teslimat yaratılır.
Siparişte başlık>muhatap rollerinde Z3-yetkili servis ataması yapılmadan teslimat belgesi yaratılamaz.
TH iş emri alanı doldurulursa girilen değerin doğruluğunun kontrolü için SARİS ile sorgu yapılır. (ZSD_FM_TUKETI
CI_TESLIM_SORGULA)

ZSD_002
2Emanet
çözme
kokpiti
ZSD_003
7 - Ana
menü Emanet
/Fiktif
Kokpiti

Girilen değer doğru ise belge kaydedilir ve sipariş>başlık verileri>kullanıcı tanımlı alanlar>th iş emri alanına yazılır,
hatalı değer ise hata mesajı verilerek emanet çözme belgesi oluşmaz.
Müdür onay alanı default işaretli gelmektedir. SAP S/4 HANA sisteminden oluşturulan belgelerde bayi
yönetmenleri tarafından oluşturulduğu için emanet onay sürecine dahil olmamaktadır.
MARS ekranlarını bayiler ve bayi yönetmenleri kullandığı için emanet çözme bayi tarafından yapıldığında onay süreci
işletilecektir.

2

MARS sisteminde bayi tarafından oluşturulan emanet çözme belgesine onay verilir. Mars sisteminde satış yönetmeninin
/müdürünün çözdüğü emanet belgesi onaya düşmez(yani zaten onaylıdır). VBAK-ZZ1_MANAGER_APPROVE_SDH alanı
doluysa emanet çözme belgesi onaya düşmez. Onaylanmayan belgelerde SAP S/4 HANA sisteminde siparişte teslimat
blokajı bulunur. Belge onaylanana kadar teslimat yaratılamaz.

2.1

ZSD_0039 işlem kodundan onaya düşen belgeler görüntülenir ve bölge yöneticileri tarafından onaylanır.

ZSD_0039

Onaycılar: Hat ve hattın müdürüdür. Aynı müdüre bağlı hatlar da birbirlerinin yerine onay verebilmektedir.
2.2

Emanet süreçlerinde onay süreci vardır ancak bir workflow süreci yoktur. ZSD_0039 dan toplu onay/ret yürütülür.

3

Onaylanan emanet çözme sipariş belgesi için teslimat oluşturulur.

ZSD_0023

4

Teslimatın nakliye planlaması için Ortec'e gönderilir.

ZSD_0001

Nakliye planlama süreçlerinin detayı linkinde Final_OTC-070-020 Nakliye planlama açıklanmaktadır.
5

EWM / Arbarkod / Total depo sistemlerinde çekme işlemleri yapılır.

6

EWM / Arbarkod / Total depo sistemlerinde mal çıkışı yapılır.

7

Emanet/ fiktif çözme siparişlerinin durumunu görüntülemek için emanet raporu kullanılır.

ZSD_003
0Emanet
raporu
ZSD_003
7 - Ana
menü Emanet
/Fiktif
Kokpiti

5.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

ZSD_FM_SA
LESDOCUME
NT_CREATE
ZSD_FM_TU
KETICI_TESL
IM_SORGULA


<<< SAYFA 5 >>>
6.

İlişkili Olan Diğer Süreç Dokümanları

No UPM Süreç Adı

Referans Doküman Linki

Açıklama

1

Nakliye planlama (Ortec-Lotus sistemi
entegrasyonu)

https://digiport.arcelik.com
/wiki/x/Yxnuig

Sevkiyatın nakliyesinin planlandığı Ortec-Lotus sisteminin
detayları bulunmaktadır.

2

Çekme İşlemleri (EWM/Total Depo/Arbarkod
Entegrasyonu)

https://digiport.arcelik.com
/wiki/x/JBnuig

Sevkiyatın sonraki adımı olan çekme süreci detaylandırılmıştır.

3

Mal çıkış süreçleri (EWM/Total Depo/Arbarkod
Entegrasyonu)

https://digiport.arcelik.com
/wiki/x/LBnuig

Sevkiyat planlamanın son aşaması olan mal çıkış süreçleri
detaylandırılmıştır.

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF Tipi

WRICEF Sorumlusu (Arçelik/SAP)

CR

SATH-1986

Emanet Çözme ve Emanet/Fiktif Raporlama Geliştirmeleri - SD043

Geliştirme

Aslıhan Türkmen

X

SATH-2146

MARS Emanet Çözme Entegrasyonu - SD170

Entegrasyon

Aslıhan Türkmen

X

Emanet çözme Onay Süreci

Workflow

Gökmen Altınel

X

SATH-1993
