---
kaynak_dokuman: "Final_Completed_OTC-070-020_Nakliye_planlama.pdf"
konu: "OTC-070-020 Nakliye Planlama (Ortec-Lotus entegrasyonu, ZSD_0001)"
bicim: pdf
---

# Final_Completed_OTC-070-020_Nakliye_planlama.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-020 Nakliye planlama

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

OTC-070-020

Nakliye planlama (Ortec-Lotus sistemi entegrasyonu)

L4 Kodu

L4 Süreç Adı

OTC-070-020-010

Nakliye Sistemi Entegrasyonu

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

Bu doküman sevk ve teslimat yönetimi kapsamında ortaya çıkan nakliye planlama sürecinin Arçelik iş süreçlerinin tasarımını, SAP En
İyi Uygulamalar, Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları
halinde içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Nakliye planlama için entegre olunacak Ortec-Lotus sisteminin kullanılacağı organizasyonel yapı aşağıdaki gibidir:
Satış organizasyonu “Arçelik” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Beko” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Alternatif” olacaktır ve bu satış organizasyonu altında “Kurumsal”, “HVAC & Energy Solutions
(İklimlendirme)”, “Altus”, “Grundig” dağıtım kanalları bulunacaktır.
Satış organizasyonu “Müşteri Hizmetleri” olacaktır ve bu satış organizasyonu altında “Ürün Değişim” dağıtım kanalı bulunacaktır.

2.2

Ana Veri

Nakliye planlama sürecinde malzeme ve müşteri ana veri yapısı kullanılacaktır.

2.3

Varsayımlar

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Nakliye planlama ilişkili Best Practice ve süreç akış diagramı aşağıdaki linkte yer almaktadır.
BD9-Sell from Stock Process

4. Arçelik Senaryolara Genel Bakış
4.1. OTC-070-020-010 Nakliye Sistemi Entegrasyonu
SAP S/4 HANA sisteminde yaratılan teslimat belgelerinin nakliye planlaması Ortec-Lotus sistemde yapılacaktır.

4.1.1.

Sürece Genel Bakış

SAP S/4 HANA sisteminde yaratılan teslimat belgeleri entegrasyonla Ortec-Lotus sistemine gönderilecektir.
Teslimatlar Ortec-Lotus sisteminde araç planlamasına alınabilecek, gerekliyse bölünebilecek ve birleştirilebicektir. Bu bilgi SAP S/4
HANA sistemine iletilecektir.
Ortec-Lotus siteminde seçilen teslimat kalemlerinin araç planlaması SAP S/4 HANA sistemine geldiğinde ilgili teslimat için araca
planlanan kalemler var ise bu kalemler SAP S/4 HANA sisteminde teslimat ayrıştırma yöntemiyle mevcut teslimataki kalem miktarı
sıfırlanacak ve yeni teslimat oluşturulacaktır. Bu teslimat Ortec-Lotus sistemine gönderilecektir. Aynı teslimatın araca planlanmayan
kalemleri mevcut teslimatta kalacaktır.
Nakliye planlamasında belirlenen araç bilgileri Ortec-Lotus sisteminden SAP S/4 HANA sistemine gönderilecektir. SAP S/4 HANA
sistemindeki teslimatta bulunan araç ID ve durak sırası gibi bilgiler güncellenir.
Nakliye planlandı statüsündeki teslimatlar manuel ya da otomatik olarak EWM sistemine dağıtılacaktır. (Sadece EWM kullanan depolar
için geçerlidir, MM depoları dağıtma işlemini yapmayacaktır.)
Ortec - Lotus sisteminden gelen e-irsaliyeye baz olacak veriler SAP S/4 HANA sistemine gönderilir ve bu bilgiler ZSD_T_VEHICLE /
ZSD_T_VEHICLE_IT tablolarında tutulur. Mal çıkışı yapıldıktan sonra teslimatın e-irsaliyesi oluşturulur.

