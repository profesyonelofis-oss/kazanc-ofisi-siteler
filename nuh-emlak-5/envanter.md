# Üretim envanteri — Nuh Emlak

Paket: **100.000 ₺ tek sayfa flagship** · 7 ajan · 120 web becerisi (Sv100)

Envanter: **50 gömülü fotoğraf · 180 gömülü klip · 16 font dosyası (7 aile) · 2 kütüphane · 120 web becerisi**

Sitede: **3 sektör fotoğrafı + aynı fotoğraflardan üretilen 3 klip** · tekrar eden klip: **0** · sektör başına: **12 farklı klip**

## Gömülü envanter

| Bileşen | Adet | Lisans / not |
|---|---:|---|
| Yerel fotoğraf (JPEG) | 50 | Türkiye kareleri; stok/yabancı görsel yok · müşterinin kendi fotoğraflarıyla değiştirilir |
| Gömülü klip (MP4) | 180 | Kendi Türkiye karelerimizden (kadraj + yavaş kaydırma) · 720p · sessiz · 6 sn |
| Sitede klip | 3 | Sitenin kendi fotoğraflarından üretilir (yavaş kaydırma) · poster ile aynı sahne |
| Lisanslı font | 16 dosya · 7 aile | Fontshare Free + SIL OFL 1.1 · Türkçe latin-ext |
| Hareket kütüphanesi | 2 | MIT (Lenis 1.1.18, anime.js 3.2.2) |
| Web becerisi | 120 | Her ajan Sv100 |
| Ajans oyun kitabı | 10 disiplin | Gömülü; her üretimde `oyun-kitabi.md` |

## Sektör klip havuzları

Her sektörün 12 klibi, o sektörün üç Türkiye fotoğrafının dört ayrı kadrajından
üretilir; yabancı stok görüntü kullanılmaz.

| Sektör | Klip | Kaynak |
|---|---:|---|
| Kafe | 12 | kendi Türkiye karelerimiz |
| Kadın kuaförü | 12 | kendi Türkiye karelerimiz |
| Erkek berber | 12 | kendi Türkiye karelerimiz |
| Diş | 12 | kendi Türkiye karelerimiz |
| Emlak | 12 | kendi Türkiye karelerimiz |
| Spor | 12 | kendi Türkiye karelerimiz |
| Genel | 12 | kendi Türkiye karelerimiz |
| Avukat | 12 | kendi Türkiye karelerimiz |
| Anaokulu | 12 | kendi Türkiye karelerimiz |
| Veteriner | 12 | kendi Türkiye karelerimiz |
| Oto servis | 12 | kendi Türkiye karelerimiz |
| Oto çekici | 12 | kendi Türkiye karelerimiz |
| Temizlik | 12 | kendi Türkiye karelerimiz |
| Tesisat | 12 | kendi Türkiye karelerimiz |
| Nakliyat | 12 | kendi Türkiye karelerimiz |

## Ajan kaynakları (repo & skill)

| Kaynak | Ne için | Bağlantı |
|---|---|---|
| Instrument Serif | Lüks/editoryal başlık (SIL OFL) | https://github.com/Instrument/instrument-serif |
| Instrument Sans | Nötr gövde metni, Türkçe latin-ext (SIL OFL) | https://github.com/Instrument/instrument-sans |
| Fraunces | Değişken soft-serif başlık (SIL OFL) | https://github.com/googlefonts/fraunces |
| Clash Display | Sıkı grotesque başlık (Fontshare Free) | https://www.fontshare.com/fonts/clash-display |
| Satoshi | Gövde ve arayüz metni (Fontshare Free) | https://www.fontshare.com/fonts/satoshi |
| SIL OFL 1.1 | Font lisansı ve gömme izni | https://openfontlicense.org |
| Anthropic frontend-design skill | Tipografi ve şablon tuzağı kontrol listesi | https://github.com/anthropics/skills |
| frontend-design-skills | Web tipografi ve sanat yönetimi becerileri (MIT) | https://github.com/flitzrrr/frontend-design-skills |
| Front-End Design Checklist | Erişilebilirlik ve yayın öncesi kontrol (CC0) | https://github.com/thedaviddias/Front-End-Design-Checklist |
| awwwards-web-design | Ödüllü site hareket ve grid referansı | https://github.com/owenisas/awwwards-web-design |
| Lenis | Sinematik yumuşak kaydırma (MIT) | https://github.com/darkroomengineering/lenis |
| anime.js | Zaman çizgisi ve easing (MIT) | https://github.com/juliangarnier/anime |
| Wikimedia Commons | İl/ilçe fotoğrafları (CC BY-SA) | https://commons.wikimedia.org |
| Google Maps | İşletme/şehir fotoğrafları (işletme sahibi) | https://www.google.com/maps |
| Tabler Icons | Satır içi SVG ikon seti (MIT) | https://github.com/tabler/tabler-icons |
| Ajans oyun kitabı | 10 disiplin, 120 beceri, QA rubriği (bu depo) | skills/ajans-playbook |
| Anthropic frontend-design | Tipografi, hiyerarşi ve şablon tuzağı (Apache-2.0) | https://github.com/anthropics/skills/tree/main/skills/frontend-design |
| Awwwards web design skill | Jüri ölçütleri, 732 site korpusu (MIT) | https://github.com/owenisas/awwwards-web-design |

## Lisans ve indirme politikası

- Sektör envanteri uygulamanın içine gömülüdür; site üretmek için internet gerekmez.
- İl/ilçe adı metinde ve harita bağlantısında kullanılır; siteye dışarıdan fotoğraf indirilmez, üretim ağ olmadan da çalışır.
- Kahraman görsel, galeri, iş kartları ve üç klip sektörün kendi gömülü setinden gelir; her üretim aynı görsel dili korur.
- Üretilen sitede CDN, harici font, harici video veya API çağrısı yoktur; tüm yollar görelidir.
- Ajan yeni klip gerekirse `scripts/tr_medya.sh` ile kendi Türkiye karelerimizden üretir (ffmpeg, 720p).
- Yabancı stok görsel ve video arşivden tamamen çıkarıldı; sitede yabancı stok kare yoktur.
- Fotoğraf ve kliplerin kaynağı: uygulamayla gelen Türkiye kareleri; filtre/kadraj uygulaması uygulamanın kendisinde.
- Fontlar: Clash Display, Satoshi, Gambetta (Fontshare Free License); Bricolage Grotesque, Fraunces, Manrope (SIL OFL 1.1, Google Fonts). Hepsi Türkçe tam kapsamlı ve gömülüdür; harici istek yoktur.
- Lenis kaynağı: https://github.com/darkroomengineering/lenis
- anime.js kaynağı: https://github.com/juliangarnier/anime
- Font kaynakları: https://www.fontshare.com/fonts/clash-display · https://www.fontshare.com/fonts/satoshi · https://www.fontshare.com/fonts/gambetta
- Fontshare lisansı: https://www.fontshare.com/licenses/free
- SIL OFL 1.1: https://openfontlicense.org — Bricolage Grotesque, Fraunces, Manrope
