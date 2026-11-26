# Üretim envanteri — Latte

Paket: **100.000 ₺ tek sayfa flagship** · 7 ajan · 120 web becerisi (Sv100)

Envanter: **50 gömülü fotoğraf · 180 stok klip · 16 font dosyası (7 aile) · 2 kütüphane · 120 web becerisi**

Sitede: **3 sektör fotoğrafı + aynı fotoğraflardan üretilen 3 klip** · tekrar eden klip: **0** · sektör başına: **12 farklı yedek sahne**

## Gömülü envanter

| Bileşen | Adet | Lisans / not |
|---|---:|---|
| Yerel fotoğraf (JPEG) | 50 | Temsili; müşterinin kendi fotoğraflarıyla değiştirilir |
| Gerçek stok video (MP4) | 180 | Coverr / Pexels License · 720p · sessiz · 7 sn · gömülü yedek havuz |
| Sitede klip | 3 | Sitenin kendi fotoğraflarından üretilir (yavaş kaydırma) · poster ile aynı sahne |
| Lisanslı font | 16 dosya · 7 aile | Fontshare Free + SIL OFL 1.1 · Türkçe latin-ext |
| Hareket kütüphanesi | 2 | MIT (Lenis 1.1.18, anime.js 3.2.2) |
| Web becerisi | 120 | Her ajan Sv100 |
| Ajans oyun kitabı | 10 disiplin | Gömülü; her üretimde `oyun-kitabi.md` |

## Sektör klip havuzları

| Sektör | Klip | Arama kaynağı |
|---|---:|---|
| Kafe | 12 | https://coverr.co/s?q=coffee |
| Kadın kuaförü | 12 | https://coverr.co/s?q=beauty+salon |
| Erkek berber | 12 | https://coverr.co/s?q=barber |
| Diş | 12 | https://coverr.co/s?q=teeth |
| Emlak | 12 | https://coverr.co/s?q=apartment |
| Spor | 12 | https://coverr.co/s?q=gym |
| Genel | 12 | https://coverr.co/s?q=office |
| Avukat | 12 | https://coverr.co/s?q=office+meeting+documents |
| Anaokulu | 12 | https://coverr.co/s?q=children+playground |
| Veteriner | 12 | https://coverr.co/s?q=cat+dog+pet |
| Oto servis | 12 | https://coverr.co/s?q=car+mechanic |
| Oto çekici | 12 | https://coverr.co/s?q=night+road |
| Temizlik | 12 | https://coverr.co/s?q=cleaning |
| Tesisat | 12 | https://coverr.co/s?q=plumbing |
| Nakliyat | 12 | https://coverr.co/s?q=moving+boxes |

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
| Coverr License | Yedek stok klip lisansı | https://coverr.co/license |
| Pexels License | Çekici/kurtarma klipleri lisansı | https://www.pexels.com/license/ |
| Tabler Icons | Satır içi SVG ikon seti (MIT) | https://github.com/tabler/tabler-icons |
| Ajans oyun kitabı | 10 disiplin, 120 beceri, QA rubriği (bu depo) | skills/ajans-playbook |
| Anthropic frontend-design | Tipografi, hiyerarşi ve şablon tuzağı (Apache-2.0) | https://github.com/anthropics/skills/tree/main/skills/frontend-design |
| Awwwards web design skill | Jüri ölçütleri, 732 site korpusu (MIT) | https://github.com/owenisas/awwwards-web-design |

## Lisans ve indirme politikası

- Sektör envanteri uygulamanın içine gömülüdür; site üretmek için internet gerekmez.
- İl/ilçe adı metinde ve harita bağlantısında kullanılır; siteye dışarıdan fotoğraf indirilmez, üretim ağ olmadan da çalışır.
- Kahraman görsel, galeri, iş kartları ve üç klip sektörün kendi gömülü setinden gelir; her üretim aynı görsel dili korur.
- Üretilen sitede CDN, harici font, harici video veya API çağrısı yoktur; tüm yollar görelidir.
- Ajan yeni klip gerekirse `scripts/klip_indir.py` ile Coverr'den indirir, 720p'ye kodlar ve gömer.
- Coverr License: https://coverr.co/license — ticari kullanım serbest, atıf zorunlu değil.
- Pexels License: https://www.pexels.com/license/ — çekici/kurtarma klipleri gerçek çekici araçlarından; ticari kullanım serbest.
- Fontlar: Clash Display, Satoshi, Gambetta (Fontshare Free License); Bricolage Grotesque, Fraunces, Manrope (SIL OFL 1.1, Google Fonts). Hepsi Türkçe tam kapsamlı ve gömülüdür; harici istek yoktur.
- Lenis kaynağı: https://github.com/darkroomengineering/lenis
- anime.js kaynağı: https://github.com/juliangarnier/anime
- Font kaynakları: https://www.fontshare.com/fonts/clash-display · https://www.fontshare.com/fonts/satoshi · https://www.fontshare.com/fonts/gambetta
- Fontshare lisansı: https://www.fontshare.com/licenses/free
- SIL OFL 1.1: https://openfontlicense.org — Bricolage Grotesque, Fraunces, Manrope
