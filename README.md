# Dört Ulus: Bükücüler Arenası

*Avatar: The Last Airbender* ve *The Legend of Korra* evrenlerinden esinlenen, tarayıcıda çalışan **2D element bükme dövüş oyunu** (hayran projesi). Tüm grafikler kodla çizilir; kurulum gerekmez.

## Nasıl oynanır?

`index.html` dosyasını herhangi bir modern tarayıcıda açın (iPhone / iPad dahil). Kurulum yok.

### Modlar
- **⛰ Macera Modu** — dizinin olay sırasına göre 15 seviye (Kitap 1: Su → Korra Efsanesi). Her seviye bir sonrakini açar; can durumuna göre 1-3 yıldız. Son seviye: Avatar Durumu'ndaki Korra.
- **⚔ Hızlı Dövüş** — bilgisayara karşı, 3 zorluk.
- **👥 Çok Oyunculu** — aynı ekranda 2 kişi: klavye (WASD / oklar), **telefonda bölünmüş dokunmatik ekran** (sol yarı 1P, sağ yarı 2P) veya **2 oyun kolu** (PS / Xbox / MFi).
- **♾ Sonsuz Mod** — dalga dalga gelen, giderek güçlenen rakipler. Dalgalar arası %30 can yenilenir; rekor kaydedilir.
- **👁 İzle** — bilgisayar vs bilgisayar.

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

### iPhone (16 / 17 Pro dahil)
Telefonu yan çevirince oyun dünyası ekranın en-boy oranına göre genişler ve **tüm ekranı doldurur** (Dynamic Island / çentik bölgesine de taşar, arayüz güvenli alanda kalır). Safari'de **Paylaş → Ana Ekrana Ekle** ile açarsanız tarayıcı çubukları da gizlenir.

### Mekanikler
- **Dört element doğru dağılımla:** Su (Katara; Amon kan bükme), Toprak (Toph, Bumi), Ateş (Zuko, Iroh, Azula – mavi ateş, Ozai), Hava (Zaheer). **Avatarlar (Aang, Korra) dört elementin hepsini büker** — temel saldırı her atışta sıradaki elemente geçer.
- **Element sesleri:** ateş (kükreme + çıtırtı), mavi ateş (tıslama), su (sıçrama + baloncuk), buz, toprak (gümbürtü + kaya çatırtısı), hava (rüzgar uğultusu), şimşek, kan bükme. Pentatonik prosedürel müzik ve taiko davulu.
- **Görsel:** alev dilli ateş, parlak su, gölgeli kayalar, dinamik kamera zoom'u, paralaks arka plan, vuruş donması, ışıma efektleri.
- **Chi** (mavi) yetenekler için harcanır; **Ulti** (altın) vurdukça dolar. Blok %75 azaltır ama chi yer; chi biterse gard kırılır.
- **Durum etkileri:** yanma, yavaşlama, sersemleme, **chi engelleme** (bükücü olmayanlar bağışık). Zıt mermiler havada birbirini söndürür. Iroh şimşeği yönlendirir.
- **Arena eşyaları:** Yasemin Çayı (can), Lahana (chi + ulti), Momo (hız).
- **Arenalar:** Güney Hava Tapınağı, Kuzey Su Kabilesi (dolunay + kutup ışıkları), Ba Sing Se, Ateş Ulusu Sarayı (volkan), Cumhuriyet Şehri (yağmur).

## Karakterler ve araştırma özeti

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
| **Zaheer** | Kızıl Lotus · Hava | Anarşist; Harmonik Yakınsama ile hava bükücü oldu; Laghima'dan beri uçan ilk kişi; boğma | Hava Bıçağı · Uçuş · **Havasız Bırakma** |

Yardımcılar: **Appa** (Sokka'nın ultisi), **Momo**, **Lahana Satıcısı**, **Yasemin Çayı**.
Oyun içindeki **Karakter Rehberi** ekranında her karakterin ayrıntılı biyografisi, bükme stilleri (Tai Chi, Hung Gar, Kuzey Shaolin, Baguazhang) ve alt teknikler anlatılır.

---
*Bu, resmi olmayan bir hayran projesidir; Avatar karakterleri ve dünyası Nickelodeon/Paramount'a aittir.*