4.1.2.

Süreç Akışı


<<< SAYFA 3 >>>
Arçelik Solution Process Flow Linkleri
SD070020-01 Nakliye Planlama Süreci
SD070020-01 Nakliye Planlama Süreci Süreç Akışı Ekran Görüntüsü :

Draft

4.1.3.

Süreç Adımları

Nakliye planlama süreç adımları aşağıdaki gibidir :
SAP S/4 HANA sisteminde yaratılan teslimatlar nakliye planlamasının yapılması için Ortec-Lotus sistemine gönderilir.
Teslimat kalemleri Ortec-Lotus sistemine kaydedilir.
Ortec-Lotus sisteminde araç bazında detay planlama yapılır.
Eğer gerekiyorsa Ortec-Lotus sisteminde teslimat satırı için ayrıştırma yapılır.
Teslimat ayrıştırma bilgisi SAP S/4 HANA sistemine gönderilir ve teslimat satırı için ayrıştırma yapılır.
SAP S/4 HANA sisteminde teslimat araç bilgilerinin güncellenmesi yapılır.

Süreç
Adım
No

Süreç Adımı

İşlem
Kodu

1

Teslimat belgesi oluşur.

ZSD_0023

1.1

ZSD_T_DLV_CONFIG bakım tablosunda girilen teslimat türü, satış organizasyonu, sevkiyat noktası ve muhatap türüne
göre teslimatın Ortec-Lotus ilişkisi belirlenir.

ZSD_T00
07

Entegrasyon
Kaynak
Sistem

Entegrasyon
Hedef
Sistem


<<< SAYFA 4 >>>
1.2

Ortec-Lotus ilişkisi olan teslimatın başlığındaki teslimat nakliye planlama durum "90" olarak belirlenir.

1.3

Ortec-Lotus ilişkisi olan teslimatın kalemindeki teslimat nakliye planlama durum "01" olarak belirlenir.
Kalemde tutulan nakliye planlama durumu entegrasyonlar tetiklendiğinde güncellenir.
01 => Teslimat oluştuğu anda ZSD_T_DLV_CONFIG tablosundaki verilere göre Ortec ilişkili ise 01 statüsü
belirlenir.
02 => ZSD_0001- Ortec-Lotus gönderme ekranından Ortec'e gönder butonu ile teslimat statüleri 02 olarak
güncellenir. Bu statü ALV ekranına gelmediği için kullanıcı bu kalemi tekrardan Ortec sistemine gönderemez.
03 = Ortec-Lotus sisteminden SAP S/4 HANA sistemine teslimatın Ortec'e kaydedildiği bilgisi için dönüş
geldiğinde statü 03 olarak güncellenir. Bu statü ALV ekranına gelmediği için kullanıcı bu kalemi tekrardan Ortec
sistemine gönderemez.
04 => ZSD_0001 ekranından teslimat gönderilirken hata alırsa statü 04 olarak güncellenir. Hatanın giderilip
tekrar gönderilebilmesi için ALV ekranına 04 statüsündeki teslimatlar düşecektir.
05 => Ortec-Lotus ilişkili olan teslimatta değişlik yapılabilmektedir. Teslimat miktarı sıfır, teslimatın emanet
/fiktife alınması ve teslimata blokaj konulduğunda statü 05 olarak güncellenir. Ortec-Lotus sistemine iptal bilgisi
gönderilir ve Orte'ten bu teslimat silinir.
06 => Mal çıkışı yapılan ve e-irsaliye belgesi oluşturulan teslimatlar Ortec-Lotus sistemine realizasyon
tamamlandı bilgisi gönderilir.
07 => Teslimat miktarı EWM sisteminde YUTS istisna kodu ile düşüm yapılır. S4 sistemine düşüm bilgisi
gönderildiğinde sipariş teyidinin kaybolmaması için düşülen miktarla yeni teslimat yaratılır. Yeni teslimat statüsü
01 olur. Mevcuttaki teslimat kaleminin statüsü 07 olarak güncellenir. (Bu statü canlı sistemde pasif hale
getirilmiştir.)

