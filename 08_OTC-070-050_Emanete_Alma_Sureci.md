---
kaynak_dokuman: "Final_Completed_OTC-070-050_Emanete_Alma_Süreci.pdf"
konu: "OTC-070-050 Emanete Alma Süreci (ZSD_0034, ZSD_0002, yansıtma ZSD_0035)"
bicim: pdf
---

# Final_Completed_OTC-070-050_Emanete_Alma_Süreci.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-050 Emanete Alma Süreci

Teknik ve Süreç Dokümanı
Süreç Kodu

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

OTC-070-050

Emanete Alma Süreci

L4 Kodu

L4 Süreç Adı

OTC-070-050-010

Emanete Alma Süreci

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

Bu doküman sevkiyat ve teslimat yönetimi kapsamında ortaya çıkan emanete alma sürecinin Arçelik iş süreçlerinin tasarımını, SAP En
İyi Uygulamalar, Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları
halinde içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Emanete alma sürecinin kullanılacağı organizasyonel yapı aşağıdaki gibidir:
Satış organizasyonu “Arçelik” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Beko” olacaktır ve bu satış organizasyonu altında “Yetkili Satıcı Kanalı” dağıtım kanalı bulunacaktır.
Satış organizasyonu “Alternatif” olacaktır ve bu satış organizasyonu altında “Kurumsal”, “HVAC & Energy Solutions
(İklimlendirme)”, “Altus”, “Grundig” dağıtım kanalları bulunacaktır.

2.2

Ana Veri

Emanete alma sürecinde malzeme ve müşteri ana veri yapısı kullanılacaktır.
Müşteri ve malzeme ana verisi üzerinde "emanet alınabilir" ve "fiktif alınabilir" alanları tutulmaktadır. Bu alanlar işaretli değilse belgeler
emanet/fiktife alınamayacaktır.
WEB ve personel kanalları, emanet/fiktife alınmadığı için malzeme ana verisi SD görünümünde emanet/fiktife alınabilir göstergesi
işaretli olmayacaktır.

2.3

Varsayımlar

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Emanete alma süreci SAP standart süreci olmadığı için Best Practice detayı bulunmamaktadır.

4. Arçelik Senaryolara Genel Bakış
4.1. OTC-070-050-010 Emanete Alma Süreci
Emanet/fiktif süreci; sipariş, teslimat ve fatura belgeleri oluştuktan sonra 601E depolarına stok giriş hareketinin yapılıp 601E
depolarından sevk edilmesi için tasarlanan bir yapıdır.

Emanet süreci, Arçelik bünyesinde ürünün müşteri adına depolanmasıdır. Bayinin malı bulunduracak yerinin olmaması, kurumsal
kanallarda müşterilerin proje, inşaat lokasyonlarına ürünün talep edilmesi gibi sebeplerden dolayı emanet süreci yürütülmektedir.
Emanet sürecinde müşteriye fatura kesildikten sonra ürün sanal olarak müşterinin PYP stoklarına giriş yapılarak müşteriye ürün rezerve
edilir.
Müşteri talep ettiğinde Emanet Çözme ekranlarından çözme siparişi açılarak 601E depolardan sevk işlemleri yapılır.

Fiktif süreci, özellikle ay sonlarında ciro hedeflerine ulaşmak için ürünün müşteri gönderilmeden yapılan faturalama işlemidir.
Fatura oluşturulduktan sonra 16 gün içerisinde ürünler sevk edilmektedir.
16 günü geçen sevkiyatlar otomatik emanete alınacaktır. Ayrıca sehven fiktife alma durumunda manuel olarak emanete
dönüştürülecektir.

Yansıtma süreci, emanet ve fiktif siparişlerin, en uygun teslimat noktasına ulaştırılabilmesi için yapılan işlemlerdir.
Emanet / fiktif çözme belgesinde depo yeri matriste müşteri il/ilçe kodu ve malzemede hedef grup bazında bulunan ilk depoya
açılacaktır.


