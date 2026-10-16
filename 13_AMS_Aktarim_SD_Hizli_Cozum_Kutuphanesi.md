---
kaynak_dokuman: "Arçelik_AMS_Aktarim_SD_ASLIHAN.xlsx"
konu: "AMS devir dokümanı: iletişim matrisi, sevkiyat / emanet-fiktif / nakliye-Ortec hızlı çözüm kütüphanesi, sık ticket-hata vakaları"
bicim: xlsx
---

# Arçelik_AMS_Aktarim_SD_ASLIHAN.xlsx
## Sheet: Genel Bilgilendirme

GENEL BİLGİLENDİRME & İLETİŞİM REHBERİ
AMS destek sürecinde doğru kaynağa hızlı ulaşmak, talep kurallarını hatırlatmak ve konu bazlı doğru kişiye yönlenmek için hazırlanmıştır.
1. HIZLI ERİŞİM & ÇALIŞMA KURALLARI
Konu	Ne Yapılmalı?	Referans / Link	Talep Kimden Gelmeli?	Kontrol / Onay	Kritik Not	Durum	Anahtar Kelime
Jira Kullanımı	Ticket açma, takip ve dokümantasyon standardına göre ilerlenmeli.	Jira kullanım dokümanı	İlgili iş birimi / Arçelik IT	Ticket içeriği ve öncelik doğrulanmalı.	Çözüm, kök neden ve test sonucu ticket üzerinde iz bırakacak şekilde tutulmalı.	Aktif	Jira, ticket
Job Kurma	Yeni job veya job değişikliği yalnızca yetkili talep ve onay ile yapılmalı.	Paylaşılan Job Kurma dokümanı	Arçelik IT	Talep sahibi + kapsam + sistem + periyot doğrulanmalı.	Kullanıcıdan doğrudan gelen job talebiyle işlem yapılmamalı, Arçelik IT yönlendirmesi beklenmeli.	Aktif	job, SM36, SM37
Ana Veri Değişikliği	Önce problemin gerçekten ana veri kaynaklı olduğu doğrulanmalı, sonra ilgili ana veri sahibine yönlenilmeli.	İlgili ana veri dosyası / süreç dokümanı	İlgili iş birimi / Arçelik IT	Değişiklik yetkisi ve iş gerekçesi kontrol edilmeli.	Danışman doğrudan ana veri değiştirmek yerine süreç sahibini ve yetkili ekibi yönlendirmeli.	Aktif	müşteri, malzeme, fiyat
Dış Sistem / Entegrasyon	SAP tarafındaki belge ve entegrasyon logları kontrol edildikten sonra ilgili dış sistem sorumlusuna somut belge örneğiyle gidilmeli.	İlgili süreç sheet'i / entegrasyon logları	Arçelik IT / süreç sahibi	Belge no, tarih-saat, hata mesajı, sistem akışı hazırlanmalı.	'Çalışmıyor' yerine örnek belge + beklenen/gerçekleşen sonuç ile eskale edilmeli.	Aktif	MARS, SARIS, Ortec, Salesforce

