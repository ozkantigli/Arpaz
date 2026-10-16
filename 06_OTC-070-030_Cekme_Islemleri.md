---
kaynak_dokuman: "Final_Completed_OTC-070-030_Çekme_İşlemleri.pdf"
konu: "OTC-070-030 Çekme İşlemleri (EWM / Total Depo / Arbarkod)"
bicim: pdf
---

# Final_Completed_OTC-070-030_Çekme_İşlemleri.pdf


<<< SAYFA 1 >>>
Final_Completed_OTC-070-030 Çekme İşlemleri

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

OTC-070-030

Çekme İşlemleri (EWM/Total Depo/Arbarkod Entegrasyonu)

L4 Kodu

L4 Süreç Adı

OTC-070-030-010

MM Depo Çekme İşlemleri

OTC-070-030-020

EWM Depo Çekme İşlemleri

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
Bu doküman sevk ve teslimat yönetimi kapsamında ortaya çıkan çekme işlemleri sürecinin Arçelik iş süreçlerinin tasarımını, SAP En İyi
Uygulamalar, Model Company ve Arçelik Entegrasyon İş Süreçleri baz alınarak iş akışları, teknik gereksinimler ve süreç adımları halinde
içermektedir.

2.

Ön Koşullar

2.1

Organizasyonel Yapı

Çekme işlemleri Arçelik Pazarlama bünyesindeki tüm satış organizasyonları için kullanılan bir süreçtir.

2.2

Ana Veri

Çekme işlemleri sürecinde malzeme ana veri yapısı kullanılacaktır.

2.3

Varsayımlar

3.

SAP Best Practice Detayları

Best Practice Tanımı ve Solution Process Flow Linkleri
Sevkiyat ve çekme işlemi ilişkili Best Practice ve süreç akış diagramı aşağıdaki linkte yer almaktadır.
BD9-Sell from Stock Process

4. Arçelik Senaryolara Genel Bakış
Çekme işlemi ürünlerin depo yerlerinden doğru miktarlarda alınarak sevkiyat için hazırlanacağı alana taşınması işlemidir.

4.1. OTC-070-030-010 MM Depo Çekme İşlemleri
MM depo çekme işlemleri Arbarkod ve Total Depo sistemlerinden yürütülecektir ve bu bilgi SAP S/4 HANA sistemine entegrasyonla
alınacaktır.
Çekme işlemi yapıldıktan sonra SAP S/4 HANA sistemindeki teslimatlar güncellenecektir.

4.1.1.

Sürece Genel Bakış

Arbarkod ve Total sistemlerinden çekme işlemi yapılır.
SAP S/4 HANA sistemin teslimat güncelleme işlemleri gerçekleşir.

4.1.2.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070030-01 Çekme İşlemleri
SD070030-01 Çekme İşlemleri Süreç Akışı Ekran Görüntüsü :


<<< SAYFA 3 >>>
4.1.3.

Süreç Adımları

Çekme işlemleri süreç adımları aşağıdaki gibidir :
1. Ortec kullanan depolar terminale ortec teki araç numarasını, ortec kullanmayan depolar ise teslimat numarasını terminale
girerek mal çıkış işlemlerini başlatır.
2. ZSD_PICK_VIEW4 fonksiyonu ile terminallerden girilen teslimat bilgileri SAP den çekilir ve kullanıcı bu bilgileri terminalde
görüntüler.
3. Arbarkod veya Total depo sisteminden çekme işlemleri yapılır.
4. Çekme işlemleri yapıldıktan sonra seri no bilgisi güncellenir.
5. Arbarkod ve Total depo sistemlerinden SAP S/4 HANA sistemine çekme işlemleri ve seri no bilgisi entegrasyonla alınır. Bu işlem
için SAP de SDPICK temel ileti tipinde idoc oluşur ve bu idoclar ile teslimatlar güncellenir.
6. Mal çıkışı gerçekleşir: Araç no ile toplu bir şekilde mal çıkışı gerçekleştirilmek istendiğinde VL06O ile mal çıkışı yapılır. Teslimat
numarası ile mal çıkışı yapılmak istendiğinde VL02N ile mal çıkışı yapılır.

Süreç
Adım
No

Süreç Adımı

1

Ortec kullanan depolar terminale ortec teki araç numarasını, ortec
kullanmayan depolar ise teslimat numarasını terminale girerek mal çıkış
işlemlerini başlatır.

2

ZSD_PICK_VIEW4 fonksiyonu ile terminallerden girilen teslimat bilgileri SAP
den çekilir ve kullanıcı bu bilgileri terminalde görüntüler.

İşlem
Kodu /
Fonksiyon
Adı

ZSD_PICK_V
IEW4
ZARBARCOD
E_01_DELIV
ERY_REPORT

Entegrasyon
Kaynak
Sistem

Entegrasyon
Hedef
Sistem

Job

Arbarkod-Total

S4

S4
da
tetikl
enen
bir
job
bulun
muyo
r.

S4

Arbarkod-Total

S4
da
tetikl
enen
bir
job
bulun
muyo
r.


<<< SAYFA 4 >>>
3

Arbarkod veya Total depo sisteminden çekme işlemleri yapılır.

Eski
Arbarkod
fonksiyonu:

Arbarkod-Total

S4

S4
da
tetikl
enen
bir
job
bulun
muyo
r.

Arbarkod-Total

S4

S4
da
tetikl
enen
bir
job
bulun
muyo
r.