<<< SAYFA 3 >>>
Emanet / fiktif çözme belgesinin açıldığı depo yerinde stok yoksa, stokun olduğu depodan siparişin açıldığı depo yerine Stok Nakil
Siparişi (SNS) oluşturulacaktır.

4.1.1.

Sürece Genel Bakış

Müşteri ve malzeme ana verisinde emanet sürecinin yürütülmesi için bir gösterge olacaktır.
Kurumsal bayi satışları gibi teklif belgesi kullanılan satışlarda teklif belgesi üzerinde emanete alınabilirlik yönetilecektir.
Sipariş belgesi üzerinde kalem bazında emanet göstergesi (Z01) olacaktır.
Teslimat belgesi üzerinde başlık verilerinde emanet/fiktif göstergesi olacaktır.
Sipariş satırlarındaki emanet/fiktif göstergesi farklılaşması durumunda satırdaki göstergelere bakılarak birden fazla teslimat belgesi
yaratılacaktır. Ayrışan teslimatlar için teslimat başlığındaki emanet/fiktif göstergesi güncellenecektir.
601U emanet/fiktife alınan teslimatlar Ortec sistemine gönderilmeyecektir. Ortec'e gönderilen bir teslimat varsa iptal bilgisi
gönderilecektir ve teslimat Ortec'ten silinecektir.
MM'li depolarda emanet teslimatlarının mal çıkışı teslimat iş listesi üzerinden manuel olarak yapılacaktır.
EWM'li depolarda emanet teslimatlarının mal çıkış işlemleri EWM sisteminde yapılacaktır.
Emanet teslimatlarının mal çıkışının yapılmasından sonra veya faturalama işleminin yapılmasından sonra değersiz olarak yönetilecek
stok mal girişi yapılacaktır.
Emanet teslimatlarının değersiz stok mal girişi satış faturasına referanslı yapılacaktır.
Değersiz tarafta EWM ilişkili depolarda mal girişi teslimat üzerinden yapılacaktır ve EWM sisteme ilk değerli çıkış belgesiyle(601U
teslimatı) bu girişi eşleştirdiği (601E teslimatı) noktada mal çıkış ve mal giriş bilgilerini S4 sistemine gönderecektir.
Fiktiften emanete dönme kuralı sadece bayi kanalında işletilecektir.

4.1.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070050-01 Emanete alma süreci
SD070050-01 Emanete Alma Süreç Akışı Ekran Görüntüsü :

4.1.3.

Süreç Adımları

Emanet/ fiktife alma ve yansıtma süreç adımları aşağıdaki gibidir:

Süreç
Adım
No
1

Süreç Adımı

Sipariş açılırken emanet göstergesi belirlenir.

İşlem Kodu

Entegrasyon
Kaynak
Sistem

Job


<<< SAYFA 4 >>>
1.1

Bayi yönetmeni veya müşteri temsilcisi tarafından Mars sisteminde satış sipariş kaleminde emanet
göstergesi belirlenir.

Mars

1.2

Bayi yönetmeni veya müşteri temsilcisi tarafından SAP S/4 HANA sisteminde VA01 ekranından satış sipariş
kaleminde emanet göstergesi belirlenir.

VA01

1.3

SAP S/4 HANA sisteminde excel upload programı ile sipariş açılırken emanet göstergesi belirlenir.

ZSD_0013

2

Siparişin teslimat belgesi oluşturulur.

ZSD_0023

3

Toplu emanet/fiktif alma 601U işlemleri yürütülür.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri

ZSD_JOB
_VARY_1
ZASD:
SEVKIYA
TI_601
/ABCP

ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti
3.1

Sipariş açılırken emanet/fiktif göstergesi bulunmayan teslimatlar için depo kullanıcıları tarafından "fiktife al"
veya satış ekibi tarafından "emanet al" işlemleri yapılır.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

3.2

601U teslimatları emanet/fiktife alınırken işlemler otomatik yapılır.
Belge üzerinde emanet/fiktif göstergesi belirlenir.
Teslimatın çekmesi yapılır.
Teslimat EWM depo ise EWM sistemine dağıtılır.
Teslimat MM depo (Arbarkod/ Total depo) ise mal çıkışı yapılır.
Teslimatın faturası oluşturulur.

