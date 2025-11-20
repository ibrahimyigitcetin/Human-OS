# HUMAN OS // FINALITY v12.1

**Kişisel Yaşam Simülatörü & Bio-Feedback Dashboard**

> Tek bir HTML dosyasında çalışan, tamamen istemci taraflı (offline-first), yerel depolama (localStorage) kullanan, cyberpunk/neon arayüzlü kişisel yaşam takip ve bio-simulation sistemi.

## Özellikler

- **Zero Dependency** – Harici kütüphane, framework veya sunucu yok
- **Tamamen Offline** – İnternet bağlantısı gerekmez
- **Cyberpunk UI** – Neon temalı, HUD tarzı responsive arayüz
- **Neural Topology Canvas** – Fizik tabanlı görsel geri bildirim (Web Canvas API)
- **Pomodoro + Manuel Veri Girişi** – Derin çalışma, öğrenme, yaratıcılık, fitness, dinlenme vb. kategoriler
- **Bio-Reactor Simülasyonu** – Enerji (Battery) ve Stres seviyesi gerçek zamanlı hesaplaması
- **AUTO-SIM Modu** – Hayatınızı otomatik simüle eder (eğlence + stres testi)
- **Radar Dağılım Grafiği** – Yaşam alanlarınızın dengesini görselleştirir
- **Kernel Terminal** – Tüm olaylar canlı olarak terminalde loglanır
- **Veri Yönetimi**
  - JSON & CSV dışa aktarma
  - JSON içe aktarma
  - Factory Reset (tam sıfırlama)
- **İlk Kullanım Rehberi** – Spotlight-style interaktif tur
- **localStorage Kalıcılığı** – Tarayıcı kapandıktan sonra verileriniz korunur


## Hızlı Başlangıç (1 Dakika)

1. Dosyayı indirin veya aşağıdaki kodu kopyalayın:
   ```html
   <!-- human-os-v12.1.html -->
   ```

2. `human-os-v12.1.html` adıyla kaydedin

3. Tarayıcıda açın → Hazır!

> Hiçbir kurulum, npm, python veya sunucu gerekmez.

## Kullanım

| Bölüm | Açıklama |
|-------|----------|
| CONTROL DECK | Manuel veri girişi & Pomodoro timer |
| NEURAL TOPOLOGY | Girilen her aktivite görsel node olarak eklenir |
| BIO-REACTOR | Enerji ve stres seviyenizi canlı gösterir |
| RADAR DISTRIBUTION | Yaşam dengesi (work/rest/social/chaos) radar |
| SYSTEM KERNEL | Tüm olayların terminal stili logu |
| AUTO-SIM | Sistemi kendi kendine veri üretmeye bırakır |

## Veri Modeli

Her giriş şu yapıda `localStorage`'a kaydedilir:

```json
{
  "type": "work | learn | create | fit | soc | rest | chaos",
  "dur": 60,
  "note": "Proje teslimi",
  "ts": "2025-11-21T14:32:18.123Z"
}
```

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/AmazingFeature`)
3. Commit edin (`git commit -m 'Add some AmazingFeature'`)
4. Push edin (`git push origin feature/AmazingFeature`)
5. Pull Request açın

Detaylar için [CONTRIBUTING.md](CONTRIBUTING.md) ve [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) dosyasını inceleyiniz.

## 📄 Lisans

Bu proje MIT lisansı altında dağıtılmaktadır. Detaylar için [LICENSE.md](LICENSE.md) dosyasını inceleyiniz.

## Teşekkürler

- Cyberpunk 2077, Deus Ex ve Ghost in the Shell'dan ilham
- Tüm gece kodlayanlar ve neon ışıklar altında kahve içenler ❤️

---

**HUMAN OS // FINALITY v12.1**

CTRL + ALT + DEL → Yeniden doğ.