1.4

Teslimatların Ortec-Lotus sisteminde nakliye planlama önceliğinin belirlenmesi için SAP S/4 HANA sisteminde
ZSD_T_ORD_PRIORI bakım tablosu yapılmıştır.

ZSD_T00
12

1000: Düşük öncelik
600: Yüksek öncelik

2

Teslimatlar Ortec-Lotus sistemine entegrasyonla gönderilir.

ZSD_0001 SAP S/4 HANA

Ortec


<<< SAYFA 5 >>>
2.1

Teslimatlar ZSD_0001 ekranından "Lotus'a gönderme" işlem tipi seçilerek gönderilir.
Ekranda nakliye planlama durumu 01 ve 04 olan teslimatlar listelenir.
01 statüsündeki teslimatların gönderilmeme durumları aşağıda yer almaktadıır.
Emanet göstergesi alanı dolu
Teslimat miktarı 0
Teslimat blokajı dolu
Bu durumlarda teslimat ALV ekrana gelmez ve Ortec-Lotus sistemine gönderilemez.

2.2

Ortec-Lotus sistemine gönderilen teslimatlarda zorunlu alanların boş olmasından kaynaklı hatalar alınmaktadır.
Teslimatta nakliye planlama statüsü 04 olarak güncellenmektedir.

2.2.1

Ortec-Lotus sisteminde planlama yapılacak nihai adres bilgisinin gönderilemesinden kaynaklı alınan hatalar:
Adres verisinin Ortec-Lotus sisteminde bulunmaması.
Özellikle kurumsal kanal süreçlerinde proje satışlarında ürünlerin proje alanına, inşaat lokasyonuna gönderilmesi
için sipariş açılırken teslimat türü "10- Doğrudan teslim" belirlenmektedir. Bu alan teslimata kopyalanır. Eksik
olduğunda müşteri gönderilemediği için teslimat hata alıp nakliye planlama statüsü 04 olarak güncellenir.
Tüketici teslim sürecinde sevkiyat türü "20-tüketici teslim" olarak belirlenmektedir. Z3-Yetkili servis muhatabı
teslimatta eksik olduğu durumda teslimat gönderilirken hata almaktadır.

2.2.2

Order kind eksikliğinden kaynaklı teslimatlar gönderilirken hata alınır.
ZSD_T_DLV_CONFIG tablosunda order kind alanı eksik olduğunda teslimat Ortec'e gönderilme aşamasında hata verilir.

2.2.3

ZSD_T_ORD_PRIORI tablosunda priority alanı eksik olduğunda teslimat Ortec'e gönderilme aşamasında hata verilir.

2.2.4

Malzeme Ortec-Lotus sisteminde teslimat Ortec'e gönderilme aşamasında hata verilir.

SAP ECC & SAP
S/4 HANA

Ortec

ZSD_0001 SAP S/4 HANA

Ortec

Mevcutta malzeme bilgisi SAP ECC sisteminden alınmaktadır.
SAP S/4 HANA sisteminde de malzemenin gönderilme için bir fonksiyon geliştirilmiştir ama kullanılmamaktadır.
2.3

SAP S/4 HANA sisteminde teslimatlarda aşağıdaki değişiklikler yapıldığında nakliye planlama statüsü 05 olarak
güncellenmektedir.
Teslimatın emanet/fiktife alnıması. Emanet gösterge alanın Z01/Z02 olarak doldurulması
Teslimat miktarının sıfırlanması
Teslimata blokaj konulması
Teslimatlar job ile Ortec-Lotus sistemine iptal bilgisiyle gönderilerek Ortec'ten silinir.
Nakliye planlama statüsü 03 olarak güncellenir.
Gönderirken hata aldığı durumda statü 04 olarak güncellenir ve tekrardan teslimatlardaki değişiklikler job ile
gönderilir. (Statü 04 teslimat değişiklik haricinde manuel olarak kullanıcı tarafından tetiklenmektedir)