3.3

Teslimat Ortec ilişkili (teslimat başlığındaki teslimat nakliye planlama durumu= "90") ise;
Teslimat kalemindeki nakliye planlama statüsü "01"- Ortec'e henüz gönderilmeyen ve araç planı
yapılmayan teslimatlar emanet/fiktife alınır.
Teslimat kalemindeki nakliye planlama statüsü "03"- Ortec'e gönderilen ve araç planı yapılmayan
teslimatlar emanet/fiktife alınır. Ortec'e iptal bilgisinin gönderilmesi için nakliye planlama statüsü "05"b
elirlenir ve Ortec'ten teslimat silinir. İptal bilgisi gönderilen teslimatın nakliye planlama statüsü "03"olar
ak güncellenir.
Ortec'te araç planı yapılan teslimatlar emanet/fiktife alınamaz.

3.4

Teslimat belgesi üzerinde başlık verilerinde emanet/fiktif göstergesi manuel belirlenemez

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
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

3.5

ZS08 - Mağaza teslimatlarının fiktife alınmaması için ZSD_P_TOPLU_EMANET_FIKTIF programına
(ZSD_0034) kontrol eklenmiştir.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

3.6

Emanet/fiktife alınan teslimatların faturası oluşmadıysa "belgeleri işle" işlemi ile teslimatın tamamlanmayan
adımları otomatik job ile ya da manuel olarak kullanıcı tarafından yürütülür. Fatura adımı tamamlanan
teslimatlar ALV'den silinir. Belgelerin durumu "rapor" işleminden kontrol edilir.

ZSD_0034 Toplu emanet
/fiktif alma
601U işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

ZSD_JOB
_VARY_1
/ JOB:
601U:
Emanet
Belg.i
İşle
ZSD_JOB
_VARY_2
/ JOB:
601U:
Fiktif
Belg.i
İşle


<<< SAYFA 5 >>>
4

Toplu emanet/fiktif alma 601E işlemleri yürütülür.

ZSD_0002 Toplu emanet
/fiktif alma
601E işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

4.1

ZSD_0002 ekranında faturalar listelenir. 601E depo stoklarına giriş yapılması için aşağıdaki işlemler
otomatik yapılır.
İade sipariş belgesi oluşturulur.
İade teslimatı yaratılır.
601E depo stoklarına mal girişi yapılır. Her müşteri için oluşturulan emanet/fiktif PYP stokuna mal
girişi yapılır.
Belge fiktif ise (Z02) fiktif çözme belgesi oluşur.

ZSD_0002 Toplu emanet
/fiktif alma
601E işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

Örneğin; 24101335 müşteri koduna sahip bayi için 601E işlemleri yürütüldüğünde mal giriş adımında
emanet için E-0024101335 PYP stokuna fiktif için F-0024101335 PYP stokuna giriş yapılır.

ZSD_JOB
_VARY_1
JOB:
601E:
Emanet
Belg. İşle
ZSD_JOB
_VARY_2
JOB:
601E:
Fiktif
Belg. İşle

ZSD_0002 ekranı job veya manuel olarak kullanıcı tarafından yürütülür.
5

Yansıtma ekranından 601E depolar arası transfer işlemler yürütülür. Bu ekrandan SNS (stok nakil siparişi)
oluşturulur.

ZSD_0035 Yansıtma
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

5.1

Yansıtma ekranından önce yapılması gereken işlemler aşağıdaki gibidir. Bu işlemler Emanet/Fiktife Alma
ekranlarında 4.1 adımında yapılmış olacaktır.
Fiktif faturaları oluştuktan sonra emanet/fiktife alma ekranında 601E üretim yerinde;
İlgili depoya PYP öğesi ile müşteri ilişkili olarak stok girişi yapılacak.
Fiktif çözme belgesi oluşturulacaktır. Fiktif çözme belgesinde depo yeri matriste müşteri il/ilçe
kodu ve malzemede hedef grup bazında bulunan ilk depoya açılacaktır. (Bakım tablosu :
ZSD_T_EMA_LGOR_T)
Fiktif çözme belgesinin açıldığı depo yerinde stok yoksa, stokun olduğu depodan siparişin açıldığı
depoyerine Stok Nakil Siparişi (SNS) oluşturulacaktır.

