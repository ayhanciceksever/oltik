# Veri kapısı

Aşağıdakiler açık olmadan **gerçek veri kabul edilmez**:

- [ ] Amaç
- [ ] Gerekli alanlar (asgari veri)
- [ ] Alıcı kişi / hizmet
- [ ] İşleme ortamı
- [ ] Erişen roller
- [ ] Log içeriği
- [ ] Saklama / iade / silme kuralı
- [ ] Olay sahibi

## Kurallar

- Müşteri kaydını görme yetkisi, başka model veya hizmete gönderme yetkisi sayılmaz.
- Önce sentetik veya gerçekten anonimleştirilmiş veri; asgari erişim ve müşteri ayrımı.
- **Gerçek müşteri verisi bu depoya commit edilmez** (`.gitignore` ile korunur).
- Şifre ve API anahtarı rapor, form veya model girdisine konmaz.

## Prova

Sentetik müşteri A/B verisiyle dosya, arama, model çağrısı, log, rapor ve kapanış akışı denenir. Çapraz müşteri erişimi, yetkisiz alıcı veya kalıntı veri görülürse gerçek veri aşaması açılmaz. Prova verisi: [`data/synthetic/`](../../data/synthetic/)

Şablonlar: [`templates/data/`](../../templates/data/)
