---
kaynak_dokuman: "Final_Completed_OTC-070-060_Fiktife_Alma_Sürec.pdf"
konu: "OTC-070-060 Fiktife Alma Süreci"
bicim: pdf
---

# Final_Completed_OTC-070-060_Fiktife_Alma_Sürec.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-060 Fiktife Alma Süreci

Teknik ve Süreç Dokümanı
Süreç kodu

Süreç Adı

OTC-070

Sevk ve Teslimat Yönetimi

Arçelik IT Sorumlusu

SAP Danışmanı

Mehmet Ercan, Ayşegül Doğar Gürbüz, Yağmur Kucur

Onur Türkeş, Meltem Komur, Aslıhan Türkmen

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

OTC-070-060

Fiktife Alma Süreci

L4 Kodu

L4 Süreç Adı

OTC-070-060-010

Fiktife alma süreci

Doküman Detayı
Hazırlayan

SAP Çözüm Mimarı

Aslıhan Türkmen

Fuat Güney Günay / Onur Türkeş

SAP Proje Yöneticisi

Arçelik Proje Yöneticisi

Funda Taş

Tasarım Dokümanının Tanımı


<<< SAYFA 2 >>>
1.

Amaç

Bu doküman sevkiyat ve teslimat yönetimi kapsamında ortaya çıkan fiktife alma sürecinin Arçelik iş süreçlerinin tasarımını, SAP En İyi
Uygulamalar, Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları halinde
içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Fiktife alma sürecinin kullanılacağı organizasyonel yapı aşağıdaki gibidir:
Satış organizasyonu “Arçelik” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Beko” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Alternatif” olacaktır ve bu satış organizasyonu altında “Kurumsal”, “HVAC & Energy Solutions
(İklimlendirme)”, “Altus”, “Grundig” dağıtım kanalları bulunacaktır.

2.2

Ana Veri

Fiktife alma sürecinde malzeme ve müşteri ana veri yapısı kullanılacaktır.

2.3

Varsayımlar

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Fiktife alma süreci SAP standart süreci olmadığı için Best Practice detayı bulunmamaktadır.

4. Arçelik Senaryolara Genel Bakış
4.1. OTC-070-060-010 Fiktife Alma Süreci
Malın fiili olarak müşteriye gönderilmediği ama faturanın önceden kesildiği süreçler için kullanılmaktadır.
Fiktif sürecinde (peşin faturalan) ürünler 16 gün içerisinde gönderilmelidir.
16 günü geçen sevkiyatlar otomatik emanete alınacaktır. Ayrıca sehven fiktife alma durumunda manuel olarak emanete
dönüştürülecektir.

4.1.1.

Sürece Genel Bakış

Müşteri ve malzeme ana verisinde fiktif sürecinin yürütülmesi için bir gösterge olacaktır.
Sipariş belgesi üzerinde kalem bazında fiktif göstergesi olacaktır.
Teslimat belgesi üzerinde başlık bazında fiktif (Z02) göstergesi olacaktır.
Teslimat ayrıştırma programı yapılacak ve satırdaki göstergelere bakılarak birden fazla teslimat belgesi yaratılacaktır ve teslimat
başlığındaki fiktif göstergesi güncellenecektir.
601U fiktif olan teslimatlar Ortec-Lotus sistemine gönderilmeyecektir.
Tipi fiktife dönen teslimat daha önce Ortec-Lotus sistemine gönderildiyse Ortec-Lotus sistemine iptal bilgisi gönderilecektir.
MM'li depolarda fiktif teslimatlarının mal çıkışı teslimat iş listesi üzerinden manuel olarak yapılacaktır.
EWM'li depolarda fiktif teslimatlarının mal çıkış işlemleri EWM sisteminde yapılacaktır.
Fiktif teslimatlarının mal çıkışının yapılmasından sonra veya faturalama işleminin yapılmasından sonra değersiz olarak yönetilecek stok
mal girişi yapılacaktır.
Fiktif çıkışları daha sonra değersiz stok tarafına giriş yapılmasına takiben otomatik olarak satış siparişi/teslimat belgesi yaratılacaktır.
Değersiz tarafta EWM ilişkili depolarda mal girişi teslimat üzerinden yapılacaktır ve EWM sisteme ilk değerli çıkış belgesiyle(601U
teslimatı) bu girişi eşleştirdiği (601E teslimatı) noktada mal çıkış ve mal giriş bilgilerini S4 sistemine gönderecektir.


