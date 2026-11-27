# Ajans oyun kitabı

Bu dosya Kazanç Ofisi'nin yedi ajanının site üretirken uyduğu ölçütlerdir. Kaynak: Awwwards jüri ölçütleri, WCAG 2.2 AA, Core Web Vitals ve MIT/Apache lisanslı açık kaynak skiller. Uydurma kanıt üretilmez.

## 1. Strateji ve brief — Duru · Strateji

_Keşif, konumlandırma, kanıt envanteri, bilgi mimarisi ve tek ana eylem._

# 01 · Strateji ve brief

## Ne zaman

Her üretimin ilk adımı. Site türü, sektör veya bütçe ne olursa olsun brief
yazılmadan tek satır kod yazılmaz.

## Girdi

- İşletme adı, sektör, şehir/ilçe, telefon, e-posta.
- Varsa gerçek kanıt: yıl, yorum sayısı, puan, sertifika, gerçek fotoğraf, ödül.
- Karar verici: siteyi kim onaylayacak, kimin telefonu çalacak.
- Kısıtlar: mevcut alan adı, marka rengi, zorunlu logo, yasal uyarı.

## Süreç

1. **İşi tek cümlede yaz.** “Ne satıyor, kime, nerede, neden bu işletme?”
2. **Kanıt envanteri çıkar.** Her kanıtı `gerçek` / `müşteriden alınacak` /
   `kullanılmayacak` olarak işaretle. Doğrulanamayan sayı sitede yer almaz.
3. **Rakip üçlüsünü incele.** Aynı şehir ve hizmetteki üç sitenin hero'sunu,
   birincil eylemini ve farkını not et. Kopyalama; boşluğu bul.
4. **Tek ana eylem seç.** Telefon, WhatsApp, randevu, teklif veya sipariş.
   Sayfadaki diğer eylemler en fazla iki tanedir ve birincil CTA'dan küçüktür.
5. **Konumlandırma cümlesini yaz.**
   `[Marka], [bölge]'de [hedef kitle] için [somut fark] sunan [kategori].`
6. **Bilgi mimarisini kur.** Tek sayfa: 7–9 bölüm. Çok sayfa: ana sayfa +
   hizmetler + kanıt/işler + hakkımızda + iletişim.
7. **Ölçümü tanımla.** Birincil KPI (telefon tıklaması, WhatsApp, form) ve
   ikincil KPI (yol tarifi, menü görüntüleme, fiyat sorusu).

## Ölçütler

- Konumlandırma cümlesi 25 kelimeyi geçmez ve rakip adı içermez.
- Hero'da işletme adı + ne yaptığı + nerede + kanıt + CTA vardır.
- Tek sayfada tek H1, tek ana eylem, en fazla 9 içerik bölümü.
- Her bölümün tek işi vardır; aynı bilgi iki bölümde tekrarlanmaz.
- Kanıt yoksa iddia yumuşatılır: “Türkiye'nin en iyisi” yerine
  “İzmir'de 2014'ten beri” gibi doğrulanabilir ifade kullanılır.

## Yapma

- Brief'i 10 sayfalık ajans sunumuna çevirme; bir ekranlık özet yeter.
- “Modern, yenilikçi, kaliteli, kusursuz” gibi kanıtsız sıfatlar kullanma.
- Hedef kitleyi “herkes” yazma; karar vericiyi tarif et.
- Müşterinin onaylamadığı fiyatı, garantiyi veya teslim süresini varsayma.

## Teslim kanıtı

`brief.md` şu başlıkları içerir: işletme, hedef kitle, tek cümle, kanıt
envanteri, rakip notu, bilgi mimarisi, birincil/ikincil eylem, KPI.

## Ajan kullanımı

Duru bu dosyayı `brief.md` ve `satis.md` için kullanır. Deniz, QA sırasında
“hero sözleşmesi” ve “tek ana eylem” maddelerini brief'e karşı denetler.


---

## 2. Metin ve dönüşüm — Ela · Metin

_Hero sözleşmesi, bölüm akışı, CTA, mikro metin ve yerel SEO dili._

# 02 · Metin ve dönüşüm

## Ne zaman

Brief onaylandıktan sonra, tasarım iskeletinden önce. Metin bitmeden hero
yerleşimi kilitlenmez.

## Girdi

`brief.md`: işletme, bölge, hedef kitle, kanıt envanteri, tek ana eylem.

## Hero sözleşmesi (3 saniye)

İlk ekranda beşi birden bulunur:

1. İşletme adı, gerçek ve büyük.
2. Ne yaptığı + nerede yaptığı, açık dilde.
3. Bir gerçek güven sinyali (yıl, puan, uzmanlık, gerçek fotoğraf).
4. Birincil eylem (ara / WhatsApp / randevu / teklif).
5. Tek görsel odak; slider, rozet yığını ve gereksiz etiket yok.

Başlık yaratıcı olabilir; altındaki tek cümle net olmak zorundadır.

## Bölüm akışı

1. Hero — vaat + kanıt + CTA.
2. Hizmetler — 3–6 gerçek hizmet, her biri tek cümle + süre/kapsam.
3. Nasıl çalışır — 3–4 adım, her adımda müşteriye düşen iş.
4. Kanıt — gerçek fotoğraf, gerçek yorum, gerçek sayı; yoksa bu bölüm
   “çalışma biçimi” veya “mekân” olarak yeniden adlandırılır.
5. İtiraz/SSS — fiyat, süre, garanti, bölge, acil durum.
6. Son CTA — aynı birincil eylem, tekrar ve tek cümle.

## Yazım kuralları

- Başlık 6–12 kelime; ilk üç kelimede hizmet veya fayda geçer.
- Cümle ortalaması 12–18 kelime; paragraf en fazla 3 cümle.
- “Siz” dili; emir kipi yerine net eylem (“Randevu al”, “Fiyat sor”).
- Somut isim, sayı, yer ve süre kullan. Belirsiz sıfat yerine kanıt yaz.
- Türkçe karakterler eksiksiz; `İ/ı` ve `ğ/ş/ç/ö/ü` doğru.
- Satır uzunluğu 60–75 karakter; gövde 16–18 px.
- Kısaltma ve jargon yok; sektör terimi gerekiyorsa bir kez açıklanır.
- Sayı ve birim arasında boşluk: “30 dakika”, “2 yıl”, “%50”.

## CTA yazımı