2. KONU BAZLI İLETİŞİM MATRİSİ — KİME, NE ZAMAN GİDİLMELİ?
Ekip / Rol	Kişi	Uzmanlık / Sorumluluk	Hangi Konularda?	Ne Zaman İletişime Geçilmeli?	İletirken Hazır Olması Faydalı Bilgi	Öncelik	Not
Arçelik IT	Burak Aksoy	Arçelik IT / çözüm ekibi	IT sahipliği, yönlendirme, onay	Süreç sahibi veya karar/onay gereken konularda	Ticket no, örnek belge, beklenen sonuç	Ana	Talep edilen işler önceliklendirilmeli.
Arçelik IT	Hatice Ergör	Arçelik IT / çözüm ekibi	IT sahipliği, yönlendirme, onay	Süreç sahibi veya karar/onay gereken konularda	Ticket no, örnek belge, beklenen sonuç	Ana	Talep edilen işler önceliklendirilmeli.
Arçelik IT	Mehmet Ercan	Arçelik IT / çözüm ekibi	IT sahipliği, yönlendirme, onay	Kullanıcıların programdaki kontrollerden dolayı yürütemediği kritik işlemsel veri değişikliği/ debug change /tablo edit gereken konularda	Ticket no, örnek belge, beklenen sonuç	Ana
Danışman	Onur Türkeş	Çözüm Mimarı; genel süreç bilgisi	Tüm süreçler; özellikle Emanet/Fiktif ve Ortec	Kritik tasarım kararı, süreçler arası etki veya mimari yönlendirme gerektiğinde	Süreç akışı, örnek belge, mevcut analiz	Ana	Geniş süreç bilgisi
Danışman	Ayşegül Gürbüz	SD fonksiyonel	Emanet/Fiktif, satış-lojistik, genel SD, MARS, SARIS(Tüketici teslim süreçleri)	Fonksiyonel süreç analizi ve hata incelemesinde	Sipariş/teslimat/fatura no, hata, senaryo	Ana
Danışman	Serdar Kızıltuğ	SD / ticari süreçler	Fiyatlandırma, hakediş, WCOCO, prim, intercompany	Fiyat, prim, hakediş veya şirketler arası süreç sorunlarında	Belge no, koşul tipi, müşteri/malzeme	Ana
Danışman	Yücel Çetin	SD / Müşteri Hizmetleri 	Müşteri Hizmetleri ve SARIS	MH veya SARIS kaynaklı süreçlerde	Belge no, TH iş emri, hata mesajı	Ana
Danışman	Gökmen Altınel	Rapid / Salesforce / Workflow	Rapid, Salesforce teklif, workflow	Teklif, Rapid veya onay/workflow sorunlarında	Belge/teklif no, onay durumu, hata	Ana
Danışman	Tevfik Ünlüer	Rapid, D2D/H2O su arıtma sistemleri	Rapid stok transferi, su arıtma sistemleri	Mağazacılık stok transferi gereken durumlarda  Su arıtma ZSD_014 ekranı	Malzeme, kaynak/hedef depo, belge no	Ana
Proje Yönetimi	Ali Yılmaz	Çözüm ekibi proje yönetimi	Koordinasyon / öncelik / eskalasyon	Birden fazla ekibi ilgilendiren veya önceliklendirme gereken konularda	Ticket listesi, etki, aciliyet	Destek
Proje Yönetimi	Yasemin Yıldıztekin	Ana veri ve E-çözüm proje yönetimi	Ana veri / E-çözüm koordinasyonu	Koordinasyon veya sahiplik netleştirme gerektiğinde	Talep özeti, etkilenen süreç	Destek
Ana Veri	Barış Koyuncu	Malzeme ve fiyat ana verisi	Malzeme / fiyat ana veri	Ana veri eksikliği veya değişiklik ihtiyacında	Malzeme no, satış alanı, beklenen değer	Ana	Malzeme/fiyat ana veri ilgili listesi paylaşıldı. İlgili kişiye ulaşılamadığı durumda veya farklı bir durum olduğunda iletişime geçilmeli
Ana Veri	Yasemin Yıldıztekin	Ana veri koordinasyonu	Ana veri süreçleri	Ana veri sahipliği/koordinasyonu gerektiğinde	Talep özeti 	Destek
Ana Veri	Suat Uyar	Kredi Risk / müşteri ana verisi	Müşteri ana verisi / müşteri görünümü / kredi risk	Müşteri ana veri veya kredi risk bağlantılı konularda	Müşteri no, satış alanı, beklenen görünüm	Ana	Müşteri ana verisi SD görünümü "Hat sahibi" tarafından değiştirilir. Müşteri ana verisi ilişkili konularda fikir almak için Suat Bey ile görüşülebilir. 
Dış Sistem	Kübral Bahar / Tuğçe Gürsu	MARS	MARS entegrasyon ve ekranları	MARS tarafında kayıt/entegrasyon problemi olduğunda	SAP belge no + MARS ekranı/hata + tarih/saat 	Ana
Dış Sistem	Elif Melis Geçginci	Ortec / Lojistik	Nakliye planlama ve Ortec	Ortec'e gönderim, iptal, araç planı vb. sorunlarda	Teslimat no, nakliye statüsü, tarih-saat	Ana
Dış Sistem	Yasemin Oğuz Topaloğlu	Salesforce	Salesforce teklif süreci ve müşteri ana veri süreci	Teklif/entegrasyon kaynaklı sorunlarda	Teklif no, müşteri, hata/ekran görüntüsü	Ana
Dış Sistem	Sami Tetik / Serdar Uysal	SARIS / Müşteri Hizmetleri	SARIS entegrasyonu ve MH	SARIS servis ataması, TH iş emri, MH entegrasyonunda	Sipariş no, TH iş emri, hata mesajı	Ana
3. ESKALASYON ÖNCESİ MİNİ CHECKLIST
#	Kontrol	Neden?	Hazır Edilecek Bilgi	Tamamlandı?
1	Örnek belge mevcut mu?	Sorunun tekrar üretilebilir ve somut olması için	Sipariş / teslimat / fatura / ticket no
2	Hata mesajı veya ekran görüntüsü var mı?	Teknik ve fonksiyonel ayrımı hızlandırır	Tam hata metni + ekran görüntüsü
3	Beklenen ve gerçekleşen sonuç net mi?	Yanlış anlaşılmayı önler	1-2 cümlelik senaryo açıklaması
4	SAP tarafı kontrol edildi mi?	Dış sisteme gereksiz eskalasyonu önler	Belge akışı, statü, job/log sonucu
5	Doğru süreç sahibine mi gidiliyor?	Çözüm süresini kısaltır	Yukarıdaki iletişim matrisi

## Sheet: Sevkiyat Planlama

