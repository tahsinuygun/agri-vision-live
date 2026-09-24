# AgriVision Segmentation Lab

BarnSeg-ECA-Lite ile canlı kamera tabanlı instance segmentasyon eğitim uygulaması.

## Sınıflar ve maske renkleri

- Buffalo Head — magenta
- Feed — yeşil
- MLB — cyan

## Özellikler

- Mobil tarayıcı kamerasından canlı segmentasyon
- Instance maskeleri ve güven skoru
- Sınıf bazlı anlık örnek sayısı
- Sınıf bazlı yaklaşık maske alanı (%)
- Güven ve maske eşiği ayarı
- Dondurma / devam ettirme
- Maskeleri gösterme / gizleme
- Ön/arka kamera değiştirme

## Model

Web modeli şu konumda olmalıdır:

`segmentation/model/model.onnx`

Giriş boyutu: `640 × 640`

Sınıf sırası:

```text
0: Buffalo Head
1: Feed
2: MLB
```

## Bilimsel kaynak

Uygun, T.; Yılmaz, H.; Çoşlu, M.; Ungureanu, N.; Ünal, İ. (2026). *BarnSeg-ECA-Lite: A Lightweight Instance Segmentation Model for Feed, Buffalo Heads, and Mineral Lick Blocks in Buffalo Barn Environments.* Agriculture, 16(18), 2004.

https://www.mdpi.com/2077-0472/16/18/2004

## Eğitim

Bu uygulama, TÜBİTAK 2237-A “Tarımda Dijital Dönüşüm: Web Tabanlı Yapay Zekâ Uygulamaları Eğitimi” kapsamında Dr. Öğr. Üyesi Tahsin UYGUN tarafından hazırlanmıştır.