| Zayıf | Güçlü |
|---|---|
| Gönder | Teklif al |
| İletişim | WhatsApp'tan yaz |
| Devam | Randevu seç |
| Tıkla | Yol tarifi al |
| Daha fazla | Hizmetleri gör |

Bir akışta aynı eylemin adı değişmez: “Teklif al” → “Teklifiniz hazır”.

## Mikro metin

- Form etiketi görünür; placeholder etiket yerine geçmez.
- Hata: ne oldu + nasıl düzeltilir (“Telefon 10 haneli olmalı”).
- Boş durum: ne yapılacağını söyle, mood metni yazma.
- Onay: ne olduğunu söyle (“Mesajınız WhatsApp'ta açıldı”).
- Gizlilik: hangi veri, neden, ne kadar süre tutulduğu tek cümlede.

## SEO metni

- H1: hizmet + bölge + fayda. Örnek: “Karşıyaka'da diş implantı”.
- Title 50–60, description 140–160 karakter; ikisi farklı yazılır.
- Her bölümde bir H2; H3'ler H2'nin altında mantıklı sıralanır.
- Anahtar kelimeyi üç kez tekrarlamak yerine bir kez doğru yere koy.
- SSS soruları gerçek arama dilinde: “Diş implantı ne kadar sürer?”

## Yapma

- “Hayalinizdeki deneyim”, “kusursuz harman”, “tutkuyla üretiyoruz” gibi
  AI klişeleri.
- Uydurma yorum, puan, sertifika, “Türkiye'nin lideri”.
- Tüm başlıkları büyük harfe çevirme; tek kelimeyi renkli/italik yapma.
- Aynı cümleyi iki bölümde tekrarlama.

## Teslim kanıtı

`metin.md`: hero başlığı, alt cümle, 3 kart, süreç adımları, SSS (en az 3),
mikro metinler, CTA etiketleri. Deniz, her metni brief'teki kanıt
envanterine karşı denetler.


---

## 3. Sanat yönetimi ve tipografi — Kerem · Sanat

_Tek konsept, palet, tipografi, grid, fotoğraf kadrajı ve şablon tuzakları._

# 03 · Sanat yönetimi ve tipografi

## Ne zaman

Brief ve metin hazır olduktan sonra, arayüz iskeletinden önce. Konsept
cümlesi yazılmadan renk ve font seçilmez.

## Tek konsept

Siteye bir metafor seç ve bütün sayfayı onunla taşı: “gece filmi”, “dergi
kapağı”, “klinik raporu”, “atölye tezgâhı”, “saha defteri”, “vitrin spotu”.
Metafor; başlık tonunu, fotoğraf kadrajını, hareketi ve bölüm ritmini birlikte
belirler. Başka bir markaya kopyalanabiliyorsa konsept zayıftır.

Konsept cümlesi tek satırdır:
`[Metafor] · [zemin] · [vurgu] · [display aile] · [hareket saati]`.

## Palet

- Bir zemin, bir mürekkep ve **üçlü vurgu**: ana renk, tamamlayıcı (180°)
  ve 90° komşu. Kullanım oranı yaklaşık 60/30/10; üçüncü renk yalnız ışıma,
  şerit veya küçük işarette görünür.
- İkinci renk ana rengin tamamlayıcısıdır; Sakin yönde sıcak kil tonudur.
  Her vurgu için üstüne gelen metin rengi ayrıca hesaplanır; 4.5:1 altına
  düşen kombinasyon kullanılmaz.
- Saf siyah/beyaz yerine sıcak kâğıt, taş grisi, sis, kil, gece laciverti
  gibi malzemeden örneklenmiş tonlar kullan.
- Renkleri HSL/OKLCH ile kur; metin/zemin kontrastı en az 4.5:1, büyük metinde 3:1.
- Üç renkli gökkuşağı gradyanı yok. Büyük yüzey tek renk; gradyan yalnız
  yumuşak ışıma veya iki komşu ton arasında kullanılır.
- Durum renkleri (hata/başarı) vurgu üçlüsünden ayrıdır.
- Koyu tema varsa ikinci bir palet değil, aynı tokenların koyu karşılığıdır.

## Tipografi

- En fazla iki aile, en fazla üç ağırlık. Display karakterli; gövde nötr.
- Display: `clamp()` ile akışkan, 1440 px'de 56–150 px arası; satır aralığı
  0.82–0.95; harf aralığı −0.02…−0.04em.
- Gövde: 16–18 px, satır aralığı 1.55–1.65, ölçü 60–75 karakter.
- Etiket: 11–13 px, geniş harf aralığı, yalnız gerçekten sıra/numaralandırma
  varsa kullan.
- Türkçe kapsam zorunlu: `ğ ş İ ı ö ç ü` eksiksiz; latin-ext alt kümesi.
- Font dosyaları yerel `woff2`, `font-display: swap`, en fazla 2–3 dosya.
- Google/Fontshare varsayılanına sığınma; seçim işletmenin karakterinden gelir.

## Grid ve boşluk

- 12 kolon veya 60/40 asimetri; 8 px tabanlı boşluk ölçeği.
- İçerik genişliği `min(1180px, 92vw)`; geniş ekranda 75–85 karakter.
- Bir ekranda tek baskın öğe; diğerleri iki kademe küçük.
- Bölüm ritmi: büyük nefes → yoğun kanıt → büyük nefes. Her bölüm aynı
  yükseklikte olmak zorunda değil.
- Hizalama tek eksende; kartların yarıçapı ve gölgesi hiyerarşiye göre değişir.

## Fotoğraf ve kadraj

- Gerçek mekân, gerçek insan, gerçek iş; yüzsüz stok görsel kullanma.
- Hero: tek güçlü kare; `object-position` ile yüz/ürün kadrajı korunur.
- Metin fotoğrafın üstündeyse scrim (siyah %35–55 veya renkli gradyan)
  zorunlu; metni fotoğrafa emanet etme.
- Galeri: aynı ışık ve renk derecelendirmesi; üç farklı ölçek (geniş, orta,
  detay) karıştırılır.
- Her görselde anlamlı `alt`; dekoratif görselde boş `alt`.

## AI/şablon klişeleri (kullanma)

- Krem zemin + yüksek kontrast serif + terracotta vurgu.
- Siyaha yakın zemin + asit yeşili/vermilion vurgu.
- Her içeriği aynı yuvarlak karta bölmek, her karta aynı gölge.
- Her başlığın üstüne büyük harfli, geniş aralıklı etiket.
- “A · B · C” meta satırları, “KELİME — parça” kalıbı, her butona “→”.
- Her bölümde fade-and-slide-up; her kartta hover zıplaması.
- Sadece süs olsun diye 01/02/03 numaraları.

## Sektör karakteri

| Sektör | Görsel dil |
|---|---|
| Kafe | sıcak malzeme, yakın plan doku, sabah ışığı |
| Kuaför/berber | ayna, makas, hareket; moda editoryali |
| Diş/klinik | temiz beyaz, sakin mavi-yeşil, net bilgi |
| Emlak | geniş kadraj, doğal ışık, sakin lüks |
| Hukuk | kâğıt, mürekkep, ciddi serif, az süs |
| Spor | yüksek kontrast, dar sans, hareket bulanıklığı |
| Oto servis | metal, atölye, teknik yakın plan |
| Çekici | gece yolu, uyarı sarısı, güven |
| Nakliyat | koli, düzen, rota çizgisi |
| Temizlik/tesisat | önce/sonra, netlik, mavi |

## Teslim kanıtı

`tasarim.json`: konsept cümlesi, zemin/mürekkep/vurgu, font aileleri ve
ağırlıkları, tip ölçeği, grid, yarıçap/gölge, fotoğraf kadraj notu, hareket
karakteri.

## Ajan kullanımı

Kerem bu dosyayı `tasarim.json` için kullanır. Selin yalnız bu tokenlarla
arayüz kurar; yeni renk/font uydurmaz. Deniz kontrast ve font sayısını denetler.


---

## 4. Arayüz ve tasarım sistemi — Selin · Arayüz

_Token, bileşen, durumlar, responsive ve erişilebilir iskelet._

# 04 · Arayüz ve tasarım sistemi

## Ne zaman

Konsept ve metin onaylandıktan sonra. Önce iskelet, sonra görsel katman.

## Token sistemi

Tek yerde tanımlanır, her bileşen oradan beslenir:

- Renk: `--bg`, `--surface`, `--ink`, `--muted`, `--accent`, `--line`,
  `--ok`, `--warn`, `--err`.
- Tip: `--display`, `--body`, `--step--1 … --step-5`, `--leading-tight/body`.
- Boşluk: 4/8/12/16/24/32/48/64/96/128.
- Yarıçap: 0/6/12/999; gölge: 0 veya tek bir yumuşak seviye.
- Hareket: `--dur-1:150ms`, `--dur-2:250ms`, `--dur-3:600ms`,
  `--ease: cubic-bezier(.16,1,.3,1)`.

Kural: aynı işi yapan iki token olmaz; ham hex ve px değerleri bileşen
içinde tekrarlanmaz.

## Bileşen envanteri

1. Üst navigasyon: logo, 4–6 bağlantı, birincil CTA, mobil menü.
2. Hero: başlık, alt cümle, 1–2 CTA, tek görsel/video, kanıt şeridi.
3. Hizmet/ürün kartı: başlık, tek cümle, süre/kapsam, bağlantı.
4. Süreç: 3–4 adım, numara yalnız gerçek sıra ise.
5. Kanıt: yorum, sayı, logo, gerçek fotoğraf.
6. SSS: `details/summary`, tek açık, klavye uyumlu.
7. İletişim: form, telefon, WhatsApp, adres, harita bağlantısı.
8. Footer: adres, saatler, sosyal, küçük yasal satır.
9. Mobil sabit eylem çubuğu: ara + WhatsApp, 44 px hedef.
10. Durum bileşenleri: boş, yükleniyor, hata, başarı.

## Durumlar

Her etkileşimli öğe için: varsayılan, hover (yalnız fare), focus-visible,
active, disabled, loading. Odak halkası 2 px ve 3:1 kontrastlı; asla
`outline: none` tek başına. Buton metni yüklenirken değişmez, yanında
göstergesi döner.

## Responsive

- Kırılımlar: 320, 375, 480, 768, 1024, 1440, 1920.
- Mobil önce; 320 px'de yatay kaydırma yok, başlık kırpılmıyor.
- Dokunma hedefi en az 44×44 px; iki hedef arası en az 8 px.
- `100svh/100dvh` kullan; adres çubuğu zıplamasın.
- `env(safe-area-inset-*)` ile çentik/alt bar güvenliği.
- Uzun Türkçe işletme adları için `overflow-wrap: anywhere`,
  `text-wrap: balance`, `hyphens: auto`.
- Karta göre tipografi gerekiyorsa `container-type: inline-size` kullan.
- Sabit nav içeriği kapatmaz; `scroll-margin-top` başlığı kesmez.

## Yerleşim kuralları

- Hero içeriğe göre yükselir; her ekranda 100vh doldurmak zorunda değil.
- Bir ekranda tek baskın öğe; CTA'lar aynı hizada ve aynı dilde.
- Kart ızgarası 1/2/3 kolon; 4'ten fazla eşit kart yerine editoryal ritim.
- Uzun sayfada her 2–3 bölümde bir nefes; arka plan tonu bölümü ayırır.
- Footer'da dev marka adı varsa taşma testi yapılır; mobilde kırılır.

## Form

- Her alanın görünür etiketi; `autocomplete`, `inputmode`, doğru `type`.
- Hata alanın yanında, renk + metin + ikon birlikte.
- Zorunlu alan sayısı en az; telefon ve ad yeterliyse başka alan istemeyiz.
- Honeypot + zaman kontrolü; kullanıcıya görünmez captcha yok.
- Gönderim sonrası ne olacağı yazılı: “WhatsApp açılacak”, “24 saat içinde
  döneceğiz”.

## Tasarım QA

- 3 saniye testi: kim, ne, nerede, nereye tıklanacak?
- Göz kısma testi: bulanık bakışta hiyerarşi kalıyor mu?
- Grid overlay: tüm kenarlar aynı kolonda mı?
- 320 px ve 1440 px'de ekran görüntüsü; kırpılan kenar var mı?
- Klavye turu: Tab ile tüm akış, Esc ile kapanma, odak kaybolmuyor.
- Uzun metin ve uzun işletme adıyla test.

## Teslim kanıtı

Token listesi, bileşen envanteri, üç kırılımda ekran görüntüsü, klavye turu
notu. Deniz, “tek H1”, “dokunma hedefi”, “taşma yok” maddelerini denetler.


---

## 5. Frontend, performans ve erişilebilirlik — Mert · Frontend

_Semantik HTML, yerel varlıklar, CWV bütçesi ve WCAG 2.2 AA._

# 05 · Frontend, performans ve erişilebilirlik

## Ne zaman

Arayüz iskeleti hazır olduğunda. Site tek dosya veya az sayıda yerel dosya
olarak kurulur; harici CDN, font, API ve iframe yoktur.

## HTML

- `<!doctype html>`, `lang="tr"`, `meta charset`, `viewport`.
- Tek `h1`; `header/nav/main/section/footer` landmark'ları.
- Bölümler `aria-labelledby` ile başlıklarına bağlanır.
- Bağlantı gerçekten bağlantıysa `<a>`, eylemse `<button>`.
- Form alanları `label for` ile; hata `aria-describedby` + `role="alert"`.
- Mobil menü `aria-expanded`, dialog `aria-modal`, Esc ile kapanır.
- İçerik JS olmadan da görünür; gizli başlangıç durumu JS ile kurulur.

## CSS

- Tokenlar `:root`, bileşenler tek katman; `!important` yok.
- `@layer` veya net sıralama; seçici özgüllüğü çakışmıyor.
- Kritik CSS `<style>` içinde; geri kalanı tek yerel dosya.
- `text-wrap: pretty/balance`, `clamp()`, `:has()`, `color-mix()` kademeli.
- Karanlık mod `prefers-color-scheme`; `forced-colors` ve `prefers-contrast`
  için kenarlık/odak korunur.
- Yazdırma stili: menü, adres, telefon tek sayfada.

## Font

- Yerel `woff2`, latin-ext, 2–3 dosya, toplam < 180 KB.
- `font-display: swap`, hero fontu `preload`, diğerleri değil.
- Değişken font tek dosyada ağırlıkları taşır; 4 ağırlık yüklemek yerine 2.

## Görsel ve video

- `width`/`height` veya `aspect-ratio`; CLS 0 hedefi.
- AVIF + WebP, `srcset`/`sizes`, mobilde küçük varyant.
- Hero `fetchpriority="high"` ve preload; alt bölümler `loading="lazy"`.
- Video: `poster`, `preload="none"`, `muted`, `playsinline`, `loop`.
  Otomatik oynatma yalnız sessizse; mobilde ve reduced-motion'da durur.
- Hiçbir görselin kaynağı dış alan adı değil.

## JavaScript

- Toplam < 40 KB (sıkıştırılmış); framework yok, vanilla yeterli.
- `defer`, IIFE/modül, global yok; hata olsa bile içerik görünür.
- Özellik algılama: `IntersectionObserver`, `matchMedia`, WebGL yoksa fallback.
- `requestAnimationFrame`; görünmeyen sekmede döngü durur.
- `console.log`, debug paneli, localhost URL'si yayında kalmaz.

## Core Web Vitals bütçesi (mobil p75)

| Ölçü | Hedef |
|---|---|
| LCP | ≤ 2.5 s (DOM metni veya poster) |
| INP | ≤ 200 ms |
| CLS | ≤ 0.1 |
| Toplam sayfa | ≤ 1.5 MB (video hariç) |
| İlk yükte JS | ≤ 40 KB |
| Font | ≤ 180 KB |

## Erişilebilirlik (WCAG 2.2 AA)

- Kontrast 4.5:1; büyük metinde 3:1; fotoğraf üstünde scrim.
- Klavye: görünür odak, mantıklı sıra, skip link, tuzak yok.
- Dokunma hedefi 24 px minimum, birincil hedefler 44 px.
- `alt`: bilgi veren görselde anlamlı, dekoratif görselde boş.
- İkon-only düğmede `aria-label`; SVG `aria-hidden` + yanında metin.
- Hareket: `prefers-reduced-motion`; 5 s'den uzun döngüde durdurma.
- Zoom %200 ve 320 px genişlikte içerik kaybolmuyor.
- Dil `lang`, sayfa başlığı benzersiz, bağlantı metni “buraya tıklayın” değil.

## Güvenlik ve gizlilik

- Dış istek yok: CSP `default-src 'self'` ile uyumlu.
- Formda honeypot + süre kontrolü; gizli captcha yok.
- KVKK: hangi veri, neden, süre, silme yolu; çerez yoksa banner yok.
- Üçüncü taraf gömme (harita, video, font) yok; statik harita görseli +
  yol tarifi bağlantısı kullanılır.

## Safari/iOS kontrolü

- `100vh` yerine `svh/dvh`; sticky ve `backdrop-filter` testi.
- Video autoplay sessiz + `playsinline`; düşük güç modunda poster.
- `-webkit-` gereken yerler yalnız gerektiğinde; `-webkit-text-size-adjust`.
- Dokunmada hover takılı kalmasın: `@media (hover:hover)`.

## Teslim kanıtı

Lighthouse mobil raporu (performans ≥ 90, erişilebilirlik 100), CWV ölçümü,
no-JS ve reduced-motion ekran görüntüsü, klavye turu notu.


---

## 6. Sinematik hareket ve medya — Ece · Hareket

_Tek zirveli zaman çizgisi, 60fps, reduced-motion ve video bütçesi._

# 06 · Sinematik hareket ve medya

## Ne zaman

Statik sayfa doğru çalıştıktan sonra. Hareket, bozuk bir düzeni kurtarmak
için kullanılmaz.

## İlke

Her animasyonun bir görevi vardır: dikkat yönlendirmek, geçişi açıklamak,
hiyerarşiyi göstermek veya eyleme geri bildirim vermek. “Havalı” olan hareket
silinir. Sayfada **tek zirve** olur; her bölüm aynı şiddette hareket etmez.

## Zaman çizgisi

| An | Süre | Eğri |
|---|---|---|
| Hover/focus geri bildirimi | 150–250 ms | ease-out |
| Kart/menü açılışı | 400–600 ms | `cubic-bezier(.16,1,.3,1)` |
| Bölüm reveal | 600–900 ms | aynı aile |
| Hero girişi | 900–1400 ms, toplam | aynı aile |
| Split-text kelime gecikmesi | 16–38 ms, toplam ≤ 600 ms | — |

Tek eğri ailesi ve tek süre merdiveni kullanılır. Mesafe arttıkça süre artar;
sıralı gecikme okuma yönünü izler.

## Uygulama

- Yalnız `transform` ve `opacity`; layout/paint tetikleyen özellik animasyonu yok.
- `will-change` yalnız animasyon süresince; kalıcı bırakma.
- `IntersectionObserver` ile görünürken çalıştır, görünmezken durdur.
- Scroll hijack yok; native scroll + `position: sticky` + IO.
- `animation-timeline: view()` destekleniyorsa CSS ile; değilse JS.
- İçerik varsayılan olarak görünür; gizli başlangıç JS'in ilk karesinde kurulur.
- JS kapalıyken hiçbir metin, görsel veya bağlantı kaybolmaz.

## Split-text ve tipografi hareketi

- `h1` kelimelere bölünürse `aria-label` tam metni taşır, kelimeler
  `aria-hidden` olur.
- Satır maskesi taşma yapmaz; Türkçe uzun kelimeler kırpılmaz.
- Harf harf animasyon yalnız kısa başlıkta; paragrafta kullanılmaz.
- Reduced-motion'da bölünmüş metin statik ve tam görünür.

## Scroll sahneleri

- Sticky sahne 120–200svh arası; tek fikir anlatır, mobilde statikleşir.
- Parallax katmanı en fazla iki; hız farkı %10–20.
- Yatay kaydırma yalnız gerçekten yatay bir hikâye varsa; aksi halde dikey.
- İlerleme çubuğu varsa gerçek okuma oranını gösterir, süs değildir.

## İmleç ve hover

- Native imleç korunur; takip eden öğe yalnız `(hover:hover) and (pointer:fine)`
  cihazlarda ve reduced-motion kapalıyken.
- Hover kutuyu büyütmez/zıplatlatmaz; ton, çizgi veya ikon değişir.
- Dokunmada hover durumu takılı kalmaz.

## Video ve medya

- Sitede en fazla 3 tam ekran klip: açılış, iş, kapanış.
- 720p, sessiz, 6–8 s, döngülü, poster aynı kare; toplam < 8 MB.
- `preload="none"`, `poster`, `playsinline`, `muted`, `loop`.
- Mobilde ve `prefers-reduced-motion` açıkken video durur, poster kalır.
- Otomatik ses yok; ses varsa kullanıcı başlatır ve durdurabilir.
- WebGL/3B varsa: DPR sınırı, görünürken kare, LCP sonrası başlat, offscreen
  durdur, WebGL yoksa CSS/görsel fallback. Canvas `aria-hidden`; tüm metin DOM'da.
- 5 s'den uzun sürekli hareketin durdurma kontrolü vardır.

## Performans

- 60fps hedefi; uzun görev > 50 ms ise böl veya azalt.
- 4x CPU yavaşlatmada hero girişi 1.4 s'yi aşmıyorsa kabul.
- Animasyon sırasında CLS oluşmaz; layout önceden ayrılır.

## Test

- Yavaş CPU + yavaş ağ; ilk boyada metin var mı?
- Sayfa ortasından yukarı/aşağı hızlı kaydırma; sahne sıçrıyor mu?
- Sekme değiştir ve geri dön; zaman çizgisi kaldığı yerden mi?
- Reduced-motion aç/kapa; sayfa yeniden düzenleniyor mu?
- JS kapalı; içerik ve CTA görünür mü?

## Teslim kanıtı

Hareket süreleri/eğrisi, sahne listesi, klip sayısı ve boyutu, reduced-motion
ve no-JS ekran görüntüsü, 4x CPU notu.


---

## 7. Yerel SEO ve ölçüm — Duru + Deniz

_Yerel arama, şema, meta, sitemap ve dönüşüm olayları._

# 07 · Yerel SEO ve ölçüm

## Ne zaman

Metin ve bilgi mimarisi kesinleştikten sonra; sayfa yayına hazırlanırken.

## Yerel arama temeli

- H1 ve title hizmet + bölge içerir: “Karşıyaka'da diş implantı”.
- Sayfada tek bir net işletme adı, adres ve telefon (NAP) tutarlı yazılır.
- Bölge adı doğal geçer: semt, ilçe, sokak, yakın landmark. Doldurma yapılmaz.
- Harita için dış iframe yok: statik harita görseli + “Yol tarifi al” bağlantısı.
- Çalışma saatleri tablo halinde; JS saatiyle “şu an açık” etiketi (tatil hariç).
- Google İşletme Profili alanları siteyle aynı: ad, kategori, telefon, adres,
  saatler, hizmetler, fotoğraflar. Çelişki yerel sıralamayı düşürür.

## Meta ve yapı

- Title 50–60, description 140–160 karakter; ikisi farklı.
- Canonical tek adres; parametre ve `www`/`https` tekilleştirilir.
- `og:title`, `og:description`, `og:image` (1200×630 yerel), `og:locale=tr_TR`,
  `twitter:card`.
- Tek H1; H2/H3 hiyerarşisi atlamaz.
- Sayfa içi bağlantılar anlamlı metinle; “buraya tıklayın” yok.
- 404 sayfası markalı ve tek ana eylemli; eski adresler 301.
- `sitemap.xml`, `robots.txt`, `favicon.svg`, `manifest.webmanifest`.
- Çok sayfada her sayfa kendi title/description/canonical'ına sahip.

## Şema (JSON-LD)

- `LocalBusiness` (veya alt tür: `Dentist`, `Restaurant`, `AutoRepair`,
  `RealEstateAgent`, `LegalService`) — ad, adres, telefon, saatler, geo, url.
- `FAQPage` yalnız görünen SSS ile birebir aynı sorular için.
- `Product` ürün sitelerinde: ad, görsel, marka, teklif, para birimi.
- `Service` hizmet sayfalarında: hizmet adı, bölge, sağlayıcı.
- `BreadcrumbList` çok sayfada.
- Uydurma `aggregateRating`, `review`, `award` yazılmaz.

## İçerik

- Bir ana sayfa + gerçek hizmet sayfaları; her hizmete ayrı sayfa açmak
  yalnız içerik gerçekten farklıysa.
- SSS gerçek arama dilinde; cevap 40–80 kelime.
- Blog açılacaksa 3–5 yazılık küme: “fiyat”, “süreç”, “bakım”, “bölge”.
- Her yazıda tek H1, yazar/tarih, iç bağlantı, tek CTA.
- Anahtar kelime doldurma, gizli metin, kapı sayfası yok.

## Ölçüm

Olaylar (event): `tel_click`, `whatsapp_click`, `form_submit`, `directions_click`,
`menu_view`, `price_question`. Her olayda bölüm adı param olarak taşınır.
- Analitik yalnızca sahibinin onayıyla ve çerezsiz/anonim araçla eklenir.
- Çerez yoksa banner yok; varsa “reddet” seçeneği “kabul” ile eşit.
- Form gönderimi sayfa yenilemeden çalışır; başarı/hata durumu görünür.
- Aylık rapor: oturum, kaynak, cihaz, dönüşüm, en çok terk edilen bölüm.

## Yayın öncesi kontrol

- [ ] Title/description her sayfada dolu ve benzersiz.
- [ ] Tek H1, doğru H2/H3.
- [ ] JSON-LD doğrulayıcıda hatasız; görünen içerikle aynı.
- [ ] Canonical, sitemap, robots doğru; test ortamı indekslenmiyor.
- [ ] OG görseli 1200×630 ve yerel.
- [ ] Kırık bağlantı yok; tüm CTA'lar gerçek hedefe gidiyor.
- [ ] NAP site, harita ve GBP ile aynı.
- [ ] Sayfa hızı mobilde yeşil; LCP ≤ 2.5 s.

## Teslim kanıtı

`seo.md`: başlık/meta tablosu, şema listesi, sitemap/robots durumu, GBP kontrol
listesi, olay adları, aylık rapor kalemleri. Deniz, şema ile görünen SSS
eşleşmesini ve tek H1'i denetler.


---

## 8. Kalite, teslim ve müşteri — Deniz · Kalite

_10 kriterli rubrik, QA matrisi, lansman listesi ve müşteri sunumu._

# 08 · Kalite, teslim ve müşteri

## Ne zaman

Site çalıştıktan sonra, müşteriye gitmeden önce. Kalite kapısı geçilmeden
yayın URL'si paylaşılmaz.

## 10 kriterli rubrik (0–5)

Her kriter kanıtla puanlanır. Ortalama ≥ 4.0 ve hiçbir kriter < 3 olmalı.

1. Konsept özgünlüğü ve işletmeye aidiyet.
2. 3 saniyelik anlaşılırlık ve görsel hiyerarşi.
3. Tipografi ve okunabilirlik (Türkçe karakter dahil).
4. Grid, boşluk, hizalama.
5. Fotoğraf seçimi ve kadraj.
6. Hareketin işlevi ve performansı.
7. Metin netliği ve gerçek kanıt.
8. Mobil kullanılabilirlik.
9. Erişilebilirlik.
10. Dönüşüm yolu.

Puanlama kanıtı: 390/768/1440 px ekran görüntüsü, klavye turu, reduced-motion,
no-JS, yavaş ağ, gerçek telefonda CTA.

## QA matrisi

| Alan | Kontrol |
|---|---|
| Genişlik | 320, 375, 390, 768, 1024, 1440, 1920 |
| Tarayıcı | Chrome, Safari (iOS), Firefox, Edge |
| Klavye | Tab sırası, focus görünür, Esc, skip link |
| Ekran okuyucu | Başlık hiyerarşisi, landmark, form etiketi |
| Hareket | reduced-motion, 5 s üstü durdurma |
| JS kapalı | Tüm metin, görsel, CTA görünür |
| Ağ | Yavaş 3G + 4x CPU; LCP ≤ 2.5 s |
| Form | Boş, hatalı, başarılı; çift gönderim |
| Bağlantılar | Tüm CTA, tel, WhatsApp, harita |
| İçerik | Yazım, Türkçe karakter, tutarlı NAP |

Her bulgu: ne, nerede, önem (bloklayıcı/önemli/küçük), düzeltme.

## Lighthouse ve CWV

- Mobil performans ≥ 90, erişilebilirlik 100, en iyi uygulamalar ≥ 95, SEO 100.
- LCP ≤ 2.5 s, INP ≤ 200 ms, CLS ≤ 0.1.
- Bu eşikler tutmuyorsa “yayında” denmez; ölçüm ve düzeltme notu eklenir.

## Lansman listesi

- [ ] Alan adı ve SSL doğru; `www` yönlendirmesi.
- [ ] Tüm sayfalar 200; 404 ve 301 çalışıyor.
- [ ] Title/description/canonical/OG dolu.
- [ ] Sitemap ve robots yayında; test ortamı kapalı.
- [ ] Form gerçek alıcıya ulaşıyor; otomatik yanıt metni doğru.
- [ ] Telefon/WhatsApp bağlantıları gerçek numaraya gidiyor.
- [ ] Font, görsel, video yerel; dış istek yok.
- [ ] Analitik/olaylar doğru çalışıyor (onay varsa).
- [ ] Yedek alındı; geri dönüş adımı yazılı.
- [ ] KVKK/gizlilik metni ve çerez durumu tutarlı.
- [ ] Erişilebilirlik ve reduced-motion son turu yapıldı.
- [ ] Müşteriye giden URL ve giriş bilgisi hazır.

## Teslim paketi

1. Yayındaki site ve URL.
2. Kaynak dosyalar (HTML/CSS/JS, görsel, font).
3. Lisans dosyası: font, stok görsel/video, kütüphane.
4. Ölçüm raporu: Lighthouse, CWV, dönüşüm olayları.
5. Kısa kullanım rehberi: metin/fotoğraf değiştirme, form, yedek.
6. Bakım kapsamı: neler dahil, yanıt süresi, ücret.
7. Açık riskler ve müşteriden beklenenler.

## Müşteri sunumu

Akış: **sorun → sonuç → kanıt → kapsam → fiyat → sonraki adım**.
- İlk 30 saniyede siteyi aç, hero'yu göster, tek ana eylemi söyle.
- Üç somut iyileştirme göster: hız, netlik, dönüşüm.
- Fiyatı tek cümlede söyle; paketleri yan yana koy, gizli kalem bırakma.
- İtiraz: “pahalı” → ajans karşılaştırması ve kapsam; “bakarız” → 14 gün
  geçerlilik ve 48 saatlik önizleme; “kendim yaparım” → tema ile fark.
- Sunum sonunda tek bir sonraki adım: “Onaylarsanız alan adını bağlayıp
  yayına alıyorum.”

## Bakım ve geri dönüş

- Aylık: yedek, form testi, kırık bağlantı, hız kontrolü, yazılım güncellemesi.
- Yıllık: içerik tazeleme, fotoğraf yenileme, SEO kontrolü.
- Her değişiklik öncesi yedek; geri dönüş adımı ve sorumlusu yazılı.
- SLA: kritik arıza 4 saat, içerik değişikliği 2 iş günü (sözleşmeye göre).

## Teslim kanıtı

`qa.md`: 28 otomatik kontrol + rubrik puanları + bulgu listesi + lansman
kontrolü. `satis.md` ve `teklif.html` aynı kapsamı ve fiyatı söyler.


---

## 9. Sanat yönleri ve çeşitlilik — Kerem + Selin

_Beş yön, sektöre uygun seçim, farklı hero ve bölüm sırası._

# 09 · Sanat yönleri ve çeşitlilik

## Sorun

Tek şablon + renk değişimi = aynı site. Müşteri “bu benim işim” demiyorsa
tasarım başarısızdır. Her işletme, sektörüne uygun **beş yönden biriyle**
kurulur ve yön yalnız rengi değil; hero kompozisyonunu, bölüm sırasını, kart
düzenini, menüyü ve footer'ı değiştirir.

## Beş yön

| Yön | İlk ekran | Tipografi | Kartlar | Bölüm sırası |
|---|---|---|---|---|
| **Editoryal** | Asimetrik split, 3:4 görsel | Instrument Serif, 400 | 2 kolon, ince çizgi, numara | Hizmet → Vitrin → Yorum → SSS |
| **Nesne** | Tam ekran görsel, alt hizalı metin | Clash Display, 600 | 2 kolon, çizgi ızgara | Vitrin → Hizmet → Yorum → SSS |
| **Kinetik** | Görsel üstte, dev büyük harf başlık | Clash Display, sıkı | 2 kolon, vurgu şeridi | Hizmet → Yorum → Vitrin → SSS |
| **Arşiv** | Küçük kare görsel, liste hissi | Bricolage, 500 | Satır satır, küçük thumbnail | Vitrin → Hizmet → SSS → Yorum |
| **Sakin** | Bol boşluk, geniş tek kolon | Fraunces, 400 | 2 kolon, gölgesiz, yuvarlaksız | Hizmet → Yorum → SSS → Vitrin |

Seçim sektör havuzundan ve işletme adı + şehirden yapılır; aynı işletme her
üretimde aynı yönü alır, farklı işletme başka yön alır.

Her yönün **iki hero varyantı** vardır (`imza-1`, `imza-2`): aynı yöndeki iki
işletme bile görsel olarak ayrışır. Örnek: Editoryal'de metin solda/görsel
sağda ya da tersi; Sakin'de tek kolon ya da iki kolon; Nesne'de sol alt ya da
sağ üst hizalı; Arşiv'de görsel sağda ya da üstte; Kinetik'te görsel altta ya
da üstte. Varyant da işletme adı + şehir + sektörden kararlı seçilir.

Palet de yönle birlikte otomatik türetilir: ana vurgu + tamamlayıcı +
90° komşu. Böylece aynı yön ve aynı sektördeki iki işletme aynı renk üçlüsünü
almaz.

## Sektör havuzları

- Kafe: Kinetik, Editoryal, Sakin.
- Kuaför: Editoryal, Sakin, Kinetik. Berber: Kinetik, Nesne, Editoryal.
- Diş: Sakin, Editoryal, Arşiv. Emlak: Nesne, Sakin, Editoryal.
- Spor: Kinetik, Nesne, Editoryal. Avukat: Editoryal, Arşiv, Sakin.
- Anaokulu/veteriner: Sakin, Editoryal. Oto servis: Nesne, Arşiv, Kinetik.
- Çekici: Nesne, Kinetik, Editoryal. Temizlik: Sakin, Arşiv, Editoryal.
- Tesisat: Arşiv, Sakin, Nesne. Nakliyat: Arşiv, Nesne, Editoryal.

## Yön kuralları

### Editoryal
- Hero 1.3fr / 0.7fr; görsel 3:4; canvas ve glow kapalı.
- Başlık 400 serif, 12ch; ölçü çizgileri 1px; rozet çizgi + küçük etiket.
- Hizmetler 2 kolon, her kart alt çizgiyle ayrılır; ikon yok, numara var.
- Yorumlar tek kolon, alıntı gibi; form kutusu yuvarlaksız.

### Nesne
- Görsel tam ekran, alt %78 gradyan scrim; metin alt sol.
- Başlık 7vw'ye kadar, beyaz; ikincil metin %84 beyaz.
- Nav görsel üstünde; kaydırınca opak zemine döner.
- Kartlar 18rem, çizgi ızgara; fotoğraf varsa kartın içinde.

### Kinetik
- Görsel 21:9 üstte; başlık büyük harf, 0.8 satır aralığı.
- Marquee vurgu renginde, geniş; 18 s'de bir tur.
- Kartlar kareye yakın, sağ/alt çizgi; fotoğraf %32 opak, gri.
- Sekme, panel ve form yuvarlaksız.

### Arşiv
- Hero 1.35fr / 0.65fr; görsel 1:1, ince çerçeve.
- Hizmetler satır: başlık + açıklama + 7×5rem thumbnail.
- Panel tek kolon, 21:9 fotoğraf; SSS yorumdan önce.
- Teknik, sakin krom; yuvarlak köşe yok.

### Sakin
- Hero tek kolon, 64rem; görsel 16:9, çerçevesiz.
- Başlık 400 Fraunces, 17ch; bölüm boşluğu 10rem'e kadar.
- Kartlar 2 kolon, yalnız alt çizgi; fotoğraf ve ikon yok.
- Gölge, yuvarlak köşe ve hover zıplaması yok.

## Çeşitlilik kontrolü

- Aynı sektörde iki işletme üret: yönleri ve bölüm sıraları farklı olmalı.
- İki sitede aynı hero kompozisyonu + aynı kart düzeni varsa biri reddedilir.
- Aynı yön + aynı `imza` + aynı palet üçlüsü birlikte geliyorsa biri reddedilir.
- Renk değişimi tek başına çeşitlilik sayılmaz; hero, sıra ve kart dili de değişmeli.
- Yön, işletmenin işine uygun olmalı: hukukta kinetik poster, gece kulübünde
  sakin malzeme dili kullanılmaz.

## Teslim kanıtı

`tasarim.json` içinde `sanat_yonu`, `yon_aciklama`, `yon_bolum_sirasi` yazar.
`qa.md` iki farklı işletmenin farklı yön aldığını not eder.


---

## 10. Satış ve dönüşüm psikolojisi — Ela + Duru

_Teklif, kanıt, risk azaltma, fiyat ve CTA akışı._

# 10 · Satış ve dönüşüm psikolojisi

## Temel ilke

Site “güzel” olduğu için değil, ziyaretçi **ne olduğunu 3 saniyede anlayıp
tek eyleme güvenle geçtiği** için satar. Satış baskısı değil, netlik satar.
Uydurma indirim, sahte kontenjan, olmayan yorum kullanılmaz.

## Teklif mimarisi

1. **Vaat:** kim, nerede, hangi sonuç. “Karşıyaka'da diş implantı; aynı gün
   muayene, yazılı tedavi planı.”
2. **Kanıt:** yıl, vaka sayısı, gerçek yorum, sertifika, gerçek fotoğraf.
   Kanıt yoksa iddia küçültülür; uydurulmaz.
3. **Mekanizma:** neden bu işletme? Süreç, ekipman, garanti, yaklaşım.
4. **Risk azaltma:** ücretsiz keşif, yazılı fiyat, memnuniyet koşulu,
   iptal hakkı, “onay olmadan başlanmaz”.
5. **Eylem:** tek CTA; formda en az alan; WhatsApp hazır mesajı.

## Hero'da satış

- Başlık vaat, alt cümle kanıt + bölge, CTA eylem.
- Fiyat gizliyse “fiyat sor” değil, “yazılı teklif al” denir.
- Telefon numarası ilk ekranda görünür; mobilde sabit çubukta.
- Aciliyet gerçekse yazılır (“bugün 2 slot”); değilse yazılmaz.

## Bölüm sırası (dönüşüm)

1. Hero (vaat + CTA)
2. Hizmetler (ne, kime, süre)
3. Nasıl çalışır (3–4 adım, müşteriye düşen iş)
4. Kanıt (yorum, vaka, fotoğraf, sayı)
5. İtiraz/SSS (fiyat, süre, garanti, bölge)
6. Son CTA (aynı eylem, tek cümle)

Kanıt, iddianın hemen yanında olur; ayrı sayfaya saklanmaz.

## Fiyat sunumu

- Sitede fiyat yoksa teklif dosyasında net aralık, kapsam ve geçerlilik olur.
- Üç paket varsa ortadaki önerilir; fark tek bakışta görünür.
- “Pahalı” itirazı: ajans karşılaştırması, kapsam, teslim ve destek.
- Gizli kalem, zorunlu abonelik, sürpriz ek ücret yok.
- Ödeme: %50 başlangıç / %50 teslim gibi net bir kural.

## Dönüşüm bandı (sayfanın alt üçte biri)

- SSS'den sonra, iletişimden önce tam genişlikte tek renkli bir bant kur.
- Bant tek vaat taşır: “Bir mesaj. Net fiyat.” gibi; başlık + tek cümle +
  iki eylem (WhatsApp, telefon) + üç adımlı süreç.
- Bant rengi paletin ikinci rengidir; üstündeki metin ve buton kontrastı
  ayrıca hesaplanır. Gökkuşağı gradyanı kullanılmaz.
- Üç adım müşterinin işini söyler: “Yazın → Kapsamı görün → Başlayın”.
  Uydurma süre, indirim veya kontenjan eklenmez.

## Mobil sabit çubuk

- 900 px altında ekranın altında iki eylem: **Ara** ve **WhatsApp**.
- Çubuk 48 px yüksekliğinde, güvenli alan (safe-area) boşluklu; sayfa
  sonuna 4–5rem padding eklenir, içerik çubuğun altında kalmaz.
- WhatsApp marka yeşili kullanılabilir; ana CTA paletin ana rengidir.
- Masaüstünde gizlenir; klavye odağı ve `aria-label` korunur.

## Form ve lead

- Alan sayısı 3'ü geçmez: ad, telefon, hizmet.
- Gönderim sonrası ne olacağı yazılı: “WhatsApp açılacak”, “24 saat içinde
  dönüş”.
- Hata mesajı ne olduğunu ve nasıl düzeltileceğini söyler.
- Form sunucuya gitmiyorsa bu açıkça yazılır; sahte “talebiniz alındı” yok.
- Honeypot + süre kontrolü; kullanıcıya görünmez captcha yok.

## Güven sinyalleri

- Gerçek Google puanı ve yorum sayısı (varsa).
- Adres, harita, çalışma saatleri, gerçek ekip fotoğrafı.
- KVKK/gizlilik notu, çerez yoksa banner yok.
- SSL, hızlı açılış, kırık bağlantı yok.
- “Önce/sonra”, vaka veya süreç fotoğrafı; stok “mutlu müşteri” yok.

## Etik sınır

- Sahte aciliyet, sahte stok, sahte indirim, sahte yorum yasak.
- “Türkiye'nin en iyisi” gibi kanıtsız üstünlük iddiası yasak.
- Müşteri yorumu izinsiz kullanılmaz; örnek yorum “örnek” etiketi taşır.
- Sağlık/hukuk gibi sektörlerde garanti vaadi verilmez.

## Ölçüm

- Olaylar: `tel_click`, `whatsapp_click`, `form_submit`, `directions_click`.
- Hangi bölümde terk edildiği; hangi CTA çalışıyor.
- Aylık rapor: oturum, kaynak, cihaz, dönüşüm, en çok görüntülenen hizmet.
- A/B testi yalnız yeterli trafik varsa; küçük sitede sıralı iyileştirme.

## Teslim kanıtı

`satis.md` ve `teklif.html`: vaat, kapsam, kanıt, risk azaltma, fiyat, süre,
revizyon, sonraki adım. Site üzerindeki CTA metniyle birebir aynı dili kullanır.


---

## Yayın rubriği

1. Konsept özgünlüğü ve işletmeye aidiyet
2. 3 saniyelik anlaşılırlık ve görsel hiyerarşi
3. Tipografi ve okunabilirlik
4. Grid, boşluk ve hizalama
5. Fotoğraf seçimi ve kadraj
6. Hareketin işlevi ve performansı
7. Metin netliği ve gerçek kanıt
8. Mobil kullanılabilirlik
9. Erişilebilirlik
10. Dönüşüm yolu
