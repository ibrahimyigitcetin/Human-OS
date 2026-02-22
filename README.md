<div align="center">
  <img src="https://img.shields.io/github/languages/count/ibrahimyigitcetin/Human-OS?style=flat-square&color=blueviolet" alt="Language Count">
  <img src="https://img.shields.io/github/languages/top/ibrahimyigitcetin/Human-OS?style=flat-square&color=1e90ff" alt="Top Language">
  <img src="https://img.shields.io/github/last-commit/ibrahimyigitcetin/Human-OS?style=flat-square&color=ff69b4" alt="Last Commit">
  <img src="https://img.shields.io/github/license/ibrahimyigitcetin/Human-OS?style=flat-square&color=yellow" alt="License">
  <img src="https://img.shields.io/badge/Status-Active-green?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/Contributions-Welcome-brightgreen?style=flat-square" alt="Contributions">
</div>

# 🌿 HUMAN-OS

**Kişisel Yaşam Simülatörü & Bio-Feedback Dashboard**  
> Tek bir HTML dosyasında çalışan, tamamen istemci taraflı (offline-first), localStorage kullanan, cyberpunk/neon arayüzlü kişisel yaşam takip ve bio-simulation sistemi.

## ✨ Özellikler
- **Zero Dependency** – Harici kütüphane, framework veya sunucu yok  
- **Tamamen Offline** – İnternet bağlantısı gerekmez  
- **Cyberpunk HUD UI** – Neon temalı, tamamen responsive arayüz  
- **Neural Topology Canvas** – Fizik tabanlı node & bağlantı görselleştirme (Web Canvas API)  
- **Pomodoro + Manuel Veri Girişi** – Derin çalışma, öğrenme, yaratıcılık, fitness, sosyal, dinlenme, kaos kategorileri  
- **Bio-Reactor Simülasyonu** – Gerçek zamanlı Enerji (Battery) ve Stres hesaplaması  
- **AUTO-SIM Modu** – Otomatik rastgele yaşam simülasyonu (test & eğlence)  
- **Radar Distribution Grafiği** – Yaşam dengesi (Work / Rest / Social / Entropy)  
- **Kernel Terminal** – Tüm olayların canlı loglanması  
- **Veri Yönetimi**  
  - JSON & CSV dışa aktarma  
  - JSON içe aktarma  
  - Factory Reset (tam sıfırlama)  
- **İlk Kullanım Rehberi** – 8 adımlı interaktif spotlight tur  
- **localStorage Kalıcılığı** – Tarayıcı kapandıktan sonra veriler korunur  

## 🚩 Hızlı Başlangıç
1. Aşağıdaki kodu tamamen kopyalayın veya dosyayı indirin  
2. `human_OS.html` adıyla kaydedin  
3. Tarayıcıda açın → Hemen çalışır!  

> Hiçbir kurulum, npm, sunucu veya hesap gerekmez.

## 💡 Kullanım
| Bölüm              | Açıklama                                                                 |
|--------------------|--------------------------------------------------------------------------|
| CONTROL DECK       | Manuel aktivite girişi & Pomodoro timer                                   |
| NEURAL TOPOLOGY    | Her aktivite fizik tabanlı neon node olarak eklenir                      |
| BIO-REACTOR        | Enerji (Battery) ve stres seviyesi canlı gösterilir                      |
| RADAR DISTRIBUTION | Yaşam alanlarının (Work / Rest / Social / Entropy) dengesi               |
| DATA STREAM        | Son 15 aktivite logu                                                     |
| SYSTEM KERNEL      | Canlı terminal logları                                                   |
| AUTO-SIM           | Header’daki toggle ile otomatik simülasyonu aç/kapat                     |

## Veri Modeli (localStorage)
```json
{
  "logs": [
    {
      "type": "work | learn | create | fit | soc | rest | chaos",
      "dur": 60,
      "note": "Proje teslimi",
      "ts": "2025-11-28T14:32:18.123Z"
    }
  ],
  "battery": 94.5,
  "stress": 23
}
```

## Enerji & Stres Hesaplama (saat başına)
| Aktivite   | Enerji Değişimi | Stres Değişimi |
|------------|-----------------|----------------|
| work       | -10             | +15            |
| learn      | -5              | +5             |
| create     | —               | —              |
| fit        | -10             | -15            |
| soc        | -5              | -10             |
| rest       | +30             | -20            |
| chaos      | -15             | +20            |


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

**HUMAN OS // FINALITY**

CTRL + ALT + DEL → Yeniden doğ.
