# YDS 19 Aralık – Adaptif Öğretmen (Ücretsiz PWA)

Bu paket Replit kullanmaz. Statik HTML/CSS/JS + IndexedDB ile çalışır.

## En sağlam ücretsiz kullanım: GitHub Pages

1. GitHub'da yeni bir **public** repository oluşturun (ör. `yds-ogretmen`).
2. Bu ZIP içindeki dosyaların tamamını repository köküne yükleyin.
3. Repository > **Settings > Pages**.
4. Source olarak **Deploy from a branch**, branch olarak `main`, klasör olarak `/ (root)` seçin.
5. GitHub'ın verdiği `https://...github.io/.../` adresini açın.
6. Telefonda veya masaüstünde tarayıcı menüsünden uygulamayı ana ekrana / uygulamalar arasına ekleyebilirsiniz.

Bu sabit URL'de:
- ilerleme IndexedDB'de kalır,
- aynı cihaz/tarayıcıda kapatıp açınca kaldığınız ders/soru/açıklama aşamasından devam eder,
- çevrimdışı çalışabilir,
- `content-feed.json` güncellendiğinde açılışta yeni içeriği birleştirebilir.

## Neden önceki ChatGPT HTML önizlemesinden daha sağlam?

ChatGPT sandbox önizleme URL'leri izole/geçici origin kullanabilir. GitHub Pages tek ve sabit origin verdiği için IndexedDB aynı siteye bağlı kalır.

## Yedek

Uygulamada **Yedek al** ile JSON ilerleme dosyası indirin. Tarayıcı verisi silinirse **Ayarlar > İlerleme yedeği** ile geri yüklenebilir.

## Çalışma planı

- Standart gün: **90 dk**
  - 15 dk spaced review
  - 25 dk odak grammar/kelime
  - 35 dk karma YDS
  - 15 dk yanlış + aktif hatırlama
- Çok yoğun/nöbet günü: **45 dk**
- Haftada 1 uzun gün: **150 dk**
- Son 4 gün: yeni içerik minimum, yanlış/tekrar/hız maksimum
- Sınav günü: 10–15 dk hafif warm-up

## Bulut senkronizasyonu

Bu sürüm aynı cihaz/tarayıcıda kalıcıdır. Birden fazla cihaz arasında otomatik senkronizasyon istenirse ileride ücretsiz Supabase katmanı eklenebilir.
