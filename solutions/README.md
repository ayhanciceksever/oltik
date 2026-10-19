# Çözümler (Otomasyon Kurulumu)

Seçilmiş ve ayrıca kabul edilmiş kurulumlar için yeniden kullanılabilir çözüm bileşenleri. **İlk pilot onaylanana kadar (G3 öncesi) burada kod yoktur.**

## Kurallar

- Her çözüm kendi klasöründe bağımsız bir pakettir: `solutions/<cozum-adi>/` (README, `pyproject.toml`, `src/`, `tests/`).
- Varsayılan dil: **Python 3.12** (bkz. [karar 0003](../docs/decisions/0003-repository-architecture.md)).
- Müşteriye özel yapılandırma ve sırlar çözüm koduna girmez; ortam değişkeni veya müşterinin sır yöneticisiyle verilir (`.env.example` örnek olarak tutulabilir).
- Taslak üretimi ile gönderme/yazma/ödeme yetkileri ayrı modüllerdir; onay ve durdurma kontrolleri koddadır, yalnız model istemine bırakılmaz.
- Model, istem, bilgi kaynağı ve araç sürümleri kaydedilir.
- Testler sentetik veriyle çalışır ([`data/synthetic/`](../data/synthetic/)).

## İlk aday (hipotez)

`reply-draft/` — kaynak gösteren müşteri cevabı taslağı (insan kontrol eder ve gönderir). Ancak pilot ayrıca seçilirse açılır.
