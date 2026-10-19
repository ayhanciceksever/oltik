# Oltik

**Oltik · AI ve Otomasyon Çözümleri.** İşletmelerin tekrarlayan operasyonlarını analiz eden, AI ve otomasyon için uygun fırsatları belirleyen, seçilen çözümleri kuran ve ihtiyaç halinde sürdürülmesini destekleyen bir teknoloji danışmanlığı ve çözüm şirketi.

Bu depo, Notion'daki **Oltik · İş Planı**'nın uygulandığı çalışma alanıdır. Plan hizmet odaklı başladığı için depo da önce **hizmetin tekrar edilebilir teslimatını** taşır: strateji ve kararlar, hizmet kapsamları, teslim şablonları, müşteri işleri ve yalnızca kanıt geldiğinde açılacak kod alanları.

> Bu depo; kurulmuş şirket, hazır ürün, müşteri başarısı veya kurulmuş uzman kadro iddiası içermez. Ürün/platform yatırımı iş planındaki kanıt kapılarına (G0–G6) bağlıdır.

## Klasör yapısı

```
oltik/
├── docs/                    # Strateji, hizmetler, yol haritası, politikalar, kararlar
│   ├── strategy/            # Konumlandırma, marka, iş modeli (A/B), ekonomi
│   ├── services/            # Dört hizmetin kapsam ve kabul sınırları
│   ├── roadmap/             # G0–G6 kapıları ve PLANNER görev kırılımı
│   ├── policies/            # Veri, kanıt, kalite, yetki ve bağımsızlık kapıları
│   └── decisions/           # Karar günlüğü (ADR) ve hipotez kayıtları
├── templates/               # Her müşteri işinde kopyalanan teslim şablonları
│   ├── proposal/            # A (ayrı analiz) ve B (ücretli keşif + kurulum) teklifleri
│   ├── audit/               # Süreç haritası, kanıt kartı, seçenekler, ekonomi, karar özeti
│   ├── implementation/      # Pilot şartnamesi, test planı, teknik devir
│   ├── data/                # Veri kabul matrisi, onay ve kapanış kontrol listesi
│   └── records/             # Asgari kayıt şeması (iş kaydı)
├── engagements/             # Müşteri işleri (gerçek veri asla commit edilmez)
│   └── _synthetic-example/  # Sentetik, açıkça etiketli örnek karar paketi (görev 2.4)
├── solutions/               # Otomasyon Kurulumu için yeniden kullanılabilir çözüm bileşenleri
├── tools/                   # İç araçlar (görev 7.1, kanıt sonrası açılır)
└── data/synthetic/          # Yalnızca sentetik/anonim prova verisi
```

## Nereden başlamalı?

İş planına göre ilk ele alınacak görevler:

1. **1.1** Kurucu sınır kartı → [`docs/strategy/founder-boundaries.md`](docs/strategy/founder-boundaries.md)
2. **1.2** Tek segment / karar kartı → [`docs/strategy/segment-card.md`](docs/strategy/segment-card.md)
3. **2.1** Tek akış kapsamı → [`docs/services/ai-audit.md`](docs/services/ai-audit.md)

Paralelde: **3.1** erişim araştırması ve **2.3** uzman ihtiyacı. Ayrıntı için [`docs/roadmap/README.md`](docs/roadmap/README.md).

## Temel kurallar

- **Gerçek müşteri verisi bu depoya girmez.** Yalnızca sentetik veya gerçekten anonimleştirilmiş veri (bkz. [`docs/policies/data-acceptance.md`](docs/policies/data-acceptance.md)).
- **Şifre ve API anahtarı** hiçbir dosyaya, şablona veya model girdisine konmaz.
- Her önemli sayı **ölçüldü / kayıtla desteklendi / görüşmeye dayanıyor / bilinmiyor** olarak etiketlenir.
- Kod alanları (`solutions/`, `tools/`) ancak ilgili kapı geçildiğinde büyür; platform önce yazılmaz.

Kaynak: Notion · Oltik · İş Planı (§1–§15).