ZSD_0002 Toplu emanet
/fiktif alma
601E işlemleri
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

Emanet faturaları oluştuktan sonra emanet/fiktife alma ekranında 601E üretim yerinde;
İlgili depoya PYP öğesi ile müşteri ilişkili olarak stok girişi yapılacak.
Bayi yönetmenleri tarafından müşteriden talep geldikçe Emanet Çözme Siparişleri
oluşturulacaktır. Emanet çözme belgesinde depo yeri matriste müşteri il/ilçe kodu ve malzemede
hedef grup bazında bulunan ilk depoya açılacaktır.
5.2

Yansıtma ekranından 3 farklı şekilde SNS yaratılır.
1. Çözme siparişi bağımsız yapılan yansıtma: Ekranın çalıştırıldığı depo yerinde müşteri PYP stokunda
olan ve hedef depoya sevk edilecek miktar belirlenerek SNS oluşturulur. Hedef depo yeri değiştirilerek
de ilgili depoya SNS oluşturulur.
2. Depo yeri bazında yansıtma: Emanet/fiktif çözme siparişlerinden yansıtılacak depo yeri bazında
kümülatif miktarı gösterir. Hedef depo yeri değiştirilerek de ilgili depoya SNS oluşturulur.
3. Sipariş bazında yansıtma: Emanet/fiktif çözme siparişleri listelenir. Sipariş bazında hedef depoya
yansıtma yapılır. Hedef depo yeri değiştirilerek de ilgili depoya SNS oluşturulur.

5.3

Emanet/fiktif çözme siparişlerinde matrisle belirlenen depo (hedef depo yeri) yerinde stok varsa yansıtma
ekranına düşmeyecektir.

ZSD_0035 Yansıtma
ZSD_0037 Ana menü Emanet/Fiktif
Kokpiti

ZSD_0023

Ürünün sevk edilmesi için deponun sevkiyat kokpitinde görünecektir ve teslimat belgesi oluşacaktır.
5.4

Yansıtma ekranından oluşan SNS belgelerine istinaden aşağıdaki işlemler sırasıyla yürütülür.

ZSD_0023

Sevkiyat kokpitinden STO( stok nakil teslimatı) oluşturulur.
Nakliye planması için STO belgeleri Ortec'e gönderilir.
Ürünler okutularak mal çıkışı yapılır.
Ürünleri teslim alan depo, giriş teslimat belgesi yaratır.
Okutma işlemlerinden sonra mal girişi yapılır.
5.5

Ürünler hedef depoya ulaştıktan ve 5.4 adımındaki mal girişi yapıldıktan sonra emanet/ fiktif çözme
siparişleri teyit alır.

V_V2

Bu işlem teyit programındaki (SDV03V02) job ile siparişlere teyit verilir.

6

5.

Emanet/ fiktif çözme siparişleri için teslimat yaratılır ve nakliye planlama sistemi olan Ortec'e dağıtılır.

ZSD_0023

Nakliye planlama süreçlerinin detayı linkinde Final_OTC-070-020 Nakliye planlama açıklanmaktadır.

ZSD_0001

Arçelik Entegrasyon Süreçlerine Uyum Detayları

ZSD_JOB
_VARY_1
JOB:
601E:
Sipariş
Terminle
me


<<< SAYFA 6 >>>
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

7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF Tipi

WRICEF Sorumlusu (Arçelik/SAP)

SATH-1991

Emanet ve Fiktife Alma SD043

Geliştirme

Aslıhan Türkmen

SATH-1993

Emanet / Fiktif süreci için User Exit'e kontrollerin eklenmesi - MM086

Geliştirme

Aslıhan Türkmen

SATH-1999

Yansıtma/Nakil Kokpiti ve Geliştirmeleri - SD043?

Geliştirme

Aslıhan Türkmen

CR
