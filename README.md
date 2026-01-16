# v2rayNG (Custom Fork)

Android için geliştirilmiş, **V2Ray / Xray** çekirdeklerini destekleyen açık kaynaklı bir VPN istemcisidir.  
Bu depo, orijinal **v2rayNG** projesi temel alınarak oluşturulmuş olup **arayüz, logo ve kullanıcı deneyimi** tarafında özelleştirmeler içeren bir fork’tur.

> Bu proje, çekirdek protokol mantığını değiştirmeyi değil; görsel tasarım, kullanılabilirlik ve proje yapısını iyileştirmeyi amaçlar.

---

## ✨ Özellikler

- Xray Core ve v2fly Core desteği
- Modern ve sade kullanıcı arayüzü
- Özelleştirilmiş logo ve tasarım dili
- Abonelik (subscription) desteği
- Manuel sunucu yapılandırması
- GeoIP & GeoSite kural desteği
- Açık kaynak ve şeffaf yapı

---

## 🧩 Desteklenen Çekirdekler

- [Xray Core](https://github.com/XTLS/Xray-core)
- [v2fly Core](https://github.com/v2fly/v2ray-core)

---

## 📱 Gereksinimler

- **Android API 24+**
- Android Studio (geliştirme için)
- Gradle Wrapper

---
Android/data/<package_name>/files/assets
- Geliştirilmiş veri setleri için:
- https://github.com/Loyalsoldier/v2ray-rules-dat
- Resmi listeler manuel olarak içe aktarılabilir:
- Domain listesi
- IP listesi

> Not: Harici `.dat` dosyaları da aynı dizin kullanılarak desteklenir.

---

## 🛠️ Geliştirme

Proje, **Android Studio** üzerinden doğrudan derlenebilir.

Ancak uygulama içinde kullanılan **V2Ray/Xray AAR paketleri güncel olmayabilir**.  
Güncel çekirdek derlemek için aşağıdaki projeler kullanılabilir:

- https://github.com/2dust/AndroidLibV2rayLite
- https://github.com/2dust/AndroidLibXrayLite

### Faydalı Kaynaklar
- Go Mobile: https://github.com/golang/go/wiki/Mobile
- Go Makefile Rehberi: https://tutorialedge.net/golang/makefiles-for-go-developers/

---

## 🧪 Emulator & WSA

Android Emulator üzerinde çalışır.  
Windows Subsystem for Android (WSA) için VPN izni şu komutla verilmelidir:

```bash
appops set <package_name> ACTIVATE_VPN allow


## 📂 GeoIP & GeoSite

- `geoip.dat` ve `geosite.dat` dosyaları aşağıdaki dizinde bulunur:

## 📜 Lisans
⚠️ Sorumluluk Reddi

Bu yazılım eğitim ve araştırma amaçlıdır.
Kullanım sonucu doğabilecek yasal sorumluluklar tamamen kullanıcıya aittir.

## 🤝 Katkı

Pull request’ler ve geri bildirimler memnuniyetle karşılanır.
Büyük değişiklikler için lütfen önce bir issue açınız.
