---
kaynak_dokuman: "Arçelik_SD_SAP_Faturalama_Muhasebeleşme_Hata_Katalogu_20260616.docx"
konu: "VF04 / VFX3 faturalama ve muhasebeleşme hata kataloğu (16.06.2026)"
bicim: docx
---

# Arçelik_SD_SAP_Faturalama_Muhasebeleşme_Hata_Katalogu_20260616.docx
**SAP SD / FI FATURALAMA SÜREÇLERİ ve HATA KATALOĞU**

Bu kılavuz, **Arçelik** kullanıcılarının **VF04 (Toplu Faturalama)** ve **VFX3 (Bloke Faturalar)** işlemlerini anlatmak ve işlem sırasında **en sık karşılaştığı** SD-FI entegrasyon hatalarını çözüme kavuşturmak amacıyla hazırlanmıştır. Doküman kapsamında; standart ve şirkete özel (Z'li) hata kodları, bu hataların kök nedenleri, adım adım fonksiyonel çözüm yolları ve sürecin muhatabı olan sorumlu ekipler yapılandırılmış bir formatta sunulmaktadır.

**VF04 ****- ****Faturalama İş Havuzu**

Müşteriye gönderimi tamamlanan **sevkiyatların** veya tamamlanan **hizmetlerin** satış faturasına dönüştürülmek üzere bekletildiği operasyonel iş havuzudur.

**VF****X3**** ****– ****Fatura**** Sonrası**

SD faturası başarıyla kesilmiş ancak teknik/fonksiyonel hatalar nedeniyle finans (FI) modülüne ve muhasebe kayıtlarına aktarılamamış bloke belgelerdir.

|  | **NEDEN ?** **Gizli Ciro Tehditi : **VFX3 listesinde bekleyen her fatura, müşteriye mal gitmiş olsa dahi resmi mizanlarda ve gelir tablosunda ****ciro olarak yer almaz**.**** ** **Dönemsellik : **Ocak ayında teslim edilen malın gelirinin Şubat ayına kaymasını engelleyerek yasal mevzuata tam uyum sağlar. Maliyetlerin düzgün olması sağlanır. **Sistem Hızı :**** **VF04 ekranında biriken binlerce satır VKDFS verisini etkileyerek SAP faturalama ve raporlama ekranlarının performansını düşürür. **Veri Temizliği**** : **Fiilen faturalandırılmayacak **"çöp" **kayıtların iptal edilerek operasyonel kirliliğinin önüne geçilmesini sağlar. **Onay Süreçleri** : İş süreci olarak kullanıcı bazlı onay kurgusu talepleri, zamanında işlem yapılmaması durumunda gecikmeler ve bilgi kirliliğine yol açmaktadır. Bu durumda toplu onay verilmesi hatalı süreçlerin yürütülmesine sebep verecektir. |
| --- | --- |

Şekil 1 - Periyodik Sıfırlama

**VF04**** - ****Kullanımı ve Toplu Faturalandırma**

- **VF04** işlem koduna gidin.

- Seçim tabından İlgili filtreleri girin. Sabit vermek istediğiniz fatura tarihi gibi verileri standart veriler tabından girebilirsiniz. **Yürüt (F8)** butonuna basın

| Şekil 2 - VF04 Seçim Ekranı | Şekil 3 - VF04 Standart Veriler |
| --- | --- |

      

- Karşınıza gelen listede faturalandırmak istediğiniz satırları seçin.

- **Üst menüde yer alan seçenekleri değerlendirin****. Kullanılan buton işlevleri aşağıda belirtilmiştir.**

  **Simulasyon butonu**. Faturayı kesmez, sadece kesilmesi istenen belgede hata olup olmadığı simulasyon butonu ile kontrol edilir. Hata geliyorsa günlük’teki hata mesajına göre aksiyon alınır.

** ****Münferit f****aturalandır (Individual Billing Document):** Seçilen her belge için manuel müdahale ekranını (VF01 gibi) açar. Hata yoksa kaydedip işlem tamamlanır.

 **Toplu faturalama**. Arka planda toplu olarak fatura kesilmesi isteniyorsa, ilgili satırlar seçilir, gösterilen yerden kaydet’e basılır. 

**VFX3 ****Muhasebe Blokaj Kontrolü**

- **VFX3** işlem kodunu çalıştırın.

Şekil 4 - VFX3 Seçim Ekranı

- Açılan ekranda “Şu nedenle eksik" kısmından spesifik bir hata türünü seçebilir (örn: Hesap tayini, fiyatlandırma) ya da boş bırakarak tümünü listeleyebilirsiniz. Şirket kodu ve tarih kriterlerini doldurarak **Yürüt (F8)** deyin.

- Ekranda listelenen faturalardan analiz etmek istediğiniz satır seçin.

Şekil 5 - VFX3 ALV Görünüm

- İlgili faturayı seçip üstte bulunan **"Yeşil Bayrak" (Release to Accounting)** butonuna basın. Hata yoksa muhasebe belgeleri oluşur. Hata varsa notlar bölümünden hata sebebi incelenir ve çözümlenir.

- Hata çözümlendikten sonra **“yeşil” **bayrağa basarak belgenin muhasebeleşmesi sağlanır.

**SIK KARŞILAŞILAN HATA KODLARI ve FONKSİYONEL / TEKNİK ÇÖZÜM ÖNERİLERİ**

| KOD | AÇIKLAMA | KÖK NEDEN | FONKSİYONEL ÇÖZÜM | EKRAN GÖRÜNTÜSÜ |
| --- | --- | --- | --- | --- |
| VF 014 | Satış ve dağıtım belgesi, faturalama için bloke edildi. | Kaynak belgede (Sipariş) aktif bir faturalama blokajı (Billing Block) bulunması. | VA02 ekranından ilgili belgedeki Faturalama Blokajı alanı **boşluk **(Bloke Değil) konumuna getirilerek kaydedilir. İlgili blokaj herhangi bir onay sürecinden tetiklenerek kaldırılıyorsa, ilgili onaycının işlemini tamamlaması için bilgilendirme yapılır. Blokaj konfigurasyonla varsayılan olarak ayarlanmış ve istenmiyorsa çalışma için SD modül danışmanıyla iletişime geçilir. |  |
| VF 017 | Belge, önceden tam olarak faturalandı. | Kaynak belgenin miktarsal veya tutarsal olarak daha önce tamamen faturalandırılmış olması. | VA03 veya VL03N üzerinden Belge Akışı (Document Flow) kontrol edilerek mükerrer kayıt incelenir. Hatalı fatura varsa VF11 ile iptal edilir. |  |
| VF 044 | Kalem, faturalama ilişkili değil. | İlgili kalemin (Item Category) sistem konfigürasyonunda faturalama hakkının tanımlanmamış olması. | **SD Modül danışmanına konu iletilir.** Kalem tipi faturalama ilişkisi sürece göre değerlendirilip gerekli teknik aksiyonlar tamamlanır. | Uyarlama / Geliştirme |
| VF 050 | Belge <VAR1> saklandı (yevmiye kaydı üretilmedi). | Faturanın SD tarafında başarıyla kaydedilmesi ancak muhasebeye (FI) akış esnasında teknik/fonksiyonel bir blokaja takılması. | VF02 ekranına girilerek "Muhasebeye Serbest Bırak" (Yeşil Bayrak) butonuna basılır ve alınan hata analizi yapılır Gerekirse VFX3 (Bloke Faturalar) listesinden toplu kontrol edilir. |  |
| VF 051 | Belge <VAR1> saklandı (**hesap belirleme hatası**). | Faturadaki gelir, indirim veya vergi kalemlerinin hangi Genel Muhasebe (G/L) hesabına akacağının sistemde bulunamaması. | VF02 işlem koduyla fatura belgesine gidilir Hesap tayini belirlemesinde kullanılan parametreler kontrol edilir (Malzeme, müşteri hesap tayin grupları, sipariş nedeni alanları vb. Sıklıkla kullanılan alanlardır). Bu alanlar boşsa uygun veri ile doldurulur ve VF02’den yeşil bayrakla tekrar tetiklenir. Hesap tayini besleyen alanlarda eksiklik yoksa, VKOA (Hesap Tayini) ekranına gidilir ve kurallar tanımlanır. (**SD Modül danışmanı bilgilendirilir** VF02 işlem kodunda yeşil bayrağa basarak muhasebeye serbest bırakılır. |  |
| VF 055 | <VAR1> belgesini fiyatlandırma hatalı. | Faturadaki fiyatlandırma koşullarında (Price Conditions) veya döviz kurlarında tutarsızlık/eksiklik olması. | VF02 ile fatura kalemlerindeki "Koşullar" (Conditions) sekmesi incelenir Eksik fiyat ana verisi varsa VK11 ile girilir. Fatura kalemlerinde "Fiyatlandırmayı Güncelle" (Update Price - C (Manuel fiyat öğelerini kopyala diğerlerini yeniden belirle) seçeneği) tetiklenir. (*bknz sipariş ekranları) |  |
| VF 068 | Belge <VAR1> şu anda işleniyor (kullanıcı <VAR2> tarafından). | Belgenin başka bir kullanıcı veya arka plan işi (Job) tarafından kilitlenmiş (Enqueue) olması. | Belgeyi kilitleyen kullanıcının işlemi kapatması beklenir veya uyarılır. | Kullanıcı uyarılır |
| VF 071 | Belge <VAR1> saklandı (fiyatlandırma hatası). | VF 055 hatasına benzer şekilde, zorunlu bir fiyat koşulunun (VK11) sistemde bulunamamasına rağmen faturanın taslak kaydedilmesi. | Fiyat koşul kaydı, **ilgili koşul için** (ZX01 örnek olarak verilmiştir) vk13 listesinden kontrol edilir. VF02 -> Kalem Koşulları -> Güncelle adımları izlenerek faturanın mali belgesi tetiklenir. |  |
| VF 136 | <VAR1> termini, faturalama için bloke edildi (faturalama planı). | Faturalama planına bağlı bir sipariş kaleminde, ilgili dönemin/terminin finansal onaya takılması. | VA02 ile siparişteki "Faturalama Planı" (Billing Plan) sekmesine gidilir. İlgili tarihe ait blokaj kaldırılır ve faturalama (VF01) tekrarlanır. |  |
| VF 142 | Termin <VAR1> önceden faturalandı (faturalama planı). | Faturalama planındaki belirli bir taksitin veya dönemin zaten faturaya dönüştürülmüş olması. | VA02 işlem koduyla sipariş faturalama planı durum kodları incelenir Mükerrer fatura kesilmeye çalışılıyorsa süreç durdurulur. |  |
| VF 311 | Belge Saklandı. | Faturanın veri tabanına başarıyla yazıldığını belirten standart sistem bilgi mesajı (Hata değildir). | Herhangi bir aksiyona gerek yoktur, belge başarılı şekilde oluşmuştur. | Aksiyon yok |
| VF 348 | Belge <VAR1> şu anda işleniyor (kullanıcı <VAR2> tarafından). | VF 068 hatası ile aynı kök nedene sahiptir; belgenin başka bir oturumda açık kalması. | Kullanıcının oturumu kapatması sağlanır veya SM12 üzerinden kilit temizlenir. | Aksiyon yok |
| VF 510 | Fatura oluşturma kuralı (copy control) yok / hatalı. | Kaynak belgeden hedef faturaya veri aktarımı sağlayan kopyalama kurallarının sistemde tanımlı olmaması. | **SD Modül danışmanına iletilir. **VTFL (Teslimattan Faturaya) veya VTFA (Siparişten Faturaya) kopyalama kontrolleri kontrol edilir. | Uyarlama / Geliştirme |
| F5 201 | Varyant <VAR4> ve hesap türü <VAR3> için kayıt dönemi <VAR1> <VAR2> açılmamış. | Faturanın kayıt tarihinin, Mali Muhasebe (FI) tarafında kapalı veya henüz açılmamış bir döneme denk gelmesi. | 1. VF02 ile faturanın "Faturalama Tarihi" güncel/açık bir döneme çekilir. 2. Ya da FI ekibi tarafından OB52 ekranından ilgili yıl/dönem aralığı işleme açılır. |  |
| F5 266 | Arızi kayıtlar için ad ve kent girin. | Tek seferlik (One-Time / CpD) müşteri kayıtlarında adres, isim ve şehir bilgilerinin eksik bırakılması. | Belge oluşturulurken veya muhasebeye aktarılırken açılan pop-up ekranda müşterinin ad, soyad ve şehir bilgileri zorunlu olarak doldurulur. **Not:** Bu bilgiler sipariş açılırken belirlendiği için ilgili fatura siparişe kadar ters kayıt alınıp tekrar açılması gerekmektedir. Geri alınamadığı durumlarda siparişe müdahale yetkisi olan bir danışmandan destek alınır. | e-irsaliye kesildiği için bu belgelere yetkili sd danışmanı tarafından manuel müdahele yapılmalıdır. |
| F5 286 | Dönem <VAR1>/<VAR2> hesap türü <VAR3> ve defteri kebir <VAR4> için açılmadı. | Belirli bir Defter-i Kebir (G/L) ana hesabı bazında ilgili mali dönemin kayıt işlemlerine kapalı olması. | Fatura üzerindeki faturalama tarihi açık olan dönem olarak değiştirilir. **Alternatif olarak** OB52 işlem koduna girilir. "S" (Defteri Kebir Hesapları) hesap türü satırında, hatada belirtilen hesap aralığı için ilgili dönem serbest bırakılır. |  |
| F5 351 | Hesap <VAR1> <VAR2> kayıt için bloke edildi. | Muhasebeleşecek ana hesap veya müşteri/satıcı hesap kartının (SKB1/KNB1) kayıtlara bloke edilmiş olması. | BP ekranından müşteri hesap kartına gidilir "Kayıt Blokajı" (Posting Block) işareti kaldırılarak hesap serbest bırakılır. **Not: İlgili cari işlem görmeyecekse** fatura VF11 işlem koduyla iptal edilir. Varsa teslimatların ters kaydı alınır (VL09 veya EWM ekranlarından). Sipariş belgesinde kalemlere ret gerekçesi konulur. |  |
| ZSD 426 | Fatura kesilmesi için önce e-irsaliye gönderimi yapılmalı. | Geliştirilen özel bir sistem kontrolüyle, e-irsaliye süreci tamamlanmadan e-Fatura kesilmesinin engellenmesi. | zczm_edm_t001 irsaliye takip kokpitinden e-İrsaliye başarılı şekilde entegratöre gönderilmeli ve onay durumu alınmalıdır, ardından fatura kesilir. E-irsaliyesi kesilmemiş belgenin durumunu değerlendirmek için depo sorumlusu ile irtibata geçilir. |  |
| ZSD 517 | Fatura tarihi (<VAR1>) günün tarihinden 7 günden önce olamaz. | Şirket mali politikası gereği, fatura tarihinin geriye dönük en fazla 7 gün olmasına izin veren özel kontrol. | VF01/02/04 veya VA02 ekranında faturalama tarihi cari günden en fazla 7 gün geride olacak şekilde revize edilir. Toplu olarak belgelere fatura tarihi verilmek istenirse VF04, standart veriler ekranından (Şekil-3) faturalama tarihi bilgilerini girebilirsiniz. |  |
| ZSD 659 | Fatura tarihi (<VAR1>) günün tarihinden 7 günden önce olamaz. | ZSD 517 validasyonunun farklı bir belge türü veya kalem kırılımı için çalışan eş hata kodu. | ZSD517 hata türünde olduğu gibi fatura tarihi güncel veya izin verilen yasal tolerans sınırları içerisine çekilir. |  |
| F5 808 | Alan <VAR1> ana hesap <VAR2> <VAR3> için zorunlu bir alan. | Muhasebe hesap tayininde, ilgili G/L hesabının Alan Durum Grubu (Field Status Group) kurallarına göre zorunlu olan bir verinin (Örn: Kar Merkezi, Metin, İş Alanı) girilmemesi. | Eksik alan faturada doldurulur. Bu alan muhasebe metni gibi arka planda doldurulan bir alansa verinin neden dolmadığı ile ilgili olarak SD / FI danışmanlarından destek alınır. Opsiyonel : Hata mesajında zorunlu tutulan alan kullanılmayacaksa FI danışmanından zorunluluğun kaldırılması talep edilir. | Hata mesajındaki alana göre farklı ekranlar kullanılabilir. |
| ZFI 150 | Ana veride tercih göstergesi bakımı eksiktir! İş alanı türetilemedi. | Şirketinize özel (Z'li) geliştirilen, müşteri veya malzeme ana verisindeki eksiklikten dolayı iş alanı (Business Area) bulma lojiğinin kırılması. | Müşteri ana verisi (BP)) üzerindeki tercih göstergesi alanları kontrol edilir. Gerekli düzenlemeler yapıldıktan sonra VF02 işlem kodu ve yeşil bayrakla muhasebeye akış sağlanır. |  |
| ZSD 262 | Satış Bürosu zorunlu alanı doldurun. | Şirket içi validasyon kuralları gereği, satış belgesinde "Satış Bürosu" (Sales Office) alanının boş bırakılmış olması. | VA02 ile sipariş başlık bilgilerine gidilir. Satış Bürosu (Sales Office) alanı doldurularak belge kaydedilir. Not : Sipariş içerisinden benzer hata mesajları gelebilir. Eksik bilgiye istinaden siparişte düzenleme yapılarak süreç devam ettirilir. |  |

2