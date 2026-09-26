# Kadro — Organizasyon Şeması

Tarayıcıda çalışan, kurulum gerektirmeyen organizasyon şeması düzenleyici.

**Canlı sürüm:** https://muratyk1.github.io/org-chart/

## Özellikler
- Katman ekleme, yeniden adlandırma, sıralama ve silme
- Kutulara pozisyon adı, kişi adı, fotoğraf ve birim rengi
- Kutuları bağlama / bağlantı çözme, otomatik hizalama
- Yakınlaştırma, kaydırma, ekrana sığdırma (dokunmatik destekli)
- Birden fazla şema, Taslak / Yayında durumu, kopyalama
- Paylaşım bağlantısı (şema bağlantının içinde taşınır), PNG ve JSON dışa aktarma, JSON içe aktarma

## Veriler nerede saklanır?
Şemalar yalnızca kullandığınız tarayıcıda (localStorage) saklanır; sunucuya veri gönderilmez.
Başka cihaza taşımak veya yedeklemek için **Paylaş → JSON** ile indirip **Organizasyonlarım → JSON içe aktar** ile yükleyin.

Tek dosyalık bir uygulamadır: `index.html`.