<<< SAYFA 3 >>>
Fiktiften emanete dönme kuralı sadece bayi kanalında işletilecektir.
Fiktife alınmayacak ürünler aşağıda listelenmiştir:
Cep telefonu
Yazar kasa ( pompa yazar kasa hariç)
Malzeme ana verisinde tutulan "fiktife alınabilir" göstergesi ile ürünlerin fiktife alınma durumu belirlenir.

4.1.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070060-01 Fiktife alma süreci
SD070060-01 Fiktife Alma Süreç Akışı Ekran Görüntüsü :

Draft

4.1.3.

Süreç Adımları

Fiktife alma süreç akışının adımları aşağıdaki gibidir:

Süreç
Adım
No

Süreç Adımı

1

Depo tarafından teslimat belgesinde fiktif göstergesi belirlenir.

1.1

Toplu emanet/fiktif alma 601U işlemleri yürütülür.

İşlem Kodu

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

1.2

Sipariş açılırken emanet/fiktif göstergesi bulunmayan teslimatlar için depo kullanıcıları
tarafından "fiktife al" veya satış ekibi tarafından "emanet al" işlemleri yapılır. ZSD_0034 seçim
ekranında butonlar yetki nesnesine bağlanmıştır. Satış ekibi "emanete al" deponun ise "fiktife
al" butonu ile açılan ekranlara yetkisi bulunmaktadır.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

Entegrasyon
Kaynak
Sistem

Job


<<< SAYFA 4 >>>
1.3

601U teslimatları fiktife alınırken işlemler otomatik yapılır.
Belge üzerinde fiktif göstergesi belirlenir.
Teslimatın çekmesi yapılır.
Teslimat EWM depo ise EWM sistemine dağıtılır.
Teslimat MM depo (Arbarkod/ Total depo) ise mal çıkışı yapılır.
Teslimatın faturası oluşturulur.

1.4

Teslimat Ortec ilişkili (teslimat başlığındaki teslimat nakliye planlama durumu= "90") ise;
Teslimat kalemindeki nakliye planlama statüsü "01"- Ortec'e henüz gönderilmeyen ve
araç planı yapılmayan teslimatlar emanet/fiktife alınır.
Teslimat kalemindeki nakliye planlama statüsü "03"- Ortec'e gönderilen ve araç planı
yapılmayan teslimatlar emanet/fiktife alınır. Ortec'e iptal bilgisinin gönderilmesi için
nakliye planlama statüsü "05"belirlenir ve Ortec'ten teslimat silinir. İptal bilgisi gönderilen
teslimatın nakliye planlama statüsü "03"olarak güncellenir.
Ortec'te araç planı yapılan teslimatlar fiktife alınamaz.

1.5

Teslimat belgesi üzerinde başlık verilerinde fiktif göstergesi manuel belirlenemez.
Fiktif göstergesi sadece ZSD_0034 ekranında program yürütüldüğünde güncellenir.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti
ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti
ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri

VL01N/VL02N ekranlarında emanet/fiktif göstergesi alanı düzenlemeye kapatılmıştır.
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti
1.6

ZS08 - Mağaza teslimatlarının fiktife alınmaması için ZSD_P_TOPLU_EMANET_FIKTIF
programına (ZSD_0034) kontrol eklenmiştir.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

1.7

