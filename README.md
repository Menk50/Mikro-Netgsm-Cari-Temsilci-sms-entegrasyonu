# Mikro-Netgsm-Cari-Temsilci-sms-entegrasyonu
Mikro ERP ve NETGSM entegreli Vadesi Geçen Bakiyelerin Temsilcilerine Sms Entegrasyonu servisi


Örnek Personel Sms Gönderme:
sms_Gonder.sms(sql_per_cep, sql_per_adi, kayit_say, toplam);

Örnek Firma Müdür/Temsilci Sms Gönderme : 
 sms_Gonder.patron_sms(firma_cep_no,firma_Temsilci_adi,personel_say.ToString(), kayit_say, toplam);
 
 Örnek Gelen SMS ;

Sayin 'TEMSİLCİADI' "Vadesi geçmiş cari sayısı" Adet Vadesi Gecmis Ödeme Alinmamis Cariniz bulunmaktadir.Toplam Tutar :"VADESİ GEÇMİŞ CARİLERİN TOPLAM BAKİYESİ" TL dir 


SQL FUNC Kullanımı: 
insert into gecicib2b  exec Neyfer_Yapilacak_Tahsilat_Hesapla


SQL jobs ile step delete|insert ve exec adımları çalışarak belirlenen saatte ve günde job çalışmaktadır. 
Servis ile Berirlenen gün (DEFAULT PAZARTESI SAAT 9) ve saatte servis kendini çalıştırarak "cari personel tanıtım kartındaki" Special1 kodu dolu olan tüm personelleri listeleyerek func daki veriler ile eşleştirip bu verileri birleştirmektedir. Birleşirilen verileri "cari personel tanıtım kartındaki" personel unvan ve personel cepno bölümündeki verileri ilede sms göndermektedir.

Projedenin tüm kaynak kodları Private olarak rep edilmiştir.
