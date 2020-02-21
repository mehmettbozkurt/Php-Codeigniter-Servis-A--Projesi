# Php-Codeigniter-Servis-Aği-Projesi

SERVİS AĞ PROGRAMI
Servis ağ programının amacı müşteri ve personelleri takip etmektir. Program personellerin telefonuna uygulama olarak indirilir. Her personel kendi kullanıcı adı ve şifresiyle giriş yapar. Kendisine atanan işleri buradan takip etmektedir. Personele siteden iş atandığı zaman personele uygulamadan bildirim gitmektedir. Personele gideceği müşterinin adı, adresi ve yol tarifi bildirimle iletilecektir. Personel işi tamamladıktan sonra iş durumunu tamamlandı olarak işaretleyecek ve müşterinin imzasını alacaktır. Firmanın mail adresine bildirim gidecektir. Personel işi tamamladı siz tamamlanan işi onaylıyor musunuz? Firma da onayladıktan sonra iş durumu tamamlanacaktır. 

# ANA SAYFA;
![anasayfa](https://user-images.githubusercontent.com/44640029/75079595-4b5b3280-551a-11ea-9ee6-4ccde5d12185.png)

•	Firma kullanıcı adı ve şifresiyle giriş yapacaktır.
•	Ana sayfa da iş raporu, iş listesi, son hareketler, biten işler, iptal olan işler listelenmektedir.
•	İş raporu bölümünde günlük, haftalık, aylık olarak yapılan işleri göstermektedir. Müşterinin arızalarını gidermek için personele atanan işler bu bölümde bekleyen, iptal, tamamlanan olarak listelenmekte ve toplam ne kadar iş yapıldığı yer almaktadır.
•	İş listesi bölümünde personele atanan işlerin, devam eden işlerin ve yeni başlayan işlerin listesi yer almaktadır.
•	Son hareketler kısmında son 100 hareketi göstermektedir. Burada atanan işler, biten işler, tamamlanan işler, güncellenen müşteriler, il-ilçe isimlerinde güncellemeler (sistemde yapılan her türlü değişiklik) listelenmektedir ve hangi personel tarafından yapıldığı da yer almaktadır.
![2](https://user-images.githubusercontent.com/44640029/75079659-8cebdd80-551a-11ea-95cd-b15465b51e98.png)

•	Biten işler kısmında son biten 100 işi listelemektedir. Tarih, saat ve hangi personel tarafından yapıldığı görülmektedir. Yanındaki #sayı tuşuna basıldığı zaman işin detayları listelenmektedir.
•	İptal olan işler kısmında son 100 iptal olan işi göstermektedir. Tarih, saat ve personelin adı yer almaktadır. İş detayları #sayı kısmına tıklandığında ekrana gelmektedir.
# İŞ YÖNETİMİ;

İş yönetimi kısmında iş ekleme ve listeme, iş tipi ekleme ve listeleme kısmı yer almaktadır.
![is-yonetimi](https://user-images.githubusercontent.com/44640029/75079699-b60c6e00-551a-11ea-936e-a0d3e4361735.png)

•	İş listesi müşterinin adı soyadı, personelin adı, işin başlangıç tarihi, ili-ilçesi, işin durumu (atandı, tamamlandı, devam ediyor) yer almaktadır. İşlemler kısmında iş listesinden silme ve düzenleme işlemi yapılabilir.
•	Çağrı numarası işin detayları ile iş hareketleri görülmektedir. İş detaylarında personel, arıza oluşturan kişi, işin durumu, işin türü, işi oluşturma tarihi, işe başlama ve bitirme tarihi/saati, müşteri adı, telefonu, ve adres bilgileri, bildiren kişi, yetkili kişi yer almaktadır.
•	İş kodu ve müşteri adı ile arama yapıp sonuçları listeleyebilirsiniz.

 

•	Sağ kutucukta iş filtreleme bölümü yer almaktadır. Kutucuğa tıklandığında ekrana gelen personel, iş durumu, iş tipi, il, ilçe ve tarih aralığından birini seçip iş ona göre listelenebilir.


 
•	Personele göre seçtiğimizde ekrana açılan kısımda hangi personeli istiyorsak onun adını seçiyoruz veya birden fazla personel seçebiliriz.
•	Filtrele dediğimiz zaman seçilen personele ve personellere ait bilgiler listelenmektedir.


 

•	İş tipi listeme de işin ne olduğu yer almaktadır. Cihaz değiştirme, teknik servis gibi kurumun yaptığı işlerin listesi görülmektedir. Silme ve düzenleme işlemi yapılabilir.
•	Arama butonunu kullanarak tablo içerisindeki tüm alanlarda arama yapabiliriz.

FİRMA YÖNETİMİ;
Firma yönetimi bölümünde firma düzenleme ve mail ayarları yer almaktadır. Firma ile ilgili bilgilerin düzenlenmesinde kullanılır.
•	Firma düzenleme bölümünde firmanın adı, yetkili kişisi, firma telefon numarası, vergi numarası, vergi dairesi, adres ve uygulama dili (Türkçe, İngilizce) daha sonra firma logosu eklenerek kaydedilir. Firmaya ait bilgiler kayıt edilip istenildiği zaman değiştirilebilir.

•	Mail ayarları kısmında firmanın kullandığı mailin adresi, kullanıcı adı, parolası kaydedilir. Müşteriler firmaya mail atacağı zaman bu mail adresini kullanırlar.

# PERSONEL YÖNETİMİ;

Personel yönetiminde personel ekleme kısmı bulunmaktadır.
![personel-yonetimi](https://user-images.githubusercontent.com/44640029/75079744-e18f5880-551a-11ea-90ed-22a4a33f475e.png)

•	Firmanın personellerini kayıt edip listelediği bölümdür.
•	Personel eklerken personelin adı, tc kimlik numarası, telefonu, mail adresi, parolası (uygulamaya girerken kullanacağı parola), yetkisi, firma adı eklenip personel kayıt edilir.
•	Personel düzenleme kısmından personele ait bilgilerin hepsinin düzenlenmesini, değiştirilmesini sağlar.
•	Arama butonunu kullanarak tablo içerisindeki tüm alanlarda arama yapabiliriz.




# MÜŞTERİ YÖNETİMİ;

Müşteri ekleme ve listeleme kısmıdır.

 

•	Müşteri eklerken müşterinin adı soyadı, müşteri kodu, yetkili kişisi, müşteri maili, telefon numarası, ili/ilçesi, adresi, adres tarifi, müşteri fotoğrafı eklenerek müşteri kaydedilir.
•	Müşteri listeleme kısmında kayıtlı olan bütün müşterilerin ismi listelenir. Müşterinin kodu, adı, adresi ve telefon numarası ekrana sıra halinde gelir. Düzenleme ve silme işlemi yapılabilir. Düzenleme kısmında müşteriyle ilgili bilgilerin değiştirilmesi, düzenlemesi yapılabilir.
•	Arama butonunu kullanarak tablo içerisindeki tüm alanlarda arama yapabiliriz.
İL-İLÇE YÖNETİMİ;

İllerin ve ilçelerin eklenip, listelendiği bölümdür. İl ve ilçe isimlerini yazarak arama yapabilir, silme ve düzeltme işlemi yapabiliriz.
 
•	İllerin kaydedilip listelendiği bölümdür.
 
•	İlçelerin kaydedilip listelendiği bölümdür. İlçe eklerken bağlı olduğu ili de seçmek gerekmektedir.
•	Arama butonunu kullanarak tablo içerisindeki tüm alanlarda arama yapabiliriz.


# DEPO YÖNETİMİ;

Firmaya ait olan depoların sisteme eklenip, listelendiği bölümdür.

•	Firmaya ait olan depoları eklerken depo adı, varsa bağlı olduğu personel, il ve ilçesi, varsa açıklaması eklenip kayıt edilir.
•	Depo listesinde depo adı, bağlı olduğu il, bağlı olduğu ilçe, açıklaması yer alarak listelenmektedir. Depo silme ve düzenleme işlemi yapılabilmektedir. Depo düzenleme bölümünden depoya ait bilgiler değiştirilebilir.
•	Arama butonunu kullanarak tablo içerisindeki tüm alanlarda arama yapabiliriz.

# STOK YÖNETİMİ;

Stok ve stok hareketleri ekleme ve listeleme bölümüdür.
 ![stok-yonetim](https://user-images.githubusercontent.com/44640029/75079870-5f536400-551b-11ea-8d11-5ceb1ddcac43.png)

•	Stoklar eklerken ürününü kodu, adı ve bağlı olduğu depo seçilerek ürün kaydedilir.
•	Stokları listelerken ürünün adı, ürünün kodu, olduğu depo yer almaktadır. Stok silme işlemi yapılabilmektedir. Ürün bilgileri hakkında düzenleme işlemi yapılabilmektedir.
•	 Stokta olup olmadığı düzenleme kısmından ayarlanabilir.
•	Arama butonunu kullanarak arayacağımız ürünün adını,ürün kodunu,depo adını veya stok durumunu  yazarak arama yapabiliriz.
•	Stok hareketi eklerken stoktaki ürün seçilir. Bağlı olduğu iş bölümünde ürünün ne için kullanılacağı seçilir. Gideceği depo seçilir, işlem türü işaretlenir, hareket (giriş, çıkış) seçilir, gerekli olursa açıklama eklenir ve stok hareketi eklenir.
•	Stok hareketleri listelemede ürünün adı, seri numarası, hareket, çıktığı depo, girdiği depo, tür, açıklama, tarih türünde ürün hareketleri listeler.

# ÜRÜN YÖNETİMİ;

Ürün yönetimi kısmında firmaya ait olan ürünleri ekleyip listeleyebiliriz.
•	Ürün ekle kısmından ürünler eklenebilir.
•	Listele kısmında eklenen ürünler görülmektedir.
•	Eklenen ürünleri silme veya düzeltme işlemi yapılabilir.
•	Arama butonunu kullanarak tablo içerisindeki tüm alanlarda arama yapabiliriz.

# RAPORLAR MENÜSÜ
Raporlar menüsü kısmında iş raporları ve stok raporları bölümü yer almaktadır.

# İŞ RAPORLARI;

•	İş raporlarını grafik iş raporu ve liste iş raporu olarak görebilmekteyiz.
•	Liste iş raporunda listelenmiş olarak iş raporları yer almaktadır.
•	Grafik iş raporunda toplam işler, bekleyen işler, tamamlanan işler, iptal edilen işlerin sayısı ayrı ayrı olarak görülmektedir. Grafik şeklinde de gösterilmektedir. 
•	Çizelge kısmında işlerin aylık olarak toplamı yer almaktadır. Aylara göre çizelgesi iş durumu gözükecektir.


# STOK RAPORLARI;

•	Stok raporları kısmında toplam depo sayısı, toplam stok sayısı, toplam stok hareketi ve toplam ürün çeşidi sayıları ayrı ayrı yer almaktadır.
•	Sol alttaki grafikte toplam stok, toplam depo ve toplam stok hareketini grafik şeklinde göstermektedir.
•	Sağ alttaki grafikte toplam ürün çeşitlerini ve hangi üründen kaç adet olduğunu grafik şeklinde göstermektedir. Depoda ki ürünlerin hangisinden kaç adet kaldığını bu grafikten takip edebiliriz.