Emanet/fiktife alınan teslimatların faturası oluşmadıysa "belgeleri işle" işlemi ile teslimatın
tamamlanmayan adımları otomatik job ile ya da manuel olarak kullanıcı tarafından yürütülür.
Fatura adımı tamamlanan teslimatlar ALV'den silinir. Belgelerin durumu "rapor" işleminden
kontrol edilir.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

2

Toplu emanet/fiktif alma 601E işlemleri yürütülür.

ZSD_0002 Toplu emanet
/fiktif alma
601E işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

ZSD_
JOB_
VARY
_1 /
JOB:
601U
:
Eman
et
Belg.
i İşle
ZSD_
JOB_
VARY
_2 /
JOB:
601U
:
Fiktif
Belg.
i İşle


<<< SAYFA 5 >>>
2.1

ZSD_0002 ekranında faturalar listelenir. 601E depo stoklarına giriş yapılması için aşağıdaki
işlemler otomatik yapılır.
İade sipariş belgesi oluşturulur.
İade teslimatı yaratılır.
601E depo stoklarına mal girişi yapılır. Her müşteri için oluşturulan fiktif PYP stokuna mal
girişi yapılır.
Fiktif çözme belgesi oluşur.

ZSD_0002 Toplu emanet
/fiktif alma
601E işlemleri

ZSD_
JOB_
VARY
_1
JOB:
601E:
Eman
et
Belg.
İşle
ZSD_
JOB_
VARY
_2
JOB:
601E:
Fiktif
Belg.
İşle

ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

Örneğin; 24101335 müşteri koduna sahip bayi için 601E işlemleri yürütüldüğünde mal giriş
adımında fiktif için F-0024101335 PYP stokuna giriş yapılır.
ZSD_0002 ekranı job veya manuel olarak kullanıcı tarafından yürütülür.

3

Fiktif çözme siparişinin sevk edilmesi için sevkiyat kokpitinden teslimat belgesi oluşturulur.

ZSD_0023

4

Fiktiften sevk teslimatı nakliye planlaması için Ortec'e gönderilir.

ZSD_0001

Nakliye planlama süreçlerinin detayı linkinde Final_OTC-070-020 Nakliye planlama açıklanmakt
adır.
5

16 günü geçen sevkiyatlar otomatik emanete alınacaktır. Ayrıca sehven fiktife alma
durumunda manuel olarak emanete dönüştürülecektir.

ZSD_0059 Fiktiflerin
otomatik
emanete
dönüştürülmesi
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

5.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

6.

İlişkili Olan Diğer Süreç Dokümanları

No UPM Süreç Adı

Referans Doküman Linki

Açıklama

1

Nakliye Planlama

Final_OTC-070-020 Nakliye planlama

Ortec nakliye planlama süreçleri detaylandırılmıştır.

2

Sevkiyat Planlama

Final_OTC-070-010 Sevkiyat planlama

Teslimat belgesinin oluşturulması detaylandırılmıştır.

3

Çekme İşlemleri (EWM/Total Depo
/Arbarkod Entegrasyonu)

Final_OTC-070-030 Çekme İşlemleri

Sevkiyatın sonraki adımı olan çekme süreci
detaylandırılmıştır.

4

Mal çıkış süreçleri (EWM/Total Depo
/Arbarkod Entegrasyonu)

Final_OTC-070-040 Mal çıkış süreçleri

Sevkiyat planlamanın son aşaması olan mal çıkış
süreçleri detaylandırılmıştır.

5

Emanet/Fiktif Çözme

Final_OTC-070-070 Emanet/Fiktif Çözme
(Emanetten Sevk)

Emanet/fiktif çözme siparişlerinin oluşması
detaylandırılmıştır.

6

Emanete alma

Final_Completed_OTC-070-050 Emanete
Alma Süreci

Emanet/fiktif alma sürecinin detayı açıklanmıştır.

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF Tipi

SATH-1991

Emanet ve Fiktife Alma

Geliştirme

SATH-1993

Emanet / Fiktif süreci için User Exit'e kontrollerin eklenmesi

Geliştirme

WRICEF Sorumlusu (Arçelik/SAP)

....

CR