3

Ortec-Lotus sisteminden teslimat kaydedilir, SAP S/4 HANA sistemine bu bilgi gönderilir.

Ortec

SAP S/4 HANA


<<< SAYFA 6 >>>
4

Teslimatlardaki malı teslim alan müşteri kodu ZSD_0021 işlem kodundan otomatik job ile ya da manuel olarak OrtecLotus sistemine gönderilir.

ZSD_0021 SAP S/4 HANA

Ortec

Ekran yetkisi kullanıcılarda yoktur, IT ekibi tarafından müşteri entegrayonu manuel olarak tetiklenebilir.
Müşteri gönderimi seçim kriterlerine göre yapılmaktadır.
Müşteri => Müşteri numarası ile gönderilir.
Tarih aralığı => Belirli tarih aralığında değişen müşteri bilgileri gönderilir.
Import order => Günün tarihinde değişiklik yapılan müşteri koduyla teslimat oluşmuş ve Ortec'e gönderiliyorsa
öncesinde değişen müşteri bilgileri gönderilir.

4.1

Ortec-Lotus sisteminde bulunan muhatap türü dönüşüm bakım tablosu ZSD_T_ORT_BPKND aşağıda yer almaktadır.

ZSD_T00
24

Müşteri ana verisinde muhatap türü alanı boş ise ya da bakım tablosunda eksik tür varsa müşteri entegrasyonu
tetiklendiğinde hata alınır ve müşteri bilgisi Ortec-Lotus sistemine gönderilemez.
4.2

Ortec-Lotus sistemine müşteri gönderilirken ZSD_T_ORT_CTYDSC bakım tablosundan il bilgisi alınmaktadır.

ZSD_T00
14

İstanbul ilçelerine göre İstanbul-Anadolu/ İstanbul-Avrupa şeklinde il bilgisi gönderilir.
Diğer iller için de Ortec'e uyumlu formatta tanımlamalar yapılmıştır.
5

Ortec-Lotus sisteminde araç planı yapılır ve SAP S/4 HANA sistemine gönderilir.

Ortec

SAP S/4 HANA

Ortec

SAP S/4 HANA

SAP S/4 HANA sisteminde ZSD_T_VEHICLE ve ZSD_T_VEHICLE_IT tablolarına araca ilişkin kayıt atılır.
Teslimattaki "harici teslimat" alanına araç ID yazılır. (LIKP-LIFEX)
Teslimattaki durak sırası alanı güncellenir.

5.1

Ortec-Lotus sisteminde teslimatın tüm kalemleri için araç planı yapılır.


<<< SAYFA 7 >>>
5.2

Ortec-Lotus sisteminde teslimatın bazı kalemleri için araç planı yapılır.

SAP S/4 HANA

Ortec

SAP S/4 HANA

Ortec

Ortec

SAP S/4 HANA

SAP S/4 HANA

Ortec

Ortec

SAP S/4 HANA

1- ZSD_FM_ORTEC_EXPORT_ROUTE_IN_2 fonksiyonuyla ZSD_T_VEHICLE ve ZSD_T_VEHICLE_IT tabloları güncellenir.
2- Yeni teslimat oluşması ve Ortec'e gönderilmesi için ZSD_FM_ORTEC_MERGE_DATA_OUT fonksiyonu çağrılır.
3-Orijinal teslimat ayrıştırılır. Araç ID(LIFEX) boş olacaktır.
4-Araç planlanmış kalem için Araç ID(LIFEX) dolu olan yeni teslimat oluşur ve senkron olarak Ortec'e gönderilir.
5.3

