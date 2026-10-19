# 2 · Otomasyon Kurulumu

Tanımlı çözümün tasarımı, kontrollü kurulumu, testi, temel kullanım eğitimi ve teknik devri. **Ayrı proje kabulü ve insan teknik sorumlu gerektirir.**

## Giriş koşulu

AI Audit karar dosyası **veya** müşterinin/başka uygulayıcının eşdeğer kapsam, başlangıç ölçümü ve kabul koşullarını içeren şartnamesi (uygunluk kontrolüyle).

## Akış (§7.1 · 7, görev 5.1–5.3)

Onaylı şartname → test ortamı / gölge çalışma → ayrı kabul seti → insan kabulü → gerçek kullanım değeri → devam veya kapanış.

## Yetki kuralları

- Mesaj gönderme, veri değiştirme, ödeme/iade ve canlı yazma, taslak üretiminden **ayrı yetki** taşır.
- Onay ve durdurma kontrolleri yalnız model istemine bırakılmaz.
- Kabul öncesi canlı işlem yoktur; otomatik canlıya geçiş yoktur.

## Teslimatlar

- Pilot şartnamesi → [templates/implementation/pilot-spec.md](../../templates/implementation/pilot-spec.md)
- Test planı → [templates/implementation/test-plan.md](../../templates/implementation/test-plan.md)
- Teknik devir → [templates/implementation/handover.md](../../templates/implementation/handover.md)
- Çözüm kodu → [`solutions/`](../../solutions/)

Kapı: G3
