# Yol haritası · Aşamalar ve karar kapıları

**Bu yol haritası takvim değildir.** Sıra, önceki adımdan hangi kanıtın gerektiğini gösterir. Her kapı “devam / eksik kanıtı tamamla / kapsamı değiştir / dur” sonucu verebilir.

| Aşama | Görevler | Kapı | Geçiş kanıtı | Durum |
|---|---|---|---|---|
| A · İş ve teklif temeli | 1.1–1.3, 2.1–2.5, 3.1 | **G0** Satılabilir hazırlık | Tek segment/akış, A/B kapsamı, sentetik örnek, maliyet dayanağı, veri prosedürü, gerekli uzman | Başlanmadı |
| B · Ödemeyi sına | 3.2–3.4 | **G1** İlk talep kanıtı | Bağımsız ödeme ve gerçek karar ihtiyacı; A ve B ayrı | Başlanmadı |
| C · Ücretli analizi teslim et | 4.1–4.4, 6.1 | **G2** Kullanışlı ve ekonomik teslim | Kullanılan karar, izlenebilir kanıt, kapanış, emek dahil katkı | Başlanmadı |
| D · Gerekirse pilot | 5.1–5.3 | **G3** Pilot sonucu | Kalite/kontrol, gerçek kullanım, değer | Başlanmadı |
| E · Tekrar edilebilir hizmet | 6.2–6.3, 8.1 | **G4** Tekrar eden hizmet | Bağımsız ücretli tekrar, sürdürülebilir katkı | Başlanmadı |
| F · İç araç / takip | 7.1, 7.2 | **G5** Ayrı yatırım gerekçesi | Net yarar; takipte ödeme ve katkı | Başlanmadı |
| G · Dar dış ürün | 7.3–7.4 | **G6** Ürün deneyi kararı | Kullanıcı-görev-ödeme örüntüsü | Başlanmadı |

## Kritik bağımlılık zinciri

1.1 sınırlar → 1.2 segment → 2.1 kapsam → 2.3 uzman/maliyet → 2.4 örnek + 2.5 teklif → 3.3 gerçek ödeme → 4.1 veri/rol kapısı → 4.2 kanıt → 4.3 seçenek/ekonomi → 4.4 kullanılan karar → 6.1 gerçek katkı → 6.3 bağımsız tekrar → ürün kanıtı

Yan ön koşullar: 2.2 veri prosedürü, 3.1 erişim kanalı.

## Depodaki karşılığı

| Kapı | Depoda açılan alan |
|---|---|
| G0 | `docs/`, `templates/`, `engagements/_synthetic-example/` |
| G2 | `engagements/<müşteri-kodu>/` (yerel, commit edilmez) |
| G3 | `solutions/<çözüm>/` |
| G5 | `tools/<araç>/` |
| G6 | Ayrı karar kaydı ile yeni ürün alanı (bugün yok) |

**Şimdilik dışarıda:** Genel amaçlı AI audit SaaS, otomatik keşif ajanı, geniş entegrasyon kataloğu, kendi modelini eğitmek, sertifika vaadi, otomatik ödeme/iade, çoklu ajanı baştan kurmak, izinsiz veri havuzu.

Görev kırılımı: [tasks.md](tasks.md)