SAP S/4 HANA sisteminde ayrışan teslimatlar entegrasyon kaynaklı bir hata sebebiyle Ortec'e gönderilmediği durumda
ZSD_T_VEHICLE_IT-STATUS= '02' olmaktadır.
Gönderilemeyen teslimatların tekrar tetiklenmesi için ZSD_0001 ekranında "teslimat ayrıştırma gönderme" işlem tipi
için job kurulmuştur.

6

Ortec-Lotus sisteminde teslimat kaleminin miktarı araca sığmadığı durumda bölünürek araç planı yapılır. Bölünmek
istenen miktar SAP S/4 HANA sistemine gönderilir.
SAP S/4 HANA sisteminde ZSD_T_SPLIT tablosuna kayıt atılır.

6.1

Ortec-Lotus sisteminde bir araca planlı olan teslimat kalemi bölünme talebi geldiğinde aşağıdaki işlemler sırasıyla
yapılır.
1- SAP S/4 HANA sisteminde araç planlanmış miktarlar için Araç ID(LIFEX) dolu olan iki yeni teslimat oluşur.
2- Senkron olarak ZSD_FM_ORTEC_SPLIT_DELIVRY_OUT fonksiyonuyla Ortec'e gönderilir.
3- Mevcut teslimatta bölünen kalemin miktarı sıfırlanır.

6.2

Ortec-Lotus sisteminde bir araca planlı olamayan teslimat kalemi bölünme talebi geldiğinde aşağıdaki işlemler sırasıyla
yapılır.
1- SAP S/4 HANA sisteminde araç planlanmış miktarlar için Araç ID(LIFEX) boş olan iki yeni teslimat oluşur.
2- Senkron olarak ZSD_FM_ORTEC_SPLIT_DELIVRY_OUT fonksiyonuyla Ortec'e gönderilir.
3- Mevcut teslimatta bölünen kalemin miktarı sıfırlanır.

6.3

SAP S/4 HANA sisteminde yeni oluşan teslimatlar entegrasyon kaynaklı bir hata sebebiyle Ortec'e gönderilmediği
durumda ZSD_T_SPLIT-STATUS= '02' olmaktadır.
Gönderilemeyen teslimatların tekrar tetiklenmesi için ZSD_0001 ekranında "kalem bölme gönderme" işlem tipi için job
kurulmuştur.

7

Araç planlaması yapılan teslimatlara rota iptali yapılabilmektedir.

7.1

Ortec'ten SAP S/4 sistemine trip status "cancel" olarak gönderilmektedir.

7.2

ZSD_T_VEHICLE_IT tablosunda CANCEL alanında teslimatın iptal bilgisi güncellenir.

7.3

Teslimattan araç id(LIKP-LIFEX) silinir.

8

Araç planı yapıldıktan sonra teslimata mal çıkışı yapılır, sürece ilişkin detaylar Final_Completed_OTC-070-040 Mal çıkış
süreçleri dokümanında yer almaktadır.

8.1

Teslimatın depo yeri MM depo(Arbarkod/Total) ise ürünler okutulup mal çıkışı yapılır. Çekme sürecine ilişkin detaylar Fin
al_Completed_OTC-070-030 Çekme İşlemleri dokümanında yer almaktadır.

8.2

Teslimatın depo yeri EWM depo ise teslimat EWM sistemine dağıtılır ve EWM sisteminden mal çıkışı bilgisi SAP S/4
HANA sistemine gönderilir.

8.2.1

Teslimat Ortec ilişkisiz ise EWM sistemine otomatik dağıtılır. Ortec ilişkisiz teslimatlarda araç id(LIKP-LIFEX) boş
olacaktır.

ZSD_0001 SAP S/4 HANA

EWM

ZSD_0001 SAP S/4 HANA

EWM

Örneğin Marketplace ve WEB kanallarında montajsız ürünler kargoyla sevk edileceği için Ortec ilişkisiz olmaktadır ve
otomatik olarak EWM'e dağıtılmaktadır.
8.2.2