Arbarkod-Total

S4

S4
da
tetikl
enen
bir
job
bulun
muyo
r.

ZSD_DELV_
SET_PICK_Q
UANTITY
Fiori
terminalleri
fonksiyonu:
ZARBARCOD
E_02_SEND_
DELIVERY
4

Çekme işlemleri yapıldıktan sonra seri no bilgisi güncellenir.

Eski
Arbarkod
fonksiyonu:
ZSD_DELV_
SET_PICK_Q
UANTITY
Fiori
terminalleri
fonksiyonu:
ZARBARCOD
E_02_SEND_
DELIVERY

5

Arbarkod ve Total depo sistemlerinden SAP S/4 HANA sistemine çekme
işlemleri ve seri no bilgisi entegrasyonla alınır. Bu işlem için SAP de SDPICK
temel ileti tipinde idoc oluşur ve bu idoclar ile teslimatlar güncellenir.

6

Mal çıkışı gerçekleşir: Araç no ile toplu bir şekilde mal çıkışı gerçekleştirilmek
istendiğinde VL06O ile mal çıkışı yapılır.

SDPICK ileti
tipinde IDoc

Teslimat numarası ile mal çıkışı yapılmak istendiğinde VL02N ile mal çıkışı
yapılır.

Arbarkod ve Total fonskiyonlarıyla ilişkili yazılan bazı doküman linkleri:
Total:
Total S4 HANA Entegrasyonları
Arbarkod:
SATH-4750 Arbarkod - > S/4 HANA Teslimat Entegrasyonu
SATH-4748 Fiori Arbarkod Teslimat Çekme İşlemleri Entegrasyonu
SATH-2190 Arbarkod Fiori el terminali ekranlarının fonksiyonlarının ARPAZ S4 sisteminde uygulanması WRICEF No: MM085 Function
Group ZARBARCODE_IF
SATH-2245 Arbarkod Alınan Teslimata İstinaden Mal Giriş Fonksiyonu

4.2. OTC-070-030-020 EWM Depo Çekme İşlemleri
EWM’li depodan yürütülen süreçlerde SAP S/4 HANA sisteminde yaratılacak teslimat belgesi çekme ve mal çıkış işlemlerinin yapılması
için EWM sistemine dağıtılır.

4.2.2.

Sürece Genel Bakış

EWM sisteminde çekme işlemi yapılacaktır.
SAP S/4 HANA sisteminde ZSD_0001 ekranındaki "EWM'e dağıt" işlem tipiyle teslimatlar EWM'e gönderilecektir.
Teslimatlar EWM'e dağıtıldıktan sonra değiştirilememektedir.


<<< SAYFA 5 >>>
Ortec ilişkisiz teslimatlar; ZSD_0001 ekranına kurulan ZASD:ORTEC_TESLIMAT_EWM_DGTM jobı ile EWM'e otomatik dağıtılır. Bu
teslimatlar kargoyla sevk edileceği için araç id(LIKP-LIFEX) boş olacaktır.
Ortec ilişkili teslimatlar; EWM sistemine manuel olarak kullanıcı tarafından dağıtılır. Teslimatlarda araç id(LIKP-LIFEX) olanlar için
EWM'e dağıtım işlemi yapılabilmektedir.

4.2.3.

Süreç Akışı

Arçelik Solution Process Flow Linkleri
SD070030-01 Çekme İşlemleri
SD070030-01 Çekme İşlemleri Süreç Akışı Ekran Görüntüsü :

4.2.4.

Süreç Adımları

Çekme işlemleri süreç adımları aşağıdaki gibidir :
1. SAP S/4 HANA sistemindeki teslimatın çekme işleminin yapılması için ZSD_0001 ekranından EWM sistemine dağıtılır.
2. EWM sisteminde çekme süreci tamamlanır. EWM süreçlerine ilişkin detaylar Final_OTC-070-040 Mal çıkış süreçleri-EWM
dokümanında yer almaktadır.
3. Fiili yüklenen mallar ve seri no bilgisi SAP S/4 HANA sistemine aktarılır.
4. Mal çıkışı gerçekleşir.
5. Mal çıkışı bilgisi EWM'den SAP S/4 HANA sistemine gönderilir.

5.

6.

Arçelik Entegrasyon Süreçlerine Uyum Detayları

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

Nakliye planlama (Ortec-Lotus sistemi
entegrasyonu)

Final_Completed_OTC-070-020
Nakliye planlama

Sevkiyatın nakliyesinin planlandığı Ortec-Lotus sisteminin
detayları bulunmaktadır.

3

Mal çıkış süreçleri (EWM/Total Depo
/Arbarkod Entegrasyonu)

Final_Completed_OTC-070-040 Mal
çıkış süreçleri

Sevkiyat planlamanın son aşaması olan mal çıkış süreçleri
detaylandırılmıştır.

Final_OTC-070-040 Mal çıkış
süreçleri-EWM


<<< SAYFA 6 >>>
7.

Geliştirme Listesi

Jira No

WRICEF ismi

WRICEF Tipi

WRICEF Sorumlusu (Arçelik/SAP)

SATH-2167

S/4 HANA -> Total depo Teslimat Entegrasyonu WRICEF No: MM071

Entegrasyon

Aslıhan Türkmen

SATH-2123

S/4 HANA -> Arbarkod Süreci - SD049

Entegrasyon

Aslıhan Türkmen

CR
