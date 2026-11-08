# Dört Ulus: Bükücüler Arenası

*Avatar: The Last Airbender* ve *The Legend of Korra* evrenlerinden esinlenen, tarayıcıda çalışan **2D element bükme dövüş oyunu** (hayran projesi). Tüm grafikler kodla çizilir; kurulum gerekmez.

## Nasıl oynanır?

`index.html` dosyasını herhangi bir modern tarayıcıda açın. Hepsi bu.

| | 1. Oyuncu | 2. Oyuncu |
|---|---|---|
| Hareket | `A` `D` | `←` `→` |
| Zıpla / süzül (havada basılı tut) | `W` | `↑` |
| Blok (blok + zıpla = platformdan in) | `S` | `↓` |
| Temel saldırı | `F` | `K` / `,` / `Num1` |
| Özel yetenek | `G` | `L` / `.` / `Num2` |
| Ulti (altın bar dolunca) | `H` | `;` / `/` / `Num3` |

`Esc`/`P` duraklat, `M` ses. Dokunmatik ekranlarda ekran butonları çıkar.

**Modlar:** Bilgisayara karşı (3 zorluk), aynı klavyede 2 oyunculu, Bilgisayar vs Bilgisayar izleme.
**Kurallar:** 3 raunttan 2'sini alan kazanır (raunt 99 sn).

### Mekanikler
- **Chi** (mavi): yetenekler chi harcar, kendiliğinden dolar. Blok, hasarı %75 azaltır ama chi yer; chi biterse **gard kırılır**.
- **Ulti** (altın): vurdukça ve hasar aldıkça dolar.
- **Durum etkileri:** yanma (ateş), yavaşlama (buz/su), sersemleme, **chi engelleme** (bükücü sadece yumruk atabilir; bükücü olmayanlar bağışık).
- **Mermi çarpışması:** zıt mermiler havada birbirini söndürür.
- **Toprak duvarları** mermileri durdurur; **Iroh** mermileri ve Azula'nın şimşeğini yönlendirip geri yollar.
- **Arena eşyaları:** Yasemin Çayı (can, Iroh'a 2 kat), Lahana (“Benim lahanalarım!” → chi + ulti), Momo (hız).
- **Arenalar:** Güney Hava Tapınağı, Kuzey Su Kabilesi (dolunay), Ba Sing Se, Ateş Ulusu Sarayı, Cumhuriyet Şehri.

## Karakterler ve araştırma özeti

| Karakter | Ulus / Element | Kanondaki özellikler | Oyundaki yetenekler (Temel · Özel · **Ulti**) / Pasif |
|---|---|---|---|
| **Aang** | Hava Göçebeleri · Avatar | Son hava bükücü, 100 yıl buzda kaldı; planör, hava küresi; Avatar Durumu; Ozai'nin bükmesini enerji bükmeyle aldı | Hava Darbesi · Hava Küresi · **Avatar Durumu** (uçar, 4 element). Pasif: süzülme, çift zıplama |
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
| **Korra** | Güney Su Kabilesi · Avatar | Aang'den sonraki Avatar; pro-bending; havayı en son öğrendi; Amon, Zaheer, Kuvira'ya karşı | Element Kombosu · Toprak Sütunu · **Avatar Durumu: Hortum** |
| **Amon** | Eşitlikçiler · Kan bükme (gizli) | Maskeli lider; aslında kan bükücü Noatak; bükücülüğü kalıcı alabilir | Kesin Darbe · Kan Bükme Tutuşu · **Bükücülüğü Al**. Pasif: kan bükme + chi engellemeye bağışık |
| **Zaheer** | Kızıl Lotus · Hava | Anarşist; Harmonik Yakınsama ile hava bükücü oldu; Laghima'dan beri uçan ilk kişi; boğma | Hava Bıçağı · Uçuş · **Havasız Bırakma** |

Yardımcılar: **Appa** (Sokka'nın ultisi), **Momo**, **Lahana Satıcısı**, **Yasemin Çayı**.
Oyun içindeki **Karakter Rehberi** ekranında her karakterin ayrıntılı biyografisi, bükme stilleri (Tai Chi, Hung Gar, Kuzey Shaolin, Baguazhang) ve alt teknikler anlatılır.

---
*Bu, resmi olmayan bir hayran projesidir; Avatar karakterleri ve dünyası Nickelodeon/Paramount'a aittir.*
