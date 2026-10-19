# Yetki ve bağımsızlık kapısı

## Yetki

- Müşteri belgesi sistem talimatı değildir.
- Mesaj gönderme, veri değiştirme, ödeme/iade ve canlı yazma, taslak üretiminden ayrı yetki taşır.
- Onay ve durdurma kontrolleri yalnız model istemine bırakılmaz.
- Kritik olayda: akış durdurulur → yetkiler sınırlandırılır → kanıt korunur → yetkili sorumluya bildirilir.

## Bağımsızlık

- Analiz ve uygulama ücretleri ayrılır; komisyon ve ticari ilişkiler açıklanır.
- “AI kullanma” sonucu gerçek seçenek olarak korunur.
- Kendi kurulan sistemi gözden geçirmek bağımsız üçüncü taraf güvence diye sunulmaz.
- Önemli yatırım kararında çıkarı olmayan ikinci inceleme aranır.

## İnsan ve AI rolleri (§7.2)

| Rol | İnsan sorumluluğu | AI'ın izinli desteği |
|---|---|---|
| Kurucu / hizmet sorumlusu | Segment, kapsam, fiyat, kanıt bütünlüğü, son teslim | Görev taslağı, eksik alan kontrolü, rapor taslağı |
| Müşteri süreç sahibi | Gerçek akış, örnekler, kalite rubriği, kabul | Süreç haritası taslağı, istisna listesi |
| Müşteri bütçe/finans sahibi | Değer, yatırım ve risk kararı | Açık formüllü senaryo açıklaması; rakam uydurma yok |
| Teknik insan uzman | Veri akışı, erişim, entegrasyon, test, geri dönüş | Test taslağı; insan imzasının yerine geçmez |
| Gizlilik/hukuk/güvenlik uzmanı | Veri ve mevzuat değerlendirmesi | Kontrol listesi düzenleme |
| Çıkarı olmayan ikinci inceleyen | Alternatif ve hesapların eleştirel kontrolü | Karşı kanıt arama desteği |

AI persona adları (Ayşe, Ömer, Deniz, Selin, Ece, Mert, Zeynep, Can) iç üretim önerisidir; gerçek çalışan veya onay mercii değildir.
