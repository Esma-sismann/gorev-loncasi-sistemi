#Görev Loncası Sistemi
# 🛡️ Görev Loncası Sistemi (Quest Guild System) v1.0

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

Günlük rutinleri bir RPG mekaniğine dönüştüren bu sistem, modern yazılım prensiplerini terminal tabanlı bir simülasyonla birleştirir.

## 🧠 Yazılım Mimarisi (Architecture)

Proje, **Seperation of Concerns (Sorumlulukların Ayrılması)** prensibine uygun olarak 3 ana modülden oluşur:

### 1. Karakter Motoru (`karakter.py`)
Sistemin kalbidir. Nesne yönelimli programlama (OOP) kullanılarak oluşturulan `Karakter` sınıfı; kapsülleme (encapsulation) mantığıyla karakter verilerini ve XP hesaplama algoritmalarını yönetir.
- **Formül:** $Seviye = (\text{Toplam XP} / 100) + 1$

### 2. Görev Mantığı (`gorev_islemleri.py`)
Veri manipülasyonunu yönetir. Kullanıcıdan alınan girdileri Python sözlük (dictionary) yapılarına dönüştürerek karakter nesnesiyle ilişkilendirir.
- **XP Tablosu:**
  - Kolay: 10 XP
  - Orta: 30 XP
  - Zor: 50 XP

### 3. Uygulama Akışı (`main.py`)
Kullanıcı arayüzü (CLI) ve ana döngüyü (while loop) yöneten orkestrasyon katmanıdır.

## 🛠️ Uygulanan Teknik Konseptler

*   **Modular Programming:** Kodun okunabilirliğini ve bakımını kolaylaştırmak için fonksiyonel ayrıştırma.
*   **Error Handling (Planlanan):** Gelecek versiyonlarda hatalı girdi yönetimi eklenecektir.
*   **Version Control:** Git ve GitHub aracılığıyla sürüm takibi ve dokümantasyon.

## 🎯 Gelecek Geliştirmeler (Roadmap)

- [ ] Verilerin `.json` veya `SQLite` ile kalıcı olarak saklanması.
- [ ] Karakter sınıflarına özel yetenek ağaçları (Skill Tree).
- [ ] Görevlerin tamamlanma sürelerine göre bonus XP çarpanları.

---
📫 **İletişim:** Proje hakkında geri bildirim vermek için Issue açabilir veya benimle GitHub üzerinden iletişime geçebilirsiniz.
## ✍️ Author

**Esma Şişman**
