# 0003 · Depo mimarisi: hizmet önce, kod kanıtla

- **Tarih:** 2026-10-19 · **Durum:** Önerildi

## Bağlam

İş planı; müşteri portalı, çok ajanlı platform veya özel model yatırımını başlangıç şartı saymaz. Platform ve geniş entegrasyon yatırımı kanıt kapıları açılmadan yapılmaz (§1, §9.5, §12.4). İlk değer, tek iş akışı için tekrarlanabilir analiz ve kurulum teslimatıdır.

## Karar

Depo tek bir monorepo olarak, iş planının katmanlarını izler:

1. `docs/` — strateji, hizmetler, yol haritası, politikalar, kararlar (docs-as-code, Markdown)
2. `templates/` — her müşteri işinde kopyalanan taşınabilir teslim şablonları
3. `engagements/` — müşteri işi klasörleri; gerçek veri `.gitignore` ile dışarıda
4. `solutions/` — Otomasyon Kurulumu için yeniden kullanılabilir çözüm bileşenleri (G3 sonrası büyür)
5. `tools/` — iç araçlar (G5 sonrası)
6. `data/synthetic/` — yalnız sentetik prova verisi

**Teknoloji varsayılanı:** İş planı teknoloji seçmez. Belgeler Markdown, kayıt şeması JSON Schema. Kod gerektiğinde varsayılan dil Python 3.12 (AI/otomasyon ekosistemi ve veri işleme için yaygın); her çözüm kendi klasöründe bağımsız paket olur.

## Yeniden açma koşulu

G6 geçilir ve ayrı bir dış ürün kararı verilirse, ürün kendi deposuna veya `apps/` alanına ayrı bir kararla taşınır.