SEVKİYAT PLANLAMA (TESLİMAT OLUŞTURMA / ÇEKME / MAL ÇIKIŞI | AMS HIZLI ÇÖZÜM KÜTÜPHANESİ
Süreç dokümanının yerine geçmez; ticket geldiğinde süreç, işlem kodu, kritik kontrol ve çözüm yoluna hızlı ulaşmak için hazırlanmıştır.
1. 30 SANİYEDE SÜREÇ ÖZETİ
Süreç	Ne Zaman Kullanılır?	Temel Akış	Kritik Kural	Ana İşlem Kodları	Çıktı / Sonuç	İlgili Sistem
Manuel Teslimat	İstisnai süreçler / MH	VL01N/VL10C ile teslimat oluşturulur.	AATP olmayan süreçler	VL01N, VL10C	Teslimat	SAP
Otomatik Teslimat	Açık ve teyitli sipariş	Job ile oluşur	Kredi+teslimat blokajı olmamalı	ZSD_0023	Teslimat	SAP
Sevkiyat Kokpiti	Açık sipariş	Teyitli siparişler listelenir	Teyitsiz sipariş görünmez	ZSD_0023	Teslimat	SAP
MH Yedek Parça	Web/Servis	Job ile oluşur	Önceliklendirme	VL10C/ZSD_0033	Teslimat	SAP
Door to Door	D2D	ZSD_0014	Ortec ilişkisi yok	ZSD_0014	Teslimat	SAP
MM Depo Çekme	Teslimat oluşturulduktan sonra ürünlerin fiziksel olarak toplanması gerektiğinde	Terminal → Arbarkod / Total → SAP Güncelleme	Seri no ve çekme bilgisi eksiksiz SAP'ye aktarılmalıdır.	ZSD_PICK_VIEW4, SDPICK, VL02N, VL06O	Çekme Tamamlandı	SAP, Arbarkod, Total Depo
EWM Depo Çekme	EWM depolarda çekme süreci gerektiğinde	ZSD_0001 → EWM → Çekme → SAP	Teslimat EWM'e dağıtıldıktan sonra değiştirilemez.	ZSD_0001	Çekme Tamamlandı	SAP, EWM
MM Depo Mal Çıkışı	Çekme tamamlandıktan sonra sevkiyatın tamamlanması için	Çekme → Mal çıkışı → e-İrsaliye → Ortec Realizasyon	Çekme tamamlanmadan mal çıkışı yapılamaz.	VL02N, VL06O	Mal Çıkışı	SAP
EWM Depo Mal Çıkışı	EWM depolarda mal çıkışı gerektiğinde	EWM Mal çıkışı→ SAP → e-İrsaliye	Mal çıkışı EWM üzerinden gerçekleştirilir.	EWM	Mal Çıkışı	SAP, EWM
2. İŞLEM KODU / PROGRAM HIZLI REFERANS
Kod	Ekran / Program	Ne İçin Kullanılır?	Kritik Not	Süreç	Job / Fonksiyon / IDOC
ZSD_0023	Sevkiyat Kokpiti	Teslimat oluşturma	Teyitli sipariş	Sevkiyat	ZASD:SEVKIYATI_601/ABCP
VL01N	Teslimat	Manuel teslimat	Referanssız	Manuel	-
VL10C	Teslimat Listesi	MH süreçleri	YP/Ürün değişimi	MH	Job
ZSD_0014	D2D	Door to Door	D2D	D2D	-
ZSD_0033	Yeniden terminleme	YP öncelik	MH	MH	-
ZASD:601S WEB YP DELIVERY	Job	Web YP	Otomatik	MH	Job
VL02N	Çekme Bilgisi Görüntüleme	Terminalden girilen teslimat/araç bilgilerinin SAP'den okunması	Terminal ilk olarak bu FM ile teslimat bilgisini çeker.	Çekme	ZSD_PICK_VIEW4
VL02N	Arbarkod Teslimat Servisi	Teslimat bilgilerinin Arbarkod terminaline gönderilmesi	Teslimat ve kamyon id Arbarkod'a gönderilir.	Çekme	FM
VL02N	Arbarkod Güncelleme	Çekme ve seri numarası bilgilerinin SAP'ye aktarılması	Çekme tamamlandıktan sonra çalışır.	Çekme	FM
ZSD_0001	Ortec / EWM Entegrasyon Kokpiti	Lotus gönderimi, EWM dağıtımı ve teslimat entegrasyon işlemleri	Ortec ve EWM dağıtım işlemlerinin ana ekranıdır.	Nakliye / Çekme	Manuel
VL02N	Teslimat Değiştir	Tek teslimat için mal çıkışı yapılması	Tek teslimat bazlı kullanılır.	Mal Çıkışı	-
VL06O	Toplu Mal Çıkışı	Araç bazlı toplu mal çıkışı yapılması	Toplu mal çıkışı için kullanılır.	Mal Çıkışı	-
VL02N	IDoc	Çekme bilgilerinin SAP'ye aktarılması	Başarısız IDoc'lar teslimatın güncellenmesini engeller.	Çekme	IDOC: SDPICK
ZSD_0001	Job	Ortec ilişkisiz teslimatların otomatik EWM'e dağıtılması	Sadece Ortec ilişkisiz teslimatlar için çalışır.  Ortec ilişkili teslimatlar kullanıcı tarafından manuel olarak ZSD_0001 ekranından işlem tipi "EWM'e Dağıt" ile dağıtılır.	EWM	ZASD:ORTEC_TESLIMAT_EWM_DGTM
3. SIK GELEN TICKET / HATA CASE KÜTÜPHANESİ
ID	Kullanıcı Sorusu / Semptom	Çözüm / Aksiyon	İşlem Kodu	Eskalasyon	Anahtar Kelimeler	Kaynak
	Sipariş kokpitte görünmüyor	Siparişte teyit, kredi blokajı ve teslimat blokajı kontrol edilir.   601U üretim yeri siparişinde teyit yoksa sipariş AATP modülüne yönlendirilir.  601E üretim yeri siparişinde teyit yoksa ZMM_0091 raporu kontrol edilir.   Blokaj varsa kaldırıldıktan sonra kokpit tekrar kontrol edilir.	VA02 / ZSD_0023 / ZMM_0091	SD / AATP	Teyit yok, kredi blokajı, teslimat blokajı
	Teslimat otomatik oluşmadı	Job logu kontrol edilir. Siparişin varyant kapsamına girip girmediği ve teslimat blokajı olmadığı doğrulanır.	SM37 / ZSD_0023	SD / Basis	Job, varyant, otomatik teslimat
	D2D teslimatı oluşmadı	Sipariş  ZSD_0014 D2D kokpitinden manuel teslimata çevrilir. Bu süreç Ortec-Lotus entegrasyonuna dahil değildir.	ZSD_0014	SD	D2D, Door to Door
	Ortec'e gitmedi	Teslimatta blokaj olup olmadığı, teslimat başlığında emanet göstergesi olup olmadığı ve ZSD_T_DLV_CONFIG bakım tablosundaki Ortec parametreleri kontrol edilir. Kargo veya D2D süreçlerinde Ortec entegrasyonu beklenmez.	VL02N / ZSD_T_DLV_CONFIG	SD / Ortec	Ortec, Lotus, blokaj
	Birleştirme olmadı	Malı teslim alan, sevkiyat noktası ve birleştirme göstergesi kontrol edilir. Varyant dışında kalan kanallar için manuel teslimat oluşturulur.	ZSD_0023	SD	Birleştirme, sevkiyat noktası
	Birleştirme oldu	601C GR kanalındaki Koçtaş, Medimarkt gibi müşteriler için 1 sipariş- 1 teslimat kuralı vardır. Siparişler tek teslimatta birleştiğinde müşteriler ürünleri geri göndermektedir.  Siparişte ve ana veride birleştirme indikatörü boş olmalıdır.	BP / VA02	SD	Birleştime, hatalı irsaliye
	Teslimat EWM'ye dağıtılamıyor	Teslimatta araç ID (LIKP-LIFEX) kontrol edilir. Ortec ilişkili teslimatlar manuel, ilişkisiz teslimatlar job ile dağıtılır. Job logları kontrol edilir.	ZSD_0001	SD / EWM	EWM, LIFEX, Dağıtım	Çekme
	Terminal teslimatı göremiyor	Terminalden girilen araç numarası / teslimat numarası kontrol edilir. ZSD_PICK_VIEW4 fonksiyonunun doğru veri döndürdüğü doğrulanır.	ZSD_PICK_VIEW4	MM	Terminal, Arbarkod, Total	Çekme
	Çekme SAP'ye yansımadı	SDPICK IDoc kontrol edilir. IDoc hata aldıysa hata giderilip tekrar işlenir.	WE02 / WE05	MM / Basis	SDPICK, IDoc, Picking	Çekme
	Seri numarası teslimata yazılmadı	Arbarkod / Total sisteminde okutma yapıldığı doğrulanır. Seri numarası entegrasyonu kontrol edilir.	VL02N	MM / SD	Seri No, IMEI; Mali ID	Çekme
	Mal çıkışı yapılamıyor	Çekme tamamlanmış mı, seri numarası eksiksiz mi kontrol edilir. Tek teslimat için VL02N, toplu araç çıkışı için VL06O kullanılır.	VL02N / VL06O	SD	Mal Çıkışı	Mal Çıkışı
	E-İrsaliye oluşmadı	E-çözümlere iletilir. Öncesinde teslimat aşağıdaki konula için analiz edilir.  Mal çıkışının başarılı olduğu doğrulanır.  Müşteri ana verisinde VKN bilgisi kontrol edilir. Boş olduğunda teslimat entegratöre gönderilemedi hatası alır.	VL03N / ZCZM_EDM	SD / e-İrsaliye	e-İrsaliye	Mal Çıkışı
	Teslimat üzerinde değişiklik yapılamıyor	Teslimatın EWM'ye dağıtılıp dağıtılmadığı kontrol edilir. EWM'ye dağıtılan teslimatlar SAP üzerinden değiştirilemez.	ZSD_0001	SD / EWM	EWM	Çekme
	6009 depo yeri teslimatı iptal edilemiyor.	AATP 601U siparişlerinde depo yerini 6009 kullanılmayan hatalı depo belirlemektedir. EWM depo olduğu için teslimat sıfırlandıktan sonra VL_COMPLETE işlem kodundan tamamlanmalıdır.	VL02N / VL_COMPLETE	SD	6009 depo yeri teslimat iptali

4. YENİ TICKET EKLEME ŞABLONU — YAŞAYAN KÜTÜPHANE
Ticket No	Tarih	Kısa Başlık	Semptom / Kullanıcı Talebi	Kök Neden	Çözüm Adımları	İşlem Kodu / Tablo	İlgili Kişi	Etiket

5. KRİTİK KONTROL LİSTESİ
Kontrol	Neden Önemli?	Nereden?	Beklenen / Kural
Ortec araç planı	Araç planı işlemi engeller.	Nakliye statüleri	Araç planı yapılmış teslimat emanet/fiktife alınamaz.
601U tamamlanma	Zincir yarım kalabilir.	ZSD_0034	Eksik adım job veya manuel işletilir.
601E / PYP	Çözme/sevk için temeldir.	ZSD_0002	E- emanet, F- fiktif müşteri PYP stoğu.
Çözme onayı	Onaysız belge teslimata dönüşmez.	ZSD_0039	Bayi açtıysa onay; bayi yönetmeni açtıysa onaya düşmez.  S4 kullanan kullancılar ZSD_0022 ekranından default "müdür onayı" ile emanet çözme siparişlerini oluşturur.
Yetkili servis Z3	Servisli teslimatı etkiler.	Sipariş / SARIS	Gereken senaryoda Z3 olmadan teslimat yaratılamaz.
Araç ID (LIFEX)	EWM dağıtımı ve nakliye planı için zorunludur.	LIKP-LIFEX	Ortec ilişkili teslimatlarda araç planı tamamlanmadan süreç ilerlememelidir.
Seri No / IMEI okutuldu mu?	Mal çıkışı ve e-İrsaliye için zorunludur.	Arbarkod / Total	Seri numarası eksiksiz olarak teslimata aktarılmış olmalıdır.
Araç üzerindeki tüm teslimatlar mal çıkışı oldu mu?	Ortec realizasyonu toplu gönderilir.	Ortec / ZSD_0001	Aynı araçtaki tüm teslimatlar tamamlandıktan sonra realizasyon gönderilir.

## Sheet: Emanet-Fiktif-Yansıtma

EMANET – FİKTİF | AMS HIZLI ÇÖZÜM KÜTÜPHANESİ
Süreç dokümanının yerine geçmez; ticket geldiğinde süreç, işlem kodu, kritik kontrol ve çözüm yoluna hızlı ulaşmak için hazırlanmıştır.
1. 30 SANİYEDE SÜREÇ ÖZETİ
Süreç	Ne Zaman Kullanılır?	Temel Akış	Kritik Kural	Ana İşlem Kodları	Çıktı / Sonuç	İlgili Sistem
Emanete Alma	Ürün faturalanır ancak müşteri adına depolanmaya devam eder.	Sipariş → Teslimat → 601U → Fatura → 601E/PYP → talepte çözme	Müşteri ve malzemede emanet alınabilir göstergesi olmalı; 601U emanet/fiktif teslimatlar Ortec'e gönderilmez.	VA01, ZSD_0013, ZSD_0023, ZSD_0034, ZSD_0002	E- müşteri PYP stokuna giriş	S/4, MARS, EWM/MM, Ortec
Fiktife Alma	Mal gönderilmeden fatura önceden kesilir.	Teslimat → ZSD_0034 → 601U/fatura → 601E/F-PYP → çözme	16 gün içinde sevk; aşılırsa bayi kanalında otomatik emanete dönüş. Cep telefonu ve yazar kasa (pompa hariç) fiktife alınmaz.	ZSD_0034, ZSD_0002, ZSD_0059	F- müşteri PYP stokuna giriş + çözme belgesi	S/4, EWM/MM, Ortec
Emanet Çözme	Emanetteki ürün sevk edilecekse.	MARS/ZSD_0022 → onay → ZSD_0023 → Ortec → çekme → mal çıkışı	Bayi oluşturursa onay; bayi yönetmeni oluşturursa onaya düşmez. Onaysız belgede teslimat blokajı vardır.	ZSD_0022, ZSD_0039, ZSD_0023, ZSD_0030	Çözme siparişi ve sevk teslimatı	MARS, S/4, SARIS, Ortec
Yansıtma	Hedef depoda stok yoksa 601E depolar arası transfer.	ZSD_0035 → SNS → STO → Ortec → çıkış/giriş → V_V2 → çözme teslimatı	Hedef depoda stok varsa yansıtma ekranına düşmez; sevkiyat kokpitinden devam eder.	ZSD_0035, ZSD_0023, V_V2	Stok hedef depoya taşınır, sipariş teyit alır	S/4, Ortec, EWM/MM
2. İŞLEM KODU / PROGRAM HIZLI REFERANS
Kod	Ekran / Program	Ne İçin Kullanılır?	Kritik Not	Süreç	Job / Fonksiyon
ZSD_0001	Ortec / EWM Entegrasyon Kokpiti	Ortec gönderimi, EWM dağıtımı, realizasyon ve tekrar gönderim işlemleri	Nakliye planlamasının ana ekranıdır. Status 01 ve 04 teslimatlar listelenir.	Nakliye Planlama	Manuel / Job
ZSD_T_DLV_CONFIG	Teslimat Konfigürasyonu	Teslimatın Ortec ilişkili olup olmadığını belirler.	LFART + VKORG + VSTEL (+ Muhatap Türü) kombinasyonu kontrol edilir.  ZFLX(mağaza flextra) belge türü için ekstra muhatap türü de kontrol edilir. (VSTEL *F ile biten bpkind kontrol edilir.)	Konfigürasyon	Bakım Tablosu
ZSD_T_ORD_PRIORI	Ortec Öncelik Tanımı	Teslimatlara araç planı yapılırken Ortec'te sevk etme öncelikleri gönderilir.   Sevkiyat nok., sevkiyat türüne (tüketici teslim/doğrudan teslim) göre öncelik belirlenir.  600 - Yüksek öncelikli  1000 - Normal 	Priority eksikse teslimat Ortec'e gönderilemez.	Konfigürasyon	Bakım Tablosu
ZSD_0021	Müşteri Gönderim Programı	Müşteri ana verisini Ortec'e gönderir.	IT tarafından manuel tetiklenebilir. Müşteri Ortec'te eksikse entegrasyon tetiklenir.  Müşteri adres verisinde değişiklik yapıldıysa sadece değişiklikler Ortec'e gönderilir. Bunun için job kurulmuştur.	Müşteri Entegrasyonu	Job
ZSD_T_ORT_BPKND	Muhatap Türü Mapping	SAP muhatap türünü Ortec formatına dönüştürür.	Mapping eksikse müşteri gönderimi başarısız olur.	Konfigürasyon	Bakım Tablosu
ZSD_T_ORT_CTYDSC	İl Dönüşüm Tablosu	İl bilgisini Ortec formatına dönüştürür.	İstanbul Anadolu / Avrupa ayrımı bu tablodan yapılır.	Konfigürasyon	Bakım Tablosu
ZSD_T_VEHICLE	Araç Başlık Bilgileri	Araç planı bilgilerini saklar.	Ortec'ten gelen araç bilgileri burada tutulur.  E-irsaliye'ye konu olcak bazı alanlar bu tabloda tutulur. 	Araç Planlama	Tablo
ZSD_T_VEHICLE_IT	Araç Kalem Bilgileri	Araç planlanan teslimat kalemlerini saklar.	Ayrıştırma, iptal ve entegrasyon statusleri buradan takip edilir.  STATUS='02' ise tekrar gönderim job'ı çalıştırılmalıdır.	Araç Planlama	Tablo
ZSD_T_SPLIT	Teslimat Bölme Takibi	Kalem bölme kayıtlarını izler.	STATUS='02' ise tekrar gönderim job'ı çalıştırılmalıdır.	Kalem Bölme	Tablo
LIKP-LIFEX	Harici Teslimat (Araç ID)	Araç planı bilgisini teslimatta gösterir.	LIFEX doluysa teslimat araç planına alınmıştır.	Araç Planlama	Teslimat Alanı
3. SIK GELEN TICKET / HATA CASE KÜTÜPHANESİ
ID	Kullanıcı Sorusu / Semptom	Olası Neden	İlk Kontrol	Çözüm / Aksiyon	İşlem Kodu	Eskalasyon	Anahtar Kelimeler	Kaynak
	Teslimat ZSD_0001 ekranında görünmüyor.	Teslimat Ortec ilişkili değildir veya statü 01/04 değildir.	ZSD_T_DLV_CONFIG ve nakliye statüsü kontrol edilir.	Ortec ilişkisi ve teslimat statüsü doğrulanır.	ZSD_0001	SD	Ortec, nakliye planlama statüsü	Final_Completed_OTC-070-020 Nakliye planlama
	Teslimat Ortec'e gönderilemiyor.	Teslimatta zorunlu alan eksiktir.	Status 04 ve hata mesajı kontrol edilir.	Eksik alan tamamlanıp ZSD_0001'den tekrar gönderilir.	ZSD_0001	SD	Ortec, Lotus, nakliye planlama statüsü	Final_Completed_OTC-070-020 Nakliye planlama
	Teslimat Status 04'te kaldı.	Adres, Order Kind veya Priority bilgisi eksiktir.	Nihai adres, ZSD_T_DLV_CONFIG ve ZSD_T_ORD_PRIORI kontrol edilir.	Eksik konfigürasyon tamamlanıp tekrar gönderim yapılır.	ZSD_0001	SD / Ana veri	Nakliye planlama statüsü 04, Order Kind	Final_Completed_OTC-070-020 Nakliye planlama
	Teslimat Ortec'e gitmiyor, ZSD_0001 ekranında görünmüyor.	Emanet/Fiktif, blokaj veya miktar sıfırdır.  Araç planlamasının yapılmaması için Ortec'e gönderilmez.	Teslimat blokajı, emanet göstergesi ve miktar kontrol edilir.	Alanlar kontrol edilir. Blokaj veya emanet göstergesi kaldırılırsa teslimat tekrar gönderilir.	VL03N / ZSD_0001	SD	Blokaj, Emanet, Miktar sıfır	Final_Completed_OTC-070-020 Nakliye planlama
	Teslimatta emanet/fiktif göstergesi / blokaj eklendi veya teslimat miktarı sıfırlandı. Ortec'te teslimat görünüyor.	Eğer araç planlaması yapılmamışsa Ortec'ten silinmesi için cancel jobı çalışır.(ZSD_0001 programının arkasına kurulan job)  Araç planlaması yapılmışsa LIFEX alanı doludur. Cancel işlemi yapılamaz, teslimat değişikliğe kapanır.	Teslimat blokajı, emanet göstergesi ve miktar kontrol edilir.	Job kontrol edilir.	VL03N / ZSD_0001	SD	Blokaj, Emanet	Final_Completed_OTC-070-020 Nakliye planlama
	Teslimat sıfırlanırken yerel depo hatası alınıyor.	EWM ilişkili teslimatlarda (LIKP-LGNUM dolu ise) teslimat iptal edilirken miktar 0 yapılıp kaydedilir. Sonrasında VL_COMPLETE işlem kodundan teslimat tamalanır. (Mal çıkışı=C yapılır.)  MM ilişkili teslimatlarda 
	Müşteri Ortec'e gönderilemiyor.	Muhatap türü veya il dönüşümü eksiktir.	ZSD_T_ORT_BPKND ve ZSD_T_ORT_CTYDSC kontrol edilir.	Eksik mapping tamamlanır, müşteri tekrar gönderilir.	ZSD_0021	Master Data	BPKND, City Mapping	Final_Completed_OTC-070-020 Nakliye planlama
	Araç planı SAP'ye gelmedi.	Ortec entegrasyonu tamamlanmamıştır.	ZSD_T_VEHICLE ve ZSD_T_VEHICLE_IT kayıtları kontrol edilir.	Entegrasyon logları incelenir.	SE16N	Ortec	LIFEX, Vehicle	Final_Completed_OTC-070-020 Nakliye planlama
	Araç ID (LIFEX) boş görünüyor.	Araç planı henüz oluşmamıştır veya iptal edilmiştir.	LIKP-LIFEX alanı kontrol edilir.	Araç planı tamamlandıktan sonra teslimat yeniden kontrol edilir.	VL03N	Ortec	LIFEX	Final_Completed_OTC-070-020 Nakliye planlama
	Ayrıştırılan teslimat Ortec'e gitmedi.	Entegrasyon STATUS='02' olarak kalmıştır.	ZSD_T_VEHICLE_IT STATUS alanı kontrol edilir.	"Teslimat Ayrıştırma Gönderme" job'ı çalıştırılır.	ZSD_0001	SD / Basis	Ayrıştırma, STATUS02	Final_Completed_OTC-070-020 Nakliye planlama
	Bölünen teslimat Ortec'e gitmedi.	Kalem bölme entegrasyonu başarısız olmuştur.	ZSD_T_SPLIT STATUS alanı kontrol edilir.	"Kalem Bölme Gönderme" job'ı çalıştırılır.	ZSD_0001	SD / Basis	Split, STATUS02	Final_Completed_OTC-070-020 Nakliye planlama
	Teslimat EWM'ye dağıtılamıyor.	Ortec ilişkisine göre yanlış dağıtım yapılmaktadır.	LIFEX ve Ortec ilişkisi kontrol edilir.	Ortec ilişkili teslimatlar manuel, ilişkisiz teslimatlar otomatik dağıtılır.	ZSD_0001	SD / EWM	EWM, LIFEX	Final_Completed_OTC-070-020 Nakliye planlama
	Araç planı değiştirilemiyor.	Teslimat PGI olmuş, EWM'ye dağıtılmış veya kilitlenmiştir.	PGI, EWM ve lock durumu kontrol edilir.	Değişiklik engeline neden olan durum kaldırılmalıdır.	VL03N	SD / EWM	Lock, PGI	Final_Completed_OTC-070-020 Nakliye planlama
	Realizasyon Ortec'e gitmedi.	Araç üzerindeki tüm teslimatlar tamamlanmamıştır.	PGI ve e-İrsaliye durumu kontrol edilir.	Tüm teslimatlar tamamlandıktan sonra "Yükleme Tamamlandı" gönderimi yapılır.	ZSD_0001	SD	Status06, Realizasyon	Final_Completed_OTC-070-020 Nakliye planlama

4. YENİ TICKET EKLEME ŞABLONU — YAŞAYAN KÜTÜPHANE
Ticket No	Tarih	Kısa Başlık	Semptom / Kullanıcı Talebi	Kök Neden	Çözüm Adımları	İşlem Kodu / Tablo	İlgili Kişi	Etiket

5. KRİTİK KONTROL LİSTESİ
Kontrol	Neden Önemli?	Nereden?	Beklenen / Kural
Müşteri/malzeme uygunluğu	İşlem başında bloklanmanın ana nedenlerinden.	Ana veri	Emanet/fiktif gösterge işaretli olmalı; WEB/personel kanalları uygun değildir.  Malzeme: PRAT1-Emanet alınabilir  PRAT2-Fiktif alınabilir  Müşteri: KATR1-Emanet alınabilir  KATR3-Fiktif alınabilir
Ortec araç planı	Araç planı işlemi engeller.	Nakliye statüleri	Araç planı yapılmış teslimat emanet/fiktife alınamaz.
601U tamamlanma	Zincir yarım kalabilir.	ZSD_0034	Eksik adım job veya manuel işletilir.
601E / PYP	Çözme/sevk için temeldir.	ZSD_0002	E- emanet, F- fiktif müşteri PYP stoğu.
Çözme onayı	Onaysız belge teslimata dönüşmez.	ZSD_0039	Bayi açtıysa onay; bayi yönetmeni açtıysa onaya düşmez.  S4 kullanan kullancılar ZSD_0022 ekranından default "müdür onayı" ile emanet çözme siparişlerini oluşturur.
Yetkili servis Z3	Servisli teslimatı etkiler.	Sipariş / SARIS	Gereken senaryoda Z3 olmadan teslimat yaratılamaz.

## Sheet: Nakliye Planlama-Ortec

EMANET – FİKTİF | AMS HIZLI ÇÖZÜM KÜTÜPHANESİ
Süreç dokümanının yerine geçmez; ticket geldiğinde süreç, işlem kodu, kritik kontrol ve çözüm yoluna hızlı ulaşmak için hazırlanmıştır.
1. 30 SANİYEDE SÜREÇ ÖZETİ
Süreç	Ne Zaman Kullanılır?	Temel Akış	Kritik Kural	Ana İşlem Kodları	Çıktı / Sonuç	İlgili Sistem
Ortec'e Gönderim	Ortec ilişkili teslimat oluşturulduğunda	Teslimat → ZSD_0001 → Ortec → Status 01→02→03	Teslimatın Ortec ilişkisi ZSD_T_DLV_CONFIG tablosuna göre belirlenir.  ZSD_IF_MV50AFZ1~SAVE_DOCUMENT_PREPARE  ZSD_T_DLV_CONFIG tablosunda ilgili LFART + VKORG + VSTEL kombinasyonu mevcut ise teslimat Ortec ilişkili olur.	ZSD_0023, ZSD_0001	Teslimat Ortec'e gönderilir.	S/4, Ortec
Araç Planlama	Teslimatlar sevk aracına atanacaksa	Ortec → Araç Planı → SAP → LIFEX güncelleme	Araç planı sonrası teslimata Araç ID (LIKP-LIFEX) yazılır.	ZSD_0001	Araç bilgisi teslimata aktarılır.	S/4, Ortec
Kalem Ayrıştırma	Teslimatın yalnızca bazı kalemleri araca atanacaksa	Ortec → Ayrıştırma → Yeni Teslimat → SAP	Yeni teslimat oluşur, araç planlı teslimatta LIFEX dolu olur.	ZSD_0001	Yeni teslimat oluşturulur.	S/4, Ortec
Kalem Bölme	Araç kapasitesi yetersiz olduğunda	Ortec → Bölme → SAP → Yeni Teslimat	Bölünen miktar için yeni teslimat oluşturulur ve Ortec'e gönderilir.	ZSD_0001	Bölünmüş teslimatlar	S/4, Ortec
EWM Dağıtımı	Araç planı tamamlanan EWM teslimatlarında	Ortec → ZSD_0001 → EWM	Ortec ilişkili teslimatlar manuel, ilişkisiz teslimatlar otomatik dağıtılır.	ZSD_0001	Teslimat EWM'ye aktarılır.	S/4, EWM
Realizasyon	Mal çıkışı ve e-İrsaliye tamamlandıktan sonra	Mal çıkışı → e-İrsaliye → Ortec	Araç üzerindeki tüm teslimatlar tamamlanmadan realizasyon gönderilmez.	ZSD_0001	Teslimat nakliye planlama statü 06 olarak güncellenir.	S/4, Ortec
2. İŞLEM KODU / PROGRAM HIZLI REFERANS
Kod	Ekran / Program	Ne İçin Kullanılır?	Kritik Not	Süreç	Job / Fonksiyon

3. SIK GELEN TICKET / HATA CASE KÜTÜPHANESİ
ID	Kullanıcı Sorusu / Semptom	Çözüm / Aksiyon	İşlem Kodu	Eskalasyon	Anahtar Kelimeler	Kaynak
	... Numaralı malzemenin Ortec'e gönderimi tamamlanmadı	ECC -> Ortec malzeme aktarımı	Ortec	Elif Melis Geçginci	Malzeme gönderimi	Ortec, ECC

3. SIK GELEN TICKET / HATA CASE KÜTÜPHANESİ
ID	Kullanıcı Sorusu / Semptom	Olası Neden	İlk Kontrol	Çözüm / Aksiyon	İşlem Kodu	Eskalasyon	Anahtar Kelimeler	Kaynak

4. YENİ TICKET EKLEME ŞABLONU — YAŞAYAN KÜTÜPHANE
Ticket No	Tarih	Kısa Başlık	Semptom / Kullanıcı Talebi	Kök Neden	Çözüm Adımları	İşlem Kodu / Tablo	İlgili Kişi	Etiket

5. KRİTİK KONTROL LİSTESİ
Kontrol	Neden Önemli?	Nereden?	Beklenen / Kural

## Sheet: Hat Yapısı

## Sheet: Sheet1

	ZSD_IF_MV50AFZ1~SAVE_DOCUMENT_PREPARE
	ZSD_T_DLV_CONFIG

## Sheet: Issue Check List

Kaynak	Hata Tanımı	Aksiyon	Sorumlu	Diş sistem sorumlu	Ref.Çağrı
Ortec	... Numaralı malzemenin Ortec'e gönderimi tamamlanmadı	Ortec'e malzeme veri aktarımı ECC'den yapılmaktadır. 		Elif Melis Geçginci	[SM-2102090] Safir ekibine - ZSD_0001 Ekranındaki hatalı kayıt - Digiport
S4	Alacak dekontu eşleşmesi tamamlanmıyor	ZSD_0047 ekranından kontrol edilir. Genelde V.D. - Vergi numarası uyuşmazlıkları kaynaklı olabilir	Kübra Sevindir