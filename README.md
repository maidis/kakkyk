# [Kamuda Açık Kaynak Kodlu Yazılım Kullanımı](https://cbddo.gov.tr/proje-aciklamasi/6776/kamuda-acik-kaynak-kodlu-yazilim-kullanimi)

Hâlihazırda birçok kamu kurumunun bilgi teknolojisi altyapılarında kullanılan ticari lisanslı yazılımlar kurumlarımız açısından oldukça önemli bir maliyet oluşturmaktadır. Hızlanan dijital dönüşüm ile birlikte bu maliyetin önümüzdeki dönemde daha da artması beklenmektedir. Öte yandan, birçok ticari lisanslı yazılımın benzerleri açık kaynak kodlu yazılım (AKKY) olarak da geliştirilmekte ve dünyada yaygın şekilde kullanılmaktadır. AKKY kullanımı, kamunun bilgi teknolojisi harcamalarında maliyet tasarrufunun yanı sıra, yerel yazılım ekosisteminin geliştirilmesi ve siber güvenliğin güçlendirilmesi açısından da önemli bir potansiyel barındırmaktadır.

Bu potansiyelden Türkiye adına mümkün olduğunca faydalanmak amacıyla, kamuda AKKY kullanımını yaygınlaştırmak üzere [Cumhurbaşkanlığı Dijital Dönüşüm Ofisi Başkanlığı](https://cbddo.gov.tr) tarafından hazırlanan "Kamuda Açık Kaynak Kodlu Yazılım Kullanımı" konulu [2023/13 sayılı Cumhurbaşkanlığı Genelgesi](https://www.resmigazete.gov.tr/eskiler/2023/07/20230729-34.pdf), 29/07/2023 tarihli ve 32263 sayılı Resmî Gazete'de yayımlanarak yürürlüğe girmiştir.

Söz konusu Genelge uyarınca kamu kurumları, AKKY Geçişi Analiz ve Yol Haritası Raporunu, [AKKY Geçişi Analiz ve Yol Haritası Raporu Şablonuna](https://cbddo.gov.tr/SharedFolderServer/Projeler/File/AKKY_Gecisi_Analiz_ve_Yol_Haritasi_Raporu_Sablonu.ods) uygun ve TÜBİTAK-ULAKBİM tarafından hazırlanan [Açık Kaynak Kodlu Yazılıma Geçiş Analiz Rehberini](https://cbddo.gov.tr/SharedFolderServer/Projeler/File/Acik_Kaynak_Kodlu_Yazilima_Gecis_Rehberi.pdf) dikkate alacak şekilde hazırlayacak olup Genelge'nin yayım tarihinden itibaren 9 ay içerisinde Cumhurbaşkanlığı Dijital Dönüşüm Ofisi Başkanlığına ileteceklerdir.

## Açık Kaynak Kodlu Yazılıma Geçiş Süreci Aşamaları

![Açık Kaynak Kodlu Yazılıma Geçiş Süreçleri](./akky-gecis-surecleri.jpeg)

### 1. Envanter Çalışması

- Öncelikle, kurumda kullanılan ticari lisanslı yazılım envanterinin çıkarılması gerekmektedir.
- Envanter oluşturulurken rapor şablonunda bulunan üst ve alt kategoriler dikkate alınır.

### 2. Teknik Analiz

AKKY'lere geçişle ilgili teknik analizler yapılarak

- Avantajlar
- Dezavantajlar
- Varsa kısıtlar

bu bölümde doldurulacaktır.

### 3. Yetkinlik Analizi

Kurum organizasyonunda belirlenmiş olan birimlerin bilişim sistemleri açısından eğitim seviyesi ve yetkinlikleri analiz edilerek bu bölüm doldurulacaktır.

### 4. Maliyet Analizi

Kurumlar tarafından envantere girilen ticari lisanslı yazılım ve muadili olan AKKY'lerin geçmiş dönem maliyetlerinden bağımsız olarak önümüzdeki 5 yıllık projeksiyonda toplam sahip olma maliyeti belirtilir.

### 5. Karar

Bu bölümde:

- Geçiş yapılabilirlik kararı, geçiş yapılamıyorsa gerekçeleri
- Geçiş için başlangıç tarihi, geçiş tamamlanma tarihi ve
- Açıklamalar

girilerek doküman tamamlanır.

## AKKY Geçişi Analiz ve Yol Haritası Raporu Şablonu

![AKKY Geçişi Analiz ve Yol Haritası Raporu Şablonu](./AKKY_Gecisi_Analiz_ve_Yol_Haritasi_Raporu_Sablonu.png)

### Envanter Çalışması
				
- Yazılım Adı: Mevcutta kullanılan yazılımın (EBYS, ERP, E-Posta vb.) bilgileri belirtilir.
- Üst Kategori: Envantere alınan yazılımın dahil olduğu üst kategori belirtilir.
- Alt Kategori: Envantere alınan yazılımın  dahil olduğu alt kategori belirtilir.
- Lisans Adedi: Ürünün lisans tipine göre satın alınmış olan miktarı belirtilir.
- Kullanıcı Sayısı: Son kullanıcı lisansları için, ürünün kullanıcı sayısı belirtilir.
- Lisans Adı: Lisansın ticari adı belirtilir.
- Lisans Son Kullanım Tarihi: Ürünün lisansına ait son kullanım tarihi belirtilir.

#### Kategoriler

##### Sunucu Sistemleri

- İşletim Sistemleri
- Veri Tabanı Yönetim Sistemi
- Dizin Yönetimi ve Kullanıcı Cihaz Yönetimi Sistemleri
- E-Posta Sistemi
- Alan Adı Sunucu Sistemi (DNS)
- Dinamik Makine Yapılandırma Protokolü (DHCP)
- Ağ İlkesi Sunucusu (NPS, RADIUS)
- Web ve Uygulama Sunucusu
- Dosya Sunucusu
- Video Konferans Sistemi
- Diğer

##### Sanallaştırma Ortamları

- Konteyner Teknolojileri
- Depolama Alanı Sanallaştırma
- Ağ Sanallaştırma
- Masaüstü Sanallaştırma ve Uygulama Sanallaştırma
- Diğer

##### Siber Güvenlik Yazılımları

- Güvenlik Duvarı
- Web Uygulama Güvenlik Duvarı (WAF)
- Saldırı Tespit / Önleme Sistemi (IDS / IPS)
- Güvenlik Bilgileri ve Olay Yönetimi (SIEM)
- Ağ Erişimi Kontrol Sistemi (NAC)
- E-Posta Güvenliği
- Sanal Özel Ağ Sistemi (VPN)
- Ağ ve Sunucu Sistemleri İzleme Sistemi
- Anti-virüs
- Güvenlik Zafiyet Yönetimi
- Diğer

##### Son Kullanıcı Uygulamaları

- İşletim Sistemi
- Kurumsal Uygulamalar
- Ofis Uygulamaları
- Multimedya Uygulamaları
- Mesleki Uygulamalar
- Web Uygulama Yazılımları
- Diğer

##### Diğer

- Diğer

### Teknik Analiz

- Açık Kaynak Kodlu Muadili: Ticari ürünün yerine kullanılması planlanan açık kaynak kodlu yazılımın adı belirtilir.
- Avantajlar: Açık kaynak kodlu muadil uygulamanın teknik üstünlükleri; bakım, destek, entegrasyon gibi konulardaki avantajları bu bölümde belirtilir.
- Dezavantajlar: Açık kaynak kodlu muadil uygulamanın teknik yetersizlikleri; bakım, destek, entegrasyon gibi konulardaki dezavantajları bu bölümde belirtilir.
- Kısıtlar: İşletim sistemi bağımlılığı, donanım bağımlılığı, uygulama bağımlılığı vb. kısıtlar bu bölümde belirtilir.

### Yetkinlik Analizi

Yetkinlik: Projenin yürütülmesi için ihtiyaç duyulan personelin teknik yeterlik durumu belirtilir.

- Kurum Personeli Yeterli
- Eğitim İhtiyacı Var
- Dış Hizmet Alımı Gerekli
- Kaynak Bulunamıyor

### Maliyet Analizi

- Açık Kaynak Kodlu Yazılım: Geçmiş dönem maliyetlerinden bağımsız olarak önümüzdeki 5 yıllık projeksiyonda açık kaynak kodlu yazılım kullanımının toplam sahip olma maliyeti belirtilir.
- Ticari Lisanslı Yazılım: Geçmiş dönem maliyetlerinden bağımsız olarak önümüzdeki 5 yıllık projeksiyonda ticari lisanslı yazılım kullanımının toplam sahip olma maliyeti belirtilir.

### Karar

- Geçiş Yapılabilirlik: Açık kaynak kodlu yazılım kullanımı ile ilgili nihai karar belirtilir.
- Geçiş Yapılamıyorsa Gerekçeleri: Geçiş yapılamıyorsa detaylı bir şekilde gerekçelendirilir.
- Geçiş Başlangıç Tarihi: Geçiş için planlanan başlangıç tarihi belirtilir.
- Geçiş Tamamlanma Tarihi: Geçiş için planlanan tamamlanma tarihi belirtilir.
- Açıklamalar: İhtiyaç halinde ayrıntılı bilgiler bu kısma yazılır.


## Blog

- [Açık Kaynak Dünyasında Yok Yok](https://www.linkedin.com/pulse/a%C3%A7%C4%B1k-kaynak-d%C3%BCnyas%C4%B1nda-yok-ersen-denli/) - Ersen Denli - Bahçelievler Belediyesi
- [Açık Kaynak Kodlu Yazılım (AKKY) Nedir](https://www.domainhizmetleri.com/blog/acik-kaynak-kodlu-yazilim-akky-nedir/) - Barış A. - Domainhizmetleri.com
- [Açık Kaynak Kodlu Yazılımların Güvenlik ve Risk Açısından Değerlendirilmesi](https://medium.com/databulls/a%C3%A7%C4%B1k-kaynak-kodlu-yaz%C4%B1l%C4%B1mlarda-risk-ve-g%C3%BCvenlik-alg%C4%B1s%C4%B1-ac7e7d250b6) - Meltem Yapar
- [Kamuda Açık Kaynak Kodlu Yazılım Kullanımı Dönüşümünde Dikkat Edilmesi Gerekenler](https://www.kuvarssoft.com/pardus-donusumu-blog/kamuda-acik-kaynak-kodlu-yazilim-kullanimi/) - Kuvarssoft Teknoloji

## Haber

- [Avcılar Belediyesi Açık Kaynak Kodlu Yazılıma Geçti](https://www.techinside.com/avcilar-belediyesi-acik-kaynak-kodlu-yazilima-gecti/), [2](https://www.bthaber.com/avcilar-yazilimda-acik-kaynaga-gecti/), [3](https://www.chip.com.tr/haber/avcilar-hem-guvenlik-hem-tasarruf-saglayacak-yazilimda-acik-kaynaga-gecti_161232.html) (2024)
- [Kamuda Açık Kaynağa Yolculuk Başlıyor](https://www.dunya.com/kose-yazisi/kamuda-acik-kaynaga-yolculuk-basliyor/704963) (2023)
- ["Kamuda Açık Kaynak Kodlu Yazılım Kullanımı" Konulu Cumhurbaşkanlığı Genelgesi Resmi Gazete’de Yayımlandı](https://www.pardus.org.tr/haberler/kamuda-acik-kaynak-kodlu-yazilim-kullanimi-konulu-cumhurbaskanligi-genelgesi-resmi-gazetede-yayimlandi/) (2023)
- [Kamuda Açık Kaynak Kodlu Yazılım Kullanılması Maliyetleri Düşürecek](https://www.dunya.com/sektorler/teknoloji/kamuda-acik-kaynak-kodlu-yazilim-kullanilmasi-maliyetleri-dusurecek-haberi-703172) (2023)
- [TOBB Ev Sahipliğinde AKKY Kamu Bilgilendirme Toplantısı](https://www.dunya.com/kose-yazisi/kamuda-acik-kaynak-kodlu-yazilima-geciste-tarihi-bir-gune-daha-imza-atildi/713676), [2](https://twitter.com/ErtanBarut/status/1735592436120875045) (2023)
- [Açık Kaynak Kodlu Yazılım Seferberliği](https://www.sabah.com.tr/yazarlar/sirt/2023/08/12/acik-kaynak-kodlu-yazilim-seferberligi) (2023)
- [Yerli ve Milli İşletim Sistemine Geçen İlk Belediye: Eyüpsultan Belediyesi](https://www.gzt.com/jurnalist/yerli-ve-milli-isletim-sistemine-gecen-ilk-belediye-eyupsultan-belediyesi-3431865), [2](https://t24.com.tr/haber/eyupsultan-belediyesinden-2-milyon-dolarlik-tasarruf,677546), [3](https://www.hukukihaber.net/eyupsultan-belediyesi-turkiyenin-siber-kalkani-ahtapot-icin-kollari-sivadi) (2018-2019)

## Video

- [Açık Seminer| Eyüpsultan Belediyesi'nde Pardus Dönüşümü ve Pardus'tan Haberler](https://www.youtube.com/watch?v=3IJwh6pYx9U)
- [Kamuda Açık Kaynak Kodlu Yazılıma Geçiş](https://www.youtube.com/watch?v=VrIWTaE2hto)

## Yazılım

- [.NET](https://learn.microsoft.com/tr-tr/dotnet/welcome) - Çok Farklı Türde Uygulama Oluşturmaya Yönelik Platformlar Arası Açık kaynak Geliştirici Platformu
- [Ahtapot](https://ahtapot.org.tr/) - Bütünleşik Siber Güvenlik Sistemi
- [Apache Guacamole](https://guacamole.apache.org/) - Platformlar Arası, İstemcisiz Uzak Masaüstü Ağ Geçidi
- [Cacti](https://www.cacti.net/) - Genişletilebilir Operasyonel İzleme ve Hata Yönetimi Çatısı
- [Coslat Hotspot](https://coslat.com/5651-hotspot-cozumleri) - Kamuya Açık Kablosuz Ağ Hizmetleri Yönetim Sistemi
- [ClamAV](https://www.clamav.net/) - Çok Platformlu Antivirüs Yazılımı
- [Django](https://www.djangoproject.com/) - Python ile Hazırlanmış Yüksek Seviyeli Web Çatısı
- [Drupal](https://www.drupal.org/) - Açık Kaynak İçerik Yönetim Sistemi ve İçerik Yönetime Odaklı Altyapı Yazılımı
- [elasticsearch](https://www.elastic.co/) - RESTful Arama ve Analiz Motoru
- [Engerek](https://www.pardus.org.tr/projeler/engerek/) - Kimlik Yönetim Sistemi
- [ETAP](https://www.etap.org.tr/) - Pardus Etkileşimli Tahta Arayüzü
- [Evolution](https://wiki.gnome.org/Apps/Evolution) - Masaüstü E-posta Uygulaması
- [Fedora](https://fedoraproject.org/) - Bir Linux Dağıtımı
- [Flask](https://flask.palletsprojects.com/) - Python ile Yazılmış Mikro Web Çatısı
- [Flutter](https://flutter.dev/) - Google Tarafından Oluşturulan Açık Kaynaklı UI Yazılım Geliştirme Kiti
- [Git](https://git-scm.com/) - Yazılım Versiyon Takip Sistemi
- [GitLab](https://about.gitlab.com/) - Kaynak Kod ve Proje Yönetim Platformu
- [GLPI](https://glpi-project.org/) - Açık Kaynak BT Varlık Yönetim Sistemi
- [Grafana](https://grafana.com/) - Açık Kaynak Veri Analizi ve İzleme Yazılımı
- [Jitsi Meet](https://meet.jit.si/) - Video Konferans ve Anlık Mesajlaşma Sistemi
- [LibreOffice](https://tr.libreoffice.org/) - The Document Foundation Tarafından Geliştirilen Açık kaynak Ofis Yazılımı Seti
- [Liderahenk](https://liderahenk.org/) - Merkezi Yönetim Sistemi
- [Liman MYS](https://liman.havelsan.com.tr/) - Açık Kaynak Merkezi Yönetim Sistemi
- [Lime Survey](https://www.limesurvey.org/) - Anket Uygulaması
- [Moodle](https://moodle.org/) - Uzaktan Eğitim Sistemi
- [MongoDB](https://www.mongodb.com/) - C++ ile Geliştirilmiş Açık Kaynak NoSQL Veritabanı
- [MySQL](https://www.mysql.com/) - Çoklu İş Parçacıklı, Çok Kullanıcılı, Hızlı ve Sağlam Bir Veri Tabanı Yönetim Sistemi
- [NoMachine](https://www.nomachine.com/) - Uzaktan Destek Yazılımı
- [Nextcloud](https://nextcloud.com/) - Dosya Barındırma, Dosya Senkronizasyonu Sistemi
- [osquery](https://github.com/osquery/osquery) - SQL Destekli İşletim Sistemi İzleme ve Analitik Yazılımı
- [Pardus](https://www.pardus.org.tr/) - TÜBİTAK ULAKBİM Tarafından Geliştirilen Debian Tabanlı GNU/Linux Dağıtımı
- [PassBox](https://passbox.io/) - İşletmeler İçin Güvenli Self Servis Şifre Sıfırlama ve OTP
- [PHP](https://www.php.net/) - Çok Geniş Kullanımlı, Genel Amaçlı, İçerisine HTML Gömülebilen Betik ve Programlama Dili
- [PostgreSQL](https://www.postgresql.org/) - Açık Kaynak Güçlü İlişkisel Veritabanı Yönetim Sistemi
- [Proxmox](https://www.proxmox.com/) - Sanallaştırma Ortamı
- [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway) - E-posta Güvenlik Çözümü
- [Redis](https://redis.io/) - Veri Yapısı Sunucusu
- [Redmine](https://www.redmine.org/) - Proje Yönetim Sistemi
- [Rocket.Chat](https://www.rocket.chat/) - Anlık İleti ve Video Konferans Yazılımı
- [Rsyslog](https://www.rsyslog.com/) - Hızlı Log İşleme Sistemi
- [Sambabox](https://sambabox.io/) - Samba4 Alt Yapılı Aktif Dizin Yönetimi
- [SonarQube](https://www.sonarsource.com/products/sonarqube/) - Kod Kalitesi, Güvenlik ve Statik Analiz Aracı
- [TaliaDomain](https://taliadomain.com/) - Açık Kaynak Domain Kurulum, Yönetim ve İzleme Sistemi
- [Ubuntu](https://ubuntu.com/) - Bir Linux Dağıtımı
- [Wazuh](https://wazuh.com/) - Uç Noktalar ve Bulut İçin XDR ve SIEM Korumasını Birleştiren Açık Kaynak Güvenlik Platformu
- [WordPress](https://tr.wordpress.org/) - PHP Dilinde Yazılmış Açık Kaynak İçerik Yönetim Sistemi
- [Zabbix](https://www.zabbix.com/) - Açık Kaynak Ağ ve Uygulama İzleme Yazılımı
- [Zimbra](https://www.zimbra.com/) - E-posta Sunucusu

## Donanım

## Firma

- [Açık Kaynak Kodlu Yazılım Ekosistemi Firma Bilgi Formu](https://forms.gle/RrbwKTqA3yCmYiDT8)

Aşağıda kamuda açık kaynak kodlu yazılım kullanımı konusunda destek/hizmet veren firmaların alfabetik bir listesini bulabilirsiniz.

- [Antandros Teknoloji](https://akky.com.tr/)
- [Artistanbul](https://www.artistanbul.io/)
- [BeyazNet](https://www.beyaz.net/)
- [Özgür Yazılım A.Ş.](https://www.ozguryazilim.com.tr/)
- [Profelis](https://profelis.com.tr/)

## Kurum

- [Hazine ve Maliye Bakanlığı Bilgi Teknolojileri Genel Müdürlüğü](https://btgm.hmb.gov.tr/), [2](https://btgm.hmb.gov.tr/haberler/gelecegi-insa-ederken-acik-kaynak-kodlu-yazilimlarin-gucuyle-ilerliyoruz), [3](https://btgm.hmb.gov.tr/haberler/acik-kaynak-kodlu-yazilimlar-ile-gelistirdigimiz-kamu-filo-bilgi-sistemini-devreye-aliyoruz)
- [Okullarda Milli İşletim Sistemi Pardus Yaygınlaştırılacak](https://www.meb.gov.tr/okullarda-mill-isletim-sistemi-pardus-yayginlastirilacak/haber/31964/tr)
- [İllere Bağlı İlçelerin Deprem Tehlike Değerlerinin Açık Kaynak Kodlu CBS ile Belirlenmesi](https://webdosya.csb.gov.tr/db/cbsgunu/webmenu/webmenu15756.pdf)

## Dernek/Platform

- [Linux Kullanıcıları Derneği](https://www.lkd.org.tr/)
- [Özgür Yazılım Derneği](https://www.oyd.org.tr/)
- [Özgür Yazılım Kullanıcıları Derneği](https://www.oyakder.org.tr/)
- [TOBB Türkiye Yazılım Meclisi](https://tobbyazilim.org/)
- [Türkiye Açık Kaynak Platformu](https://www.turkiyeacikkaynakplatformu.com/)

## Kişi

- [Ali Orhun AKKİRMAN](https://www.linkedin.com/in/alorak), [2](https://github.com/aliorhun)
- [Hüseyin GÜÇ](https://www.linkedin.com/in/huseyin-guc), [2](https://opensource.com/users/hguc)

## İnternet Sitesi

## Lisans

Rehberin Temmuz 2023 tarihli 1.0 sürümüne göre AKKY kapsamında kabul edilebilecek lisansların listesi aşağıdaki gibidir. İlgili lisansların yayımlanan son sürümleri kullanılmalıdır.

- BSD Zero Clause License
- Academic Free License
- GNU Affero General Public License
- Apache License
- Artistic License
- BSD 2-Clause "Simplified" License
- BSD 3-Clause Clear License
- BSD 3-Clause "New" or "Revised" License
- BSD 4-Clause "Original" or "Old" License
- Boost Software License
- Creative Commons Attribution International
- Creative Commons Attribution Share Alike International
- Creative Commons Zero Universal
- CeCILL Free Software License Agreement
- Educational Community License
- Eclipse Public License
- European Union Public License
- GNU Free Documentation License
- GNU General Public License
- ISC License
- GNU Lesser General Public License
- LaTeX Project Public License
- MIT No Attribution
- MIT License
- Mozilla Public License
- Microsoft Public License
- Microsoft Reciprocal License
- Mulan Permissive Software License
- University of Illinois/NCSA Open Source License
- Open Data Commons Open Database License
- SIL Open Font License
- Open Software License
- PostgreSQL License
- The Unlicense
- Universal Permissive License
- Vim License
- zlib License

Lisanslarla ilgili bilgi alınabilecek çeşitli siteler şöyledir:

- [Özgür Lisanslar](https://www.ozgurlisanslar.org.tr/) - Linux Kullanıcıları Derneği Tarafından Yapılan Yaygın Özgür Lisansların Türkçeleştirilmesi Çalışması
- [Özgür yazılım lisansları - Vikipedi](https://tr.wikipedia.org/wiki/Kategori:%C3%96zg%C3%BCr_yaz%C4%B1l%C4%B1m_lisanslar%C4%B1) - Özgür Yazılım Lisansları Listesi
- [Lisanslar - GNU Projesi](https://www.gnu.org/licenses/licenses.tr.html) - Özgür Yazılım Lisansları

## Makale

- [Kamuda Açık Kaynak Kodlu Yazılım Kullanımı Genelgesi](https://www.bilecik.edu.tr/dosya/19377_5532_AKKY%20Sunum.pdf) - Bilecik Şeyh Edebali Üniversitesi Bilgi İşlem Daire Başkanlığı (2023)
- [Kamu Kurumlarında Açık Kaynak Kodlu Yazılım Kullanımına Karşı Yönetici Direnci Üzerine Bir Araştırma](https://earsiv.kmu.edu.tr/xmlui/bitstream/handle/11492/5457/%C3%96zcan%2C%20Mahmut.pdf?sequence=1&isAllowed=y) - Mahmut ÖZCAN (2020)
- [İşletmelerde Milli ve Açık Kaynak Kodlu Bir İşletim Sistemi Uygulama Süreci: Pardus Örneği](http://acikerisim.gedik.edu.tr:8080/xmlui/bitstream/handle/11501/134/%20BRAH%20M%20SARIKAYA.pdf?sequence=1) - İbrahim SARIKAYA (2019)
- [Ülkemizde Kamu Kuruluşlarında Kullanılan Yazılımların Yerli Yazılım İle Tek Çatı Altında Toplanması](https://www.sadab.org/FileUpload/bs701867/File/ulkemizde_kamu_kuruluslarinda_yerli_yazilim_son.pdf) - Alper AYTEKİN, Fatma TÜMİNÇİN (2018)
- [Kamu Kurumlarında Açık Kaynak Kodlu Yazılımların Kullanımı](https://dergipark.org.tr/tr/pub/seyad/issue/53367/709521) - Mustafa Fedai ÇAVUŞ, Halenur Soysal KURT (2017)
- [Özgür Açık Kaynak Yazılım Stratejilerinin Türkiye Bilgi Toplumu Hedefleri İçerisindeki Önemi](https://research.sabanciuniv.edu/id/eprint/30082/1/Ozgur_Acik_Kaynak_Yazilim_Stratejilerinin_Turkiye_Bilgi_Toplumu_Hedefleri_Icerisindeki_Onemi.pdf) - Naci Dai, Sait Ölmez (2016)
- [Kamuda Açık Kaynak Kodlu Yazılım Kullanımı](http://www.bilgitoplumu.gov.tr/Documents/1/Diger/Kamuda_Acik_Kaynak_Kullanimi_Calisma_Raporu.pdf) - M. Rașit ÖZDAȘ (2012)

## Örnek

- [Ankara Üniversitesi Bilgi İşlem Daire Başkanlığı ](https://bid.ankara.edu.tr/2024/01/01/e-beyas-acik-kaynak-kod-donusumu/)
- [Bilecik Şeyh Edebali Üniversitesi Bilgi İşlem Daire Başkanlığı AKKY Genelgesi Çalışması](https://wiki.bilecik.edu.tr/tr/YARDIM/akkygenelge)
- [Diyanet Açık Kaynak](https://acikkaynak.diyanet.gov.tr/)
- [Selçuk Üniversitesi Bilgi İşlem Daire Başkanlığı](https://www.selcuk.edu.tr/Birim/daire-baskanliklari/bilgi_islem/1951/acik-kaynak/53178)
- [Ziraat Katılım Bankası](https://eksisozluk111.com/entry/139301960)

