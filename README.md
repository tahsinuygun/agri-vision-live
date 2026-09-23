# AgriVision Live

Mobil tarayıcı üzerinden tarımsal görüntülerde canlı nesne tespiti ve anlık sınıf bazlı sayım yapan etkileşimli eğitim uygulaması.

## Özellikler

- Telefonun arka/ön kamerası ile canlı analiz
- Full Ripe ve Unripe sınıfları
- Tespit kutusu, sınıf adı ve güven skoru
- Sınıf bazlı ve toplam anlık sayım
- Güven eşiği ayarı
- Tespiti dondurma / devam ettirme
- Mobil uyumlu arayüz

## Model

Web için dışa aktarılmış dosya şu konumda bulunmalıdır:

`model/model.onnx`

Giriş boyutu: `640 × 640`

Sınıf sırası:

```text
0: Full Ripe
1: Unripe
```

## Eğitim bilgisi

Bu uygulama, TÜBİTAK 2237-A “Tarımda Dijital Dönüşüm: Web Tabanlı Yapay Zekâ Uygulamaları Eğitimi” kapsamında Dr. Öğr. Üyesi Tahsin UYGUN tarafından hazırlanmıştır.
