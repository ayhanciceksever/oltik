# /PLANNER · Görev kırılımı

Tüm görevlerin başlangıç durumu: **Öneri / başlanmadı.** P0 = ön koşul · P1 = ücretli öğrenme ve tekrarlanabilir teslimat · P2 = kanıt sonrası yatırım. Öncelik tarih değildir.

| Kod | Görev | Öncelik | Bağımlılık | Durum |
|---|---|---|---|---|
| 1.1 | Kurucu sınır ve başarı kartı | P0 | — | Başlanmadı |
| 1.2 | Tek segment, alıcı ve karar problemi | P0 | 1.1 | Başlanmadı |
| 1.3 | Hipotez ve karar kayıtları | P0 | 1.2 | Başlanmadı |
| 2.1 | Tek akış teslimatı ve kapsamı | P0 | 1.2 | Başlanmadı |
| 2.2 | Veri kabulü ve güvenli çalışma prosedürü | P0 | 2.1 | Başlanmadı |
| 2.3 | Zorunlu uzman kapsamı ve maliyeti | P0 | 2.1 | Başlanmadı |
| 2.4 | Sentetik örnek karar paketi ve kalite kontrolü | P0 | 2.1–2.3 | Başlanmadı |
| 2.5 | A/B ticari teklifler ve maliyet tabanı | P0 | 1.1, 2.1, 2.3 | Başlanmadı |
| 3.1 | Ulaşılabilir aday ve kanal listesi | P1 | 1.2 | Başlanmadı |
| 3.2 | Problem, satın alma ve çıktı görüşmeleri | P1 | 3.1, 2.4 | Başlanmadı |
| 3.3 | Ücretli teklif sınaması | P1 | 2.2–2.5, 3.2 | Başlanmadı |
| 3.4 | A veya B modelini kanıtla seç | P1 | 3.3 | Başlanmadı |
| 4.1 | Müşteri kabulü, veri ve rol onayları | P0 | 2.2–2.5, 3.3 | Başlanmadı |
| 4.2 | Süreç ve başlangıç kanıtı | P1 | 4.1 | Başlanmadı |
| 4.3 | Alternatif, ekonomi ve risk karar dosyası | P1 | 4.2 | Başlanmadı |
| 4.4 | Kararı teslim et ve analizi kapat | P1 | 4.3 | Başlanmadı |
| 5.1 | Pilot kabul sözleşmesi ve test planı | P2 | 4.4 | Başlanmadı |
| 5.2 | Kontrollü sürüm, test ve insan kabulü | P2 | 5.1 | Başlanmadı |
| 5.3 | Gerçek değer, bakım ihtiyacı ve kapanış | P2 | 5.2 | Başlanmadı |
| 6.1 | Gerçek iş ekonomisi ve nakit durumu | P1 | kapanmış iş | Başlanmadı |
| 6.2 | Darboğaz düzeltme ve standart teslim yöntemi | P1 | 6.1 | Başlanmadı |
| 6.3 | Bağımsız müşteride ve kanalda tekrar | P1 | 3.4, 6.2 | Başlanmadı |
| 7.1 | Tek iç darboğazı araçlaştır | P2 | 6.2 | Başlanmadı |
| 7.2 | Tekrar eden takip işi ve ödeme | P2 | canlı kullanım | Başlanmadı |
| 7.3 | Tek dış ürün alıcısı ve görev | P2 | tekrar sinyali | Başlanmadı |
| 7.4 | Hizmet / iç araç / dar ürün kararı | P2 | 7.1–7.3 | Başlanmadı |
| 8.1 | Gösterge ve karar paneli | P1 | 1.3 | Başlanmadı |
| 8.2 | Kaynak, araç ve kapsam değişikliği yönetimi | P0 | 2.2, 2.4 | Başlanmadı |
| 8.3 | İzinli vaka ve yöntem birikimi | P2 | doğrulanmış sonuç | Başlanmadı |

Görev ayrıntıları (ne / nasıl / girdi → çıktı / tamamlanma / geçiş) Notion · Oltik · İş Planı §11'dedir.
