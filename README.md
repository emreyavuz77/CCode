# Dört Ulus: Bükücüler Arenası

*Avatar: The Last Airbender* ve *The Legend of Korra* evrenlerinden esinlenen, tarayıcıda çalışan **2D element bükme dövüş oyunu** (hayran projesi). Tüm grafikler kodla çizilir; kurulum gerekmez.

## Nasıl oynanır?

`index.html` dosyasını herhangi bir modern tarayıcıda açın (iPhone / iPad dahil). Kurulum yok.

### Modlar
- **⛰ Macera Modu** — dizinin olay sırasına göre 15 seviye; **her seviyeden önce ara sahne** (diyaloglu hikâye), sonunda final sahnesi. Can durumuna göre 1-3 yıldız.
- **⚔ Hızlı Dövüş** — bilgisayara karşı, 3 zorluk.
- **🌐 Çevrimiçi** — **iki farklı telefondan aynı maç**: biri "Oda Kur" ile 4 haneli kod alır, diğeri kodu girip katılır. (claude.ai'deki `room` yeteneğini kullanır; arkadaşın oyunu açabilmesi için Paylaş menüsünden paylaşılmalı.)
- **👥 Aynı Ekran** — 2 kişi tek cihazda: klavye, bölünmüş dokunmatik ekran veya 2 oyun kolu.
- **♾ Sonsuz Mod** — giderek güçlenen rakip dalgaları, rekor kaydı.
- **🥋 Antrenman** — sınırsız süre/can/chi, hasar ve kombo sayacı, kukla davranışı (durgun / blok / zıplar / karşılık verir), hareket listesi.
- **👁 İzle** — bilgisayar vs bilgisayar.

### Kombolar
- **↑ + saldırı:** Yükselen Darbe (elemente göre: ateş/su/kaya/hava sütunu veya silah)
- **↓ + saldırı (yerde):** Süpürme — rakibi devirir
- **↓ + saldırı (havada):** Dalış — yere çarpınca şok dalgası
- **Art arda vuruşlar:** 3+ vuruşta kombo bonusu (+%40'a kadar hasar), ekranda "N VURUŞ"

### Arena olayları (açılıp kapatılabilir)
Hava Tapınağı: rüzgar akımı · Kuzey Su Kabilesi: dolunay (su bükücüler +%30) · Ba Sing Se: toprak treni · Ateş Ulusu: kuyrukluyıldız yağmuru · Cumhuriyet Şehri: Eşitlikçi elektrik ağları.

### Kıyafetler
Her karakterin kıyafetleri seviye atladıkça açılır: örn. **Mavi Ruh Zuko**, **Ateş Lordu Zuko**, Aang **Ateş Ulusu Okulu**, Katara **Kış Parkası**, Iroh **Beyaz Lotus**, Azula **Kyoshi Kılığı**, Korra **Fire Ferrets**, Toph **Metal Polis Şefi**… ve herkes için **Gölge** (Lv 7) ile **Altın Usta** (Lv 10).

### Başarımlar ve günlük görevler
22 başarım (İlk Zafer, Dört Ulus, Kombo Ustası, Batı'nın Ejderhası, Benim Lahanalarım!…) ve her gün değişen 3 günlük görev — hepsi XP kazandırır.

### Seviye atlama
Her maçta XP kazanılır (hasar, galibiyet, seviye/dalga). Oyuncu seviyesi ve rütbesi ana menüde görünür:
Çırak → Öğrenci → Savaşçı → Usta → Büyük Usta → Beyaz Lotus → Avatar. İlerleme bu cihazda saklanır.

### Kontroller
| | 1. Oyuncu | 2. Oyuncu | Oyun kolu | Dokunmatik |
|---|---|---|---|---|
| Hareket | `A` `D` | `←` `→` | Sol çubuk / D-pad | Joystick (sola/sağa) |
| Zıpla / süzül | `W` | `↑` | A (✕) | ▲ veya joystick yukarı |
| Blok | `S` | `↓` | B (○) / LB | Joystick aşağı |
| Temel saldırı | `F` | `K` | X (□) | ⚔ |
| Özel yetenek | `G` | `L` | Y (△) | ★ |
| Ulti | `H` | `;` | RB / RT | ✦ |
| Duraklat | `Esc` / `P` | | Start | ❚❚ |

### iPhone 16 / 17 Pro'da tam ekran
iPhone'da Safari, web sayfalarının adres çubuğunu gizlemesine izin vermez; gerçek tam ekran için oyun **ana ekrana eklenmiş uygulama** olarak açılmalıdır:

1. (Bir kez) GitHub'da **Settings → Pages → Build and deployment → Source: Deploy from a branch**, Branch: `claude/intelligent-bohr-ta36oi`, klasör `/ (root)` → **Save**. Birkaç dakika sonra oyun şu adreste yayında olur: <https://emreyavuz77.github.io/CCode/>
2. iPhone'da bu adresi **Safari** ile aç → **Paylaş ⬆ → Ana Ekrana Ekle → Ekle**.
3. Ana ekrandaki **Dört Ulus** simgesinden aç, telefonu yan çevir: Safari çubukları olmadan, Dynamic Island'a kadar tam ekran.

Oyundaki sağ üst **⛶** düğmesi bu adımları gösterir; tam ekran desteği olan tarayıcılarda (Android, iPad, bilgisayar) doğrudan tam ekrana geçer. Yatayda oyun dünyası ekran oranına göre genişler (siyah kenar kalmaz), arayüz çentik/Dynamic Island güvenli alanında kalır.
Not: **Çevrimiçi maç** yalnızca claude.ai linkinde çalışır; ana ekran sürümünde diğer tüm modlar çalışır.

### Mekanikler
- **Dört element doğru dağılımla:** Su (Katara; Amon kan bükme), Toprak (Toph, Bumi), Ateş (Zuko, Iroh, Azula – mavi ateş, Ozai), Hava (Zaheer). **Avatarlar (Aang, Korra) dört elementin hepsini büker** — temel saldırı her atışta sıradaki elemente geçer.
- **Element sesleri:** ateş (kükreme + çıtırtı), mavi ateş (tıslama), su (sıçrama + baloncuk), buz, toprak (gümbürtü + kaya çatırtısı), hava (rüzgar uğultusu), şimşek, kan bükme. Pentatonik prosedürel müzik ve taiko davulu.
- **Görsel:** alev dilli ateş, parlak su, gölgeli kayalar, dinamik kamera zoom'u, paralaks arka plan, vuruş donması, ışıma efektleri.
- **Chi** (mavi) yetenekler için harcanır; **Ulti** (altın) vurdukça dolar. Blok %75 azaltır ama chi yer; chi biterse gard kırılır.
- **Durum etkileri:** yanma, yavaşlama, sersemleme, **chi engelleme** (bükücü olmayanlar bağışık). Zıt mermiler havada birbirini söndürür. Iroh şimşeği yönlendirir.
- **Arena eşyaları:** Yasemin Çayı (can), Lahana (chi + ulti), Momo (hız).
- **Arenalar:** Güney Hava Tapınağı, Kuzey Su Kabilesi (dolunay + kutup ışıkları), Ba Sing Se, Ateş Ulusu Sarayı (volkan), Cumhuriyet Şehri (yağmur).

## Karakterler ve araştırma özeti (25 karakter)

| Karakter | Ulus / Element | Kanondaki özellikler | Oyundaki yetenekler (Temel · Özel · **Ulti**) / Pasif |
|---|---|---|---|
| **Aang** | Hava Göçebeleri · Avatar | Son hava bükücü, 100 yıl buzda kaldı; planör, hava küresi; Avatar Durumu; Ozai'nin bükmesini enerji bükmeyle aldı | Dört Element (hava→su→toprak→ateş) · Hava Küresi · **Avatar Durumu** (uçar, 4 element patlaması). Pasif: süzülme, çift zıplama |
| **Katara** | Güney Su Kabilesi · Su | Usta Pakku'yu yendi; şifacı; Hama'dan kan bükme; Azula'yı yendi | Su Kırbacı · Buz Hançerleri · **Kan Bükme**. Pasif: can yenileme |
| **Sokka** | Güney Su Kabilesi · Bükücü değil | Stratejist, mucit; bumerang; Piandao'nun öğrencisi, göktaşı “Uzay Kılıcı” | Bumerang (geri döner) · Uzay Kılıcı · **Yip Yip! – Appa**. Pasif: chi engellemeye bağışık |
| **Zuko** | Ateş Ulusu · Ateş | Sürgün prens, Agni Kai yarası; Mavi Ruh; ejderhalardan ateşin özünü öğrendi; Aang'in hocası | Ateş Yumruğu · Ateş Tekmesi · **Ejderha Dansı**. Pasif: yakma |
| **Toph** | Toprak Krallığı · Toprak | Kör; sismik algı; porsuk-köstebeklerden öğrendi; metal bükmeyi icat etti; “Kör Haydut” | Kaya Fırlatma · Toprak Duvarı · **Sismik Deprem** (yerdekini vurur). Pasif: savrulma direnci |
| **General Iroh** | Ateş Ulusu · Ateş | “Batı'nın Ejderhası”; çay tutkunu; şimşek yönlendirmeyi icat etti; Beyaz Lotus | Ateş Nefesi · Şimşek Yönlendirme (karşı duruş) · **Batı'nın Ejderhası**. Pasif: hızlı chi |
| **Azula** | Ateş Ulusu · Ateş | Dahi; mavi ateş ve şimşek; Ba Sing Se'yi ele geçirdi; kusursuzluk takıntısı | Mavi Ateş · Mavi Alev Jeti · **Şimşek**. Pasif: %15 kritik |
| **Ateş Lordu Ozai** | Ateş Ulusu · Ateş | Yüz Yıl Savaşı'nın tiranı; Sozin'in Kuyrukluyıldızı; ateş jetleriyle uçuş | Ateş Topu · Ateş Jeti Uçuşu · **Sozin'in Kuyrukluyıldızı**. Pasif: 125 can |
| **Suki** | Kyoshi Adası · Bükücü değil | Kyoshi Savaşçıları lideri; yelpaze ve kılıç; Kaynayan Kaya'dan kaçış | Yelpaze Darbesi · Kyoshi Hamlesi · **Kyoshi Savaşçıları**. Pasif: çok hızlı |
| **Ty Lee** | Ateş Ulusu · Bükücü değil | Sirk akrobatı; chi engelleme; aura görür; sonra Kyoshi savaşçısı | Chi Engelleme · Akrobatik Takla · **Basınç Noktası Fırtınası**. Pasif: üçlü zıplama |
| **Mai** | Ateş Ulusu · Bükücü değil | Bıçak/stiletto ustası; rakibi duvara çiviler; Zuko için Azula'ya karşı geldi | Bıçak Atışı · Duvara Çivileme · **Bıçak Fırtınası** |
| **Kral Bumi** | Omashu · Toprak | Aang'in 112 yaşındaki “deli dahi” arkadaşı; Omashu'yu tek başına kurtardı | Dev Kaya · Toprak Dalgası · **Dağ Devirme**. Pasif: 120 can |
| **Korra** | Güney Su Kabilesi · Avatar | Aang'den sonraki Avatar; pro-bending; havayı en son öğrendi; Amon, Zaheer, Kuvira'ya karşı | Element Kombosu (ateş→su→toprak→hava) · Toprak Sütunu · **Avatar Durumu: Hortum** |
| **Amon** | Eşitlikçiler · Kan bükme (gizli) | Maskeli lider; aslında kan bükücü Noatak; bükücülüğü kalıcı alabilir | Kesin Darbe · Kan Bükme Tutuşu · **Bükücülüğü Al**. Pasif: kan bükme + chi engellemeye bağışık |
| **Mako** | Cumhuriyet Şehri · Ateş | Fire Ferrets kaptanı, santralde şimşek üretti, kırmızı atkı, sonra dedektif | Seri Ateş Yumrukları · Şimşek Darbesi · **Şimşek Fırtınası** |
| **Bolin** | Cumhuriyet Şehri · Toprak | Mako'nun kardeşi, lav bükücü, Pabu, "Nuktuk" film yıldızı | Disk Atışı · Lav Havuzu · **Lav Seli** |
| **Asami Sato** | Cumhuriyet Şehri · Bükücü değil | Future Industries mühendisi, elektrikli eldiven, usta sürücü | Elektrikli Eldiven · Bola · **Satomobil** |
| **Tenzin** | Hava Göçebeleri · Hava | Aang ile Katara'nın oğlu, Korra'nın hava hocası | Hava Dalgası · Hava Kalkanı · **Büyük Rüzgar** |
| **Lin Beifong** | Cumhuriyet Şehri Polisi · Toprak (metal) | Toph'un kızı, metal bükücü polis şefi, yanağında yara izleri | Metal Kablo · Metal Zırh · **Kablo Hapsi** |
| **Kuvira** | Toprak İmparatorluğu · Toprak (metal) | "Büyük Birleştirici", metal şeritler, ruh enerjisi topu | Metal Şeritler · Şerit Kırbacı · **Ruh Enerjisi Topu** (yönlendirilemez) |
| **Jet** | Özgürlük Savaşçıları · Bükücü değil | Kancalı kılıçlar, ağzında saman çöpü, intikamcı lider | Kancalı Kılıçlar · Kanca Atılışı · **Özgürlük Savaşçıları** (ok yağmuru) |
| **Patlama Adam** | Ateş Ulusu suikastçısı · Ateş (yanma bükme) | Üçüncü göz dövmesi, metal protezler, "Sparky Sparky Boom Man" | Patlama Işını · Uzak Patlama · **Dev Patlama** |
| **Hama** | Güney Su Kabilesi · Su (kan) | Kan bükmeyi keşfeden kişi, nemden su çeker | Nem Hançerleri · Bitki Özü · **Dolunay Kan Bükmesi** |
| **Usta Pakku** | Kuzey Su Kabilesi · Su | Kuzey'in su ustası, Kanna ile evlendi, Beyaz Lotus | Üçlü Kırbaç · Su Kalkanı · **Buz Dalgası** |
| **Zaheer** | Kızıl Lotus · Hava | Anarşist; Harmonik Yakınsama ile hava bükücü oldu; Laghima'dan beri uçan ilk kişi; boğma | Hava Bıçağı · Uçuş · **Havasız Bırakma** |

Yardımcılar: **Appa** (Sokka'nın ultisi), **Momo**, **Lahana Satıcısı**, **Yasemin Çayı**.
Oyun içindeki **Karakter Rehberi** ekranında her karakterin ayrıntılı biyografisi, bükme stilleri (Tai Chi, Hung Gar, Kuzey Shaolin, Baguazhang) ve alt teknikler anlatılır.

---
*Bu, resmi olmayan bir hayran projesidir; Avatar karakterleri ve dünyası Nickelodeon/Paramount'a aittir.*
