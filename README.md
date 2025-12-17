# Yazılım Kurulumu, Yönetimi ve Denetim Süreçleri

Bu çalışma, bir yazılımın bilgisayar sistemine tanıtılmasından, güvenlik denetimlerine ve sistemden kaldırılmasına kadar olan tüm teknik süreçleri kapsayan bir rehberdir.

**Hazırlayan:** Hazal Çorbacı  
**Bölüm:** Bilgisayar Programcılığı 1. Sınıf

---

## 📋 Genel Bakış
Yazılım kurulumu; bir yazılımın sistemde yapılandırılması ve çalışmaya hazır hale getirilmesi sürecidir. Bu sürecin temel amaçları şunlardır:
* **Sistem Kararlılığı:** İşletim sisteminin bütünlüğünü korumak.
* **Verimlilik:** Donanım kaynaklarının (CPU, RAM, Disk) optimize edilmesi.
* **Güvenlik:** Potansiyel açıkların ve risklerin minimize edilmesi.

---

## 🛠 Teknik Kurulum Metodolojileri
Kurulum süreçleri, operasyonel ihtiyaçlara göre şu yöntemlerle gerçekleştirilir:

| Yöntem | Teknik Açıklama | Araçlar / Örnekler |
| :--- | :--- | :--- |
| **Manuel** | Kullanıcı onayıyla ilerleyen standart kurulum. | .exe, .msi |
| **Sessiz (Silent)** | Parametreler kullanılarak arayüzsüz yapılan otomatik işlem. | CLI / Scripting |
| **Ağ Dağıtımı** | Merkezi yönetim ile binlerce bilgisayara gönderim. | MSI, SCCM |
| **Portatif** | Kurulum gerektirmeyen, doğrudan çalışan yapılar. | .exe |

---

## 🛡️ Güvenlik ve Doğrulama Denetimleri
Yazılımların güvenilirliği, modern denetim protokolleri ile sağlanır:
* **Bütünlük Kontrolü:** Dosyanın orijinal olduğunu kanıtlamak için **SHA-256** Hash kontrolü yapılır.
* **Dijital İmza:** Yazılım yayıncısının kimliği doğrulanır.
* **İzolasyon:** Şüpheli yazılımlar **Sandbox** ortamında test edilerek denetlenir.
* **Analiz:** Kurulum paketleri zararlı kodlara karşı antivirüs taramasından geçirilir.

---

## ⚙️ Sistem Entegrasyonu ve Yönetimi
Kurulum sırasında gerçekleştirilen kritik sistem işlemleri:
* **Kayıt Defteri (Registry):** Yazılım parametrelerinin işletim sistemine işlenmesi.
* **Ortam Değişkenleri:** PATH tanımlamaları ile sistem genelinde erişim sağlanması.
* **Bağımlılıklar:** Java, .NET ve Python gibi kütüphanelerin kontrolü.
* **Versiyonlama:** Yazılımın sürüm takibi (Örn: **Semantic Versioning - v2.1.0**).

---

## ⚖️ Lisanslama Modelleri
Yazılım dünyasında yaygın olarak kullanılan lisans ve denetim türleri:
* **Açık Kaynak:** Özgürce değiştirilebilen lisanslar (MIT, GNU).
* **Ticari:** Ücretli ve kullanım kısıtlamalı yazılımlar.
* **SaaS:** Bulut tabanlı, abonelik usulü kullanım modelleri.

---

## 🧹 Yazılım Kaldırma ve Optimizasyon
Yazılımın yaşam döngüsü sonunda sistemden tamamen arındırılması:
* **Artık Dosya Temizliği:** `%AppData%` ve `Temp` klasörlerindeki verilerin silinmesi.
* **Registry Temizliği:** Geçersiz kayıt defteri anahtarlarının temizlenmesi.
* **Sistem Kararlılığı:** Kaldırma sonrası kütüphane çakışmalarının denetimi.

---
> **Önemli:** Sadece resmi kaynaklardan kurulum yapılmalı ve sistem kaynakları düzenli denetlenmelidir.