Teslimat Ortec ilişkili ise EWM sistemine manuel olarak kullanıcı tarafından dağıtılır. Teslimatlarda araç id(LIKP-LIFEX)
olanlar için EWM'e dağıtım işlemi yapılabilmektedir.

8.3

Ortec'te bulunan teslimatlara araç planı, miktar bölme, kalem ayrıştırma gibi değişiklik yapılamama durumları:
Mal çıkışı yapılan teslimatlar (MM/EWM)
EWM sistemine dağıtılan teslimatlar
Kullanıcı tarafından teslimatın locklanması
Teslimat miktarlarının Ortec ve SAP S/4 sistemlerindeki uyumsuzluğu (Ortec'te miktar bölme talebi
entegrasyonlarının birden fazla kez üst üste tetiklenmesi ve SAP S/4 sisteminden Ortec'e yanıt dönülmediği
durumda)
Ortec'ten değişiklik talebi geldiğinde SAP S/4 HANA sisteminden hata dönülmektedir.

9

Mal çıkışı yapılan teslimat için E-irsaliye belgesi oluşturulur. E-irsaliye sürecine ilişkin detaylar E-çözüm
dokümanlarında yer almaktadır.

9.1

Personel satış süecinde E-irsaliye oluşmayacaktır, E-fatura oluşturularak ürünler müşteriye sevk edilecektir.

9.2

Ürün değişim depoları arasındaki süreçlerde E-irsaliye, ürün değişim depolarından çıkan ve servise giden ürünler için Efatura oluşmaktadır.

ZCZM_E
DM


<<< SAYFA 8 >>>
10

Mal çıkışı yapılan ve E-irsaliye belgesi oluşan araç içindeki tüm teslimatların SAP S/4 HANA sistemindeki güncel
versiyonu, realizasyon entegrasyonuyla Ortec sistemine gönderilir.
Bu entegrasyona ihitiyaç duyulmasının sebebi; ürünler okutulurken çekme adetlerinde, teslimat miktarlarında araca
sığmamasından kaynaklı miktar düşümü yapılmaktadır. Teslimattaki güncel bilginin Ortec'e gönderilmesi
gerekmektedir.

10.1

5.

Realizasyon(yükleme tamamladı) bilgisi Ortec'e başarıyla gönderildikten sonra teslimatların nakliye planlama statüsü
"06" olarak güncellenir.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

6.

İlişkili Olan Diğer Süreç Dokümanları

No UPM Süreç Adı

Referans Doküman Linki

Açıklama

1

Sevkiyat Planlama

Final_Completed_OTC-070-010
Sevkiyat planlama

Teslimat belgesinin oluşturulması detaylandırılmıştır.

2

Çekme İşlemleri (EWM/Total Depo/Arbarkod
Entegrasyonu)

Final_Completed_OTC-070-030
Çekme İşlemleri

Sevkiyatın sonraki adımı olan çekme süreci
detaylandırılmıştır.

3

Mal çıkış süreçleri (EWM/Total Depo
/Arbarkod Entegrasyonu)

Final_Completed_OTC-070-040 Mal
çıkış süreçleri

Sevkiyat planlamanın son aşaması olan mal çıkış
süreçleri detaylandırılmıştır.

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF
Tipi

WRICEF Sorumlusu (Arçelik
/SAP)

CR

SATH1536

S/4 HANA -> Ortec'e gönderilecek belgelerin yönetimi için bir yapı tasarlanacaktır. SD052

Geliştirme

Aslıhan Türkmen

X

SATH1999

Yansıtma/Nakil Kokpiti ve Geliştirmeleri - SD043?

Geliştirme

Aslıhan Türkmen

X

SATH1997

Takas kokpiti - SD043 ?

Geliştirme

Aslıhan Türkmen

X
